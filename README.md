# NAOqi Python SDK using Docker
Use Docker to build the [NAOqi Python SDK](http://doc.aldebaran.com/2-1/dev/python/install_guide.html) for Ubuntu 17.04 and NAOqi 2.1.4.13

## Installation

* Install [Docker](https://www.docker.com).
* Clone this repo `$ git clone https://github.com/MODatUniSA/naoqi-docker.git`
* Move into the directory `$ cd naoqi-docker`
* Build the container `$ docker build -t naoqi-python .`
* Run the container `$ docker run -it naoqi-python bash`
* cd into the SDK `$ cd pynao*`
* Run python `$ python`
* Import NAOqi `>> import naoqi`

### TODO

* ~~Write the Dockerfile~~.
* Open the port to NAO.
* Test with our NAO.
* Write up installation documentation for macOS, Linux, Windows.

