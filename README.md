# Kubernetes Basics for Developers (german)

from my presentation at Java Usergroup Karlsruhe - 18.07.2018

## video 

https://www.youtube.com/watch?v=BgJfnGrCQDE

---
## slides

[JUGKA-kubernetes-20180718.pdf (german)](https://github.com/cy4n/talk-kubernetes-basics/blob/master/JUGKA-kubernetes-20180718.pdf)

---
## demo resources 



the resources can be deployed to demonstrate how to run a Hello SpringBoot 2 app [cy4n/hello](https://github.com/cy4n/hello) in Kubernetes.

It utilizes kubernetes resources like Secrets and ConfigMaps to provide basic Spring external configuration parameters

in my demo i applied the configuration yaml files in the following order:

1. deployment.yml # to provide basic pod and replicasets
2. service.yml    # make it discoverable in k8s
3. ingress.yml    # serve it through nginx-ingress 

then a more advanced config by running 

4. deployment-health.yml # add k8s probes
5. deployment-advanced.yml # bump container version and add spring config

---

###### thank you Java Usergroup Karlsruhe for having my talk
###### thank you synyx for enabling me
###### thank you audience for the awesome feedback and discussion
