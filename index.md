---
layout: default
title: Summary
---

I am currently a junior at North Carolina State University majoring in Applied
Mathematics and Electrical Engineering. I am interested in a variety of fields
including quantitative finance, software engineering, and data science. I also contribute
to open-source projects in Python's data science stack; particularly [Dask](https://dask.org/).


### Open-source Work

* Currently working on developing a Kubernetes Operator for Dask that follows the [operator pattern](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/). The Operator will be a replacement for [dask_kubernetes.KubeCluster](https://kubernetes.dask.org/en/latest/kubecluster.html) that uses Kubernetes [Custom Resource Definitions](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/) (CRDs). Dask clusters would be created as CRDs on Kubernetes with the Operator communicating with the [Dask Scheduler](https://docs.dask.org/en/stable/scheduler-overview.html) to intelligently scale workers up and down. By "intelligently," I mean with [Horizontal Pod Autoscaler](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/) (HPA) style autoscaling.
* Added support to support for multiple worker groups to the [Dask Helm Chart](https://github.com/dask/helm-chart). Dask users can now configure multiple Dask worker groups on Kubernetes with different hardware configurations. For example, this feature enables running high memory or GPU workers and annotating them to run specific tasks. Users can also manage and scale their Dask cluster easily from Python. I wrote a blog post about it on the [Dask Blog](https://blog.dask.org/2022/02/17/helm-multiple-worker-groups).

### Other Projects
A record of my projects and contributions to open source is available on GitHub:
[github.com/Matt711](https://github.com/Matt711).

I write about my work at [medium.com/@dseematt](https://medium.com/@dseematt).