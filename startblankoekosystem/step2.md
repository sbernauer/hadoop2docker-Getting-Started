Get the container-Id of the manager
`export managerID=$(docker ps --filter "name=hadoop_manager" --format "{{.ID}}) && echo "ManagerID: $managerID"`{{execute}}
