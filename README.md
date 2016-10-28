# Docker DD Compose

The Docker DD Compose is a collection of the shell command to manage and manipulate Docker throw the docker-compose.

## Requirements

* [Docker](http://www.docker.com/)
* [docker-compose](https://docs.docker.com/compose/install/)
* [peco](https://github.com/peco/peco)

## Getting Started

STEP 1:

clone this repository.

```bash
git clone https://github.com/nutsllc/docker-dd-compose.git
```

STEP 2:

Add line below to ``~/.bash_profile`` or ``~/.bashrc`` with your own value.

```bash
export DDD_HOME=${HOME}/dev/src/github.com/nutsllc/docker-dd-compose
export DDD_SEARCH_DIR=${HOME}/dev/src
source ${DDD_HOME}/docker-dd-compose
```

* ``DDD_HOME`` is the Docker DD Compose installed directory.  
* ``DDD_SEARCH_DIR`` is the base directory that search ``docker-compose.yml`` files recursively.

## Usage

Run docker-dd-compose commands (DDD comand) below in a shell.

### List of the Docker DD Compose commands

|Command|Description|
|:---|:---|
|DDD|It shows all the docker-compose.yml status. (running, stopped, and so on)|
|DDDup|It runs the container(s) that is/are defined in the specific ``docker-compose.yml``.|
|DDDdown|It stops and removes the container(s) that is/are defined in the specific ``docker-compose.yml``.|
|DDDstart|It starts the container(s) that is/are defined in the specific ``docker-compose.yml``.|
|DDDstop|It stops the container(s) that is/are defined in the specific ``docker-compose.yml``.|
|DDDrm|It removes the container(s) that is/are defined in the specific ``docker-compose.yml``.|
|DDDrestart|It restart the container(s) that is/are defined in the specific ``docker-compose.yml``.|
|DDDlogs|It shows logs the container(s) that is/are defined in the specific ``docker-compose.yml``.||
|DDDps|It shows the container processes.||
|DDDconfig|It shows the contents of the specific ``docker-compose.yml``.|

