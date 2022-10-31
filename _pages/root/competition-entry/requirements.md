---
title: "Competition Entry"
permalink: /competition-entry/requirements/
---

## Solver Requirements


### Execution Environment

* The evaluations will be run on Linux machines with up to **8 GB memory** made available.
* We request that solvers be submitted as Docker images that containerize executables using only **a single core (i.e., no parallel processes/threads)**.
* Each submission will be evaluated using [Singularity](https://sylabs.io/guides/2.6/user-guide/index.html) 
with restrictied computing resource per image as described in the [Tasks](./tasks.md) descriptions.


### Containerizing Solvers in Docker
We will be accepting submissions as Docker images. Participants have two options:
1. _(PREFERRED)_ Create a Docker project and upload its image to [Dockerhub](https://hub.docker.com/).
2. Directly submit a Docker project (as opposed to the already built image) with all necessary local files to build an image


### How to Containerize Solvers in Docker
Each image should be equipped with an executable and a folder to mount the host directory during evaluation.
While running the image, the names of the files will be passed as environment variables (see section below on
Environment Variables) so the image can execute bash commands with them.

* **[Please checkout a minimal example docker project](https://github.com/dechterlab/daoopt-docker)**

#### Environment Variables for limiting time and memory
We encourage teams to each limit their own solvers' time and memory usage to prevent premature termination process termination.  We will use **environment variables** to pass memory and time limits as follows
* `TIMESEC` is the time limit in seconds.
* `MEMKB` is the memory limit in KB.
    * we will be passing a MEMKB value of 8000000

***Important Note:*** after time or memory limits are exceded, the program will be forceably terminated which can result in premature outputs that result in invalid results

#### Environment Variables for reading/writing 
We will use **environment variables** to pass the path of the input and output files and
followings are the example of values for these environment variables
* `MODEL`: /code/problems/pedigree-1.uai
* `EVID`: /code/problems/pedigree-1.uai.evid
* `QUERY`: /code/problems/pedigree-1.uai.query
* `RESULT`: /code/problems/pedigree-1.uai.MMAP
* `QUERY` filename is only relevant to the marginal MAP task, so solvers working on the other three tasks should ignore this file.
* Although the name of the files can be arbitrary, we will use a convention that extends the name of the `MODEL` files.
  * `EVID` files add `.evid', `QUERY` files add `.qeury`, `RESULT` files add `.PR/.MAR/.MPE/.MMAP' depending on the task, 

#### Directories
* Each solver should assume that necessary files will be mounted under `/code/problems` folder inside the image.
Please create `/problems` directory when you `COPY` your necessary files into image, and
put all the codes under `/code` by `COPY . /code`
* **[Please checkout a minimal example docker project](https://github.com/dechterlab/daoopt-docker)**

The file formats are described here:
* [Model Format](../file-formats/model-format.md)   
* [Evidence Format](../file-formats/evidence-format.md)
* [Query variables](../file-formats/query-format.md) (only applies to the marginal MAP task)
* [Result format](../file-formats/result-format.md)
   
