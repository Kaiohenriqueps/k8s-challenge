# Challenge: Surfind a Pod

Create a Pod with a single container and the image learnk8s/fundamentals:surfing.

The Pod exposes a web server.

Visit the page served by the Pod to solve the challenge.
```
$ kubectl port-forward pod/<pod_name> 8081:<app_port>
```