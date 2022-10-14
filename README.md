# Dockerized Openfold With Backend

## Prerequisites

- Have Docker installed on your machine. If you don't have Docker installed, you can find instructions for your operating system [here](https://docs.docker.com/install/).
- Have CUDA installed on your machine. If you don't have CUDA installed, you can find instructions for your operating system [here](https://developer.nvidia.com/cuda-downloads).
- Have Python 3.9 installed on your machine. If you don't have Python 3.9 installed, you can find instructions for your operating system [here](https://www.python.org/downloads/).
- Install streamlit, py3Dmol and requests using pip. If you don't have pip installed, you can find instructions for your operating system [here](https://pip.pypa.io/en/stable/installing/).

## How to Run
- Clone this repository
- Navigate to the `Docker Backend` directory of this repository
- Run `docker build -t openfold .` to build the Docker image
- Run `docker run -d -p 8000:8000 openfold` to create and run a container from the image
- Navigate to the `Frontend` directory and run `steramlit run frontend.py` to run the frontend