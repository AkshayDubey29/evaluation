**This repository will push the Docker Image to bocker hub repository with the automated build.**

To pull the image and run please follow below steps:-

# Pre-requisite:-

1. you need to have docker running on your machine.
2. Application will expect to have the mysql database running and serving on port 3306. (For this particular repostory we have configured the port and service within the K8s cluster).
              Database name:- evaluation
              Password for root: root
3. To create the mysql database within the K8s Cluster please do follow below github repo. (This will also create the evaluation database in mysql)
4. Application can be instlled through helm charts which you can find at the below github location.
5. Helm chart will create a service named as "evaluation-evaluation-ui" which will serve on NodePort.





# Contact:-

XebiaLabs
