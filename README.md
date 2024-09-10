# k8s-lab3

1-Create a deployment called my-first-deployment of image nginx:alpine in the default namespace.
Check to make sure the deployment is healthy. :
    ![alt text](image.png)

2-Scale my-first-deployment up to run 3 replicas.
Check to make sure all 3 replicas are ready
    ![alt text](image-1.png)

3-Scale my-first-deployment down to run 2 replicas.
    ![alt text](image-3.png)

4-Change the image my-first-deployment runs from nginx:alpine to httpd:alpine .
    ![alt text](image-2.png)

5-Delete the deployment my-first-deployment
    ![alt text](image-11.png)

6-Create deployment from the below yaml :
    ![alt text](image-5.png)

7-How many ReplicaSets exist on the system now?
    ![alt text](image-6.png)

8-How many PODs exist on the system now?
    ![alt text](image-7.png)

9-Out of all the existing PODs, how many are ready?
    ![alt text](image-8.png)

10-What is the image used to create the pods in the new deployment?
    ![alt text](image-9.png)

11-Why do you think the deployment is not ready?
 because the image does not exist :
    ![alt text](image-10.png)
