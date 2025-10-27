# kubernetes-demo

Minikube Installation Steps (Docker Driver)
This method avoids complex virtualization setup by running Kubernetes inside a Docker container.

#  Step 1: Install kubectl (Kubernetes Command-Line Tool)
           Minikube needs kubectl to interact with the cluster once it's running.

            Minikube Installation Steps (Docker Driver)
            This method avoids complex virtualization setup by running Kubernetes inside a Docker container.

#Step 2: Install Docker Engine
         The Docker daemon will serve as the Minikube hypervisor.
         Update packages and install docker.io:

 Bash

 sudo apt update
 sudo apt install -y docker.io
 Start and enable the Docker service:

Bash

sudo systemctl start docker
sudo systemctl enable docker
