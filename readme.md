usage:

    # start server:
    docker-compose up -d

    # start client:
    docker-compose run --rm zookeeper /bin/bash
    zkCli.sh -server <IP>:2181
