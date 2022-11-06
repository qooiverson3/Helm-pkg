## Using Helm
This guide explains the basics of using Helm to manage packages on your Kubernetes cluster. It assumes that you have already `installed` the Helm client.

####Three Big Concepts
A *Chart* is a Helm package. It contains all of the resource definitions necessary to run an application,tool,or service inside of a Kubernetes cluster. Think of it like the Kubernetes equivalent and shared. It's like Perl's `CPAN archive` or the `Fedora Package Database`, but for Kubernetes packages.

A *Repository* is the place where charts can be collected and shared. It's like Perl's `CPAN archive` or the `Fedora Package Database`

