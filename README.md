# dockerSetup

A simple react Application showing use of deployed using docker

## How to Run

  Go to the folder with the react application<br/>
  docker build -t  dockerdemo . <br/>
  docker ps -a and search for the container with name dockerdemo and note its id<br/>
  docker run -p 3000:3000 "dockerid"
