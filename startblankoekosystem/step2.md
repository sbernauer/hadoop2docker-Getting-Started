Get the container-Id of the manager
`export managerID=$(docker ps --filter "name=hadoop_manager" --format "{{.ID}}") && echo "ManagerID: $managerID"`{{execute}}

Watch the startUp-logs of the manager-container.
Exit with COMMAND + C
`docker logs -f $managerID`{{execute}}