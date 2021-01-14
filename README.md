# dockerSetup

A simple react Application showing use of deployed using docker

##How to Run

  Go to the folder with the react application
  docker build -t  dockerdemo .
  docker ps -a and search for the container with name dockerdemo and note its id
  docker run -p 3000:3000 <<dockerid>>
