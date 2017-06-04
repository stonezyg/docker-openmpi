docker-openmpi
---

base package for docker cluster with openmpi

# with docker compose

1. build and deploy MPI cluster
    ```
    $ docker-compose build
    $ docker-compose up -d
    ```
2. login to master node
    ```
    $ ssh -p 2222 localhost
    ```
3. run mpi program from master node
    ```
    $ mpirun -np 16 hostname
    252f9f5abc18
    252f9f5abc18
    252f9f5abc18
    252f9f5abc18
    fa00f144c7be
    0ebd38ff982e
    fa00f144c7be
    0ebd38ff982e
    fa00f144c7be
    0ebd38ff982e
    fa00f144c7be
    0ebd38ff982e
    4c1364ddf9d9
    4c1364ddf9d9
    4c1364ddf9d9
    4c1364ddf9d9
    ```

# with swarm

# with kubernetes

