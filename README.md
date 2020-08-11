## Test Assets

This directory contains examples services for use in playground kubernetes environments.

### Using a service

While each service is unique, we highly recommend the **engage** and **microservices-demo** examples be applied to your cluster
for both troubleshooting, reconaissance, and emulation of an actual platform.

To deploy to a cluster,

```
kubectl apply -f microservices-demo.yaml
```

## Notes:

* Example services with multiple objects are isolated to their own namespace
* A few, like Engage and Kuard are not namespaced and just deployed to whichever namespace your environment is set to.
* At the top of each service yaml, you can see a link for more information and/or the main page for that service


