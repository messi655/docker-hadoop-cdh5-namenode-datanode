1. Run script to build images:
  - ./build-docker-images.sh hadoop-namenode
  - ./build-docker-images.sh hadoop-datanode

2. Run start containers
  - ./start-container.sh number_of_datanode cluster_name
  - EX: ./start-container.sh 2 master
