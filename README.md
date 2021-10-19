
# k8-demo

https://www.youtube.com/watch?v=s_o8dwzRlu4&ab_channel=TechWorldwithNana

## Commands
`kubectl apply -f mongo-config.yaml` - Creates config map
<br />
`kubectl apply -f mongo-secret.yaml` - Create secret
<br />
`kubectl apply -f mongo.yaml` - Creates deployment & service
<br />
`kubectl apply -f webapp.yaml` - Same

    kubectl get all
    kubectl describe service webapp-service
    kubectl logs {instance-name} -f
