# Challenge: Inspecting a Pod

Create a Pod with a single container and the image learnk8s/fundamentals:inspect.

You should deploy the Pod in your cluster.

The container creates a well_done.txt file in the /app folder.
```
$ kubectl exec -it pod/<pod_name> -- bash
```