# hadoop-education-stepik
Hadoop examples

## Istruction
1. Download docker source: 

$ git clone https://github.com/big-data-europe/docker-hadoop.git

2. $ cd docker-hadoop/

3. edit docker-compose.yaml

$ nano docker-compose.yaml

4. Run Hadoop

$ docker-compose up

5. Upload test file 

$ docker cp ~/Downloads/plazma.JPG namenode:/

6. Run bash inside namenode container

$ docker exec -it namenode /bin/bash (Linux)
$ winpty docker exec -it namenode bash (Windows Git Bash)

## Resources
### Check health
http://localhost:9870/dfshealth.html
