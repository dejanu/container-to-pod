# container-to-pod
Container to Pod: A 1-Hour Expedition

## Slides

* Save slides on local
```bash
curl https://raw.githubusercontent.com/dejanu/container-to-pod/main/masterclass_slides.key -o masterclass_slides.key
```

## Killercoda labs

* Hands-on Docker and K8s labs [killercoda.com/dejanualex/](https://killercoda.com/dejanualex/)


## Articles
### WIP

* [containers-empathic-manifesto](https://www.linkedin.com/pulse/containers-empathic-manifesto-alexandru-dejanu-1xuzf/)

* [kubernetes-more-than-afterthought-part-I](https://www.linkedin.com/pulse/kubernetes-more-than-afterthought-part-i-alexandru-dejanu-tcc5f/)

## Tidbits

* Containers are often referred to as “lightweight” because they share the machine’s OS kernel. Containers are just a fancy way to run a process, not lightweight VMs, a container provides operating-system-level virtualization by abstracting the "user space".

* We don't put `ssh, curl, wget` into containers we just package the app and its dependencies.

* Usually, when deploying an application, you're gonna need more than one tool, a proper version for each tool, updated documentation, and not least of all proper coordination in terms of workflow.