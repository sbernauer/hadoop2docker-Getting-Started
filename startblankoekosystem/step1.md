Pull the needed scripts from git-repo
`git clone https://github.com/sbernauer/Hadoop2docker.git`{{execute}}

Initialize a swarm with the following command
`docker swarm init`{{execute}}

See the parameters that the Script takes
`startUpBlankContainers.sh --help`{{execute}}

Start a Oekosystem with 1 Manager and 2 Nodes
`startUpBlankContainers.sh -a 2`{{execute}}