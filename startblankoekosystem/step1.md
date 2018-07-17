Initialize a swarm with the following command
`docker swarm init`{{execute}}

Pull the needed scripts from git-repo
`git clone https://github.com/sbernauer/Hadoop2docker.git && cd Hadoop2docker`{{execute}}

See the parameters that the Script takes
`./startUpBlankContainers.sh --help`{{execute}}

Start a Oekosystem with 1 Manager and 2 Nodes.
It has the default name "hadoop".
With the flag -r we will use the public docker hub instead of our local registry, the flag -m and -n specify the images for the manager and node.
`./startUpBlankContainers.sh -a 2 -r sbernauer -m manager:centOS -n node:centOS`{{execute}}