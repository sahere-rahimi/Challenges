Task2: Create a Helm chart to deploy a NodeJS or Laravel application on Kubernetes and expose it in a proper way.


install the chart using the following command:
git clone <THE_PROJECT_URL>
cd <THE_PROJECT>
helm install challenge2 .

You can obtain the NodePort address using the following command:
kubectl get services challenge2-service