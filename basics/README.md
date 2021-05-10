# Challenge: Back to Basics

- Create a Deployment with two replicas.
- Create a Pod with a single container and the image learnk8s/fundamentals:basics.
- Create a Service for the two Pods.
- Create an Ingress manifest that routes the traffic to the Service.

:exclamation: Please use an Ingress with api version networking.k8s.io/v1 (this requires Kubernetes version 1.20 or greater).

:exclamation: To check in which port the app is running, please use the command:

```
$ kubectl logs pod/<pod_name> -f
```

Then, port-forward to check the answer:
```
$ kubectl port-forward pod/<pod_name> 8081:<app_port>
```