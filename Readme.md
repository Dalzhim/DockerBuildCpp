# Installation

1. Install Docker
1. `git clone https://github.com/Dalzhim/DockerBuildCpp.git`
1. `cd DockerBuildCpp`
1. `docker build -t toolchain .`
1. `docker run --rm -it -v $(pwd)/src:/Sources -v $(pwd)/Build:/Build -v $(pwd)/Install:/Install --user $(id -u):$(id -g) toolchain`
