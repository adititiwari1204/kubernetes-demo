# kubernetes-demo

Minikube Installation Steps (Docker Driver)
This method avoids complex virtualization setup by running Kubernetes inside a Docker container.

#  Step 1: Install kubectl (Kubernetes Command-Line Tool)
           Minikube needs kubectl to interact with the cluster once it's running.

            Minikube Installation Steps (Docker Driver)
            This method avoids complex virtualization setup by running Kubernetes inside a Docker container.
#  Step 2: Install Docker Engine
         The Docker daemon will serve as the Minikube hypervisor.
         Update packages and install docker.io:

         Bash

        sudo apt update
        sudo apt install -y docker.io
        Start and enable the Docker service:

        Bash

        sudo systemctl start docker
        sudo systemctl enable docker
#  Step 3: Start Minikube
           Now that all prerequisites and permissions are correct, start the cluster using the Docker driver:

           Bash

           minikube start --driver=docker
 <img width="672" height="495" alt="Screenshot 2025-10-27 225846" src="https://github.com/user-attachments/assets/1159d80f-b3f7-4a28-8a18-84769d5277af" />

           kubectl get pods

 <img width="1024" height="149" alt="Screenshot 2025-10-27 230135" src="https://github.com/user-attachments/assets/76b1b9f4-1dcc-4bff-8836-7a58a54f6c0d" />


