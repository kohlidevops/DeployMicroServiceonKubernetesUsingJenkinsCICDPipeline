# To Deploy a 10 MicroServices on Amazon Elastic Kubernetes Cluster Using Jenkins CICD Pipeline

Step -1: To setup a base instance

![image](https://github.com/user-attachments/assets/d5e4fb2c-4c4c-4168-864e-a2d6822165df)

Step -2 To create an IAM user with below policies

![image](https://github.com/user-attachments/assets/0f869b12-ab4d-4ec3-9a93-44e70e7f1ac5)

Step -3: Create EKS Cluster

![image](https://github.com/user-attachments/assets/cf950bf2-095f-4693-857c-37e0b542e258)

Step -4: Create a Worker Node group

![image](https://github.com/user-attachments/assets/29121cd4-d434-436a-b511-b438f68420d2)

Step -6: To create a namespace

![image](https://github.com/user-attachments/assets/c7ea9ef5-1de7-4a03-85a8-68c5d2706628)

Step -7: To create a Service Account

![image](https://github.com/user-attachments/assets/4cd8edb6-c933-421f-881b-c6078fedbb75)

Step -8: To create a Role

![image](https://github.com/user-attachments/assets/9fe36460-6cb9-4939-986a-4a350dacbdcc)

Step -9: To bind the role to the Service Account

![image](https://github.com/user-attachments/assets/79ed5c65-e9f3-4a5f-a331-fbc6faadb514)

Step -10: To create a secret token in the desired namespace

![image](https://github.com/user-attachments/assets/0218bb25-c94e-4c87-aae1-5f89d5881bc5)

Step -11: To install Jenkins and docker



Step -12: To access the jenkins

![image](https://github.com/user-attachments/assets/c6e685d7-24aa-48bc-8841-1e60833d1e42)

Install suggested plugins

![image](https://github.com/user-attachments/assets/b80a6079-bf09-46d0-99e0-926819b2c594)

Create a new admin user

![image](https://github.com/user-attachments/assets/f582adf8-e7a1-428c-86ef-753820f4276f)

To welcome your Jenkins dashboard

![image](https://github.com/user-attachments/assets/f532ac44-2a6a-4271-8408-b825f3cde840)

To install the plugins listed below in Jenkins console

```
docker (all plugins)
kubernetes (all plugins)
Multibranch scan webhook trigger
```

To setup docker credentials in Jenkins

![image](https://github.com/user-attachments/assets/3a81fd17-7f5c-4c3e-a1f7-f4970da2545a)

To setup github and kubernetes credentials in Jenkins

![image](https://github.com/user-attachments/assets/b4ecec38-9977-4e5f-954a-b1b3c9331a1d)

To create a new job with multibranch pipeline

![image](https://github.com/user-attachments/assets/bbdbdf38-9be2-443e-a413-a8cfd3f85d58)

To add the webhook inGithub

![image](https://github.com/user-attachments/assets/663e22a6-2fa1-4599-8a0e-69041b036d4a)

To add a git from source

![image](https://github.com/user-attachments/assets/deb7ec35-5859-4c35-aaca-81519815a04c)

To scan multibranch pipeline trigger

![image](https://github.com/user-attachments/assets/7917be0e-3788-48bd-80d6-32fe7388ad01)


