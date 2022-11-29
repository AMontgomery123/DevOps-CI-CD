# Lab 10 CI/CD
## Part 1
Part 1 was rather simple. I used the proper starter files after installing gradle and pushed the changes to the new repository. I checked in the Actions tab on Github and revealed that it successfully ran the workflow.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images.PNG)

## Part 2
I first began by creating a Kubernetes cluster.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-3.PNG)

I then enabled the necessary APIs that were provided and in the provided tutorials before creating a service account for my project. I gave them developer privileges and granted access to the cluster. I added a key to the service account and downloaded the file.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-1.PNG)

Next, I added repository secrets in the github project based on the Kubernetes project name and the information from the json key file downloaded previously.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-2.PNG)

I then modified information in the google.yml file so it corresponded to the name of my kubernetes cluster. Then, I created a release on the Github project.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-4.PNG)

It began to run a new workflow automatically.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-5.PNG)

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-6.PNG)

Furthermore, it automatically created a service and workload on Google Cloud.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-7.PNG)

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-8.PNG)

I created an ingress based on the generated service using the Google Cloud interface.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-9.PNG)

To conclude and verify the project was running correctly, I followed the link.

![spring1](https://github.com/AMontgomery123/DevOps-CI-CD/tree/main/images/images-10.PNG)
