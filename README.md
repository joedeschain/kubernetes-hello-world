# Task:

Write a Kubernetes manifest to deploy nginx. The configuration must meet the following requirements:

- [x] Creates a Deployment object for nginx named “hello-world”
- [x] The Deployment should assign the label “app: hello-world” to the nginx pods, which selectors in all Service and Deployment objects should match on
- [x] Creates a Service object for nginx that’s exposed on port 80 within the cluster and port 30080 outside the cluster
- [x] The nginx containers should listen on port 8080
- [x] The nginx containers should run latest stable nginx alpine Docker image  
- [x] The nginx.conf should be defined as a ConfigMap that’s mounted as a volume into the container
- [x] When HTTP requests are made to nginx, it should respond with “Hello, world!”
