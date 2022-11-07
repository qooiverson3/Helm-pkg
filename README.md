## Helm
#### Three Big Concepts
A *Chart* is a Helm package. It contains all of the resource definitions necessary to run an application,tool,or service inside of a Kubernetes cluster. Think of it like the Kubernetes equivalent and shared. It's like Perl's `CPAN archive` or the `Fedora Package Database`, but for Kubernetes packages.

A *Repository* is the place where charts can be collected and shared. It's like Perl's `CPAN archive` or the `Fedora Package Database`

A *Release* is an instance of a chart running in a Kubernetes cluster. One chart can often be installed many times into the same cluster. And each time it is installed, a new *release* is created. Consider a MySQL chart. If you want two databases running in your cluster, you can install that chart twice. Each one will have its own *release*, which will in turn have its own *release name*.

#### Reference
- https://helm.sh/