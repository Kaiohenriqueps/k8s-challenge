# Challenge: creating a Pod

Create a Pod with a single container.

The container should use the learnk8s/fundamentals:pod image.

Deploy the Pod into a cluster, and you will find the solution to the challenge in the Pod's logs.
```
$ kubectl logs pod/<pod_name> -f
```