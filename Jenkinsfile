node ('docker') {
  stage 'Code Checkout'
  git url: 'https://github.com/mikeagileclouds/swarm-microservice-demo-v1/cluster-detailed.png'
  sh 'ls -la'

  stage 'Docker image build'
  echo "${TEST}" 
  sh 'docker version'
  
  stage 'Docker image push'
  sh 'docker info'
}

node ('docker') {
  stage 'Launch docker container'
  echo "placeholder for launch docker container"
}
