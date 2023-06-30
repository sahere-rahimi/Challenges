# Task2: Create a Helm chart to deploy a NodeJS or Laravel application on Kubernetes and expose it in a proper way.

Install the chart using the following command:
<br>
git clone <THE_PROJECT_URL>
<br>
cd <THE_PROJECT> 
<br>
helm install challenge2 .
<br>
***
You can obtain the NodePort address using the following command:
<br>
kubectl get services challenge2-service
