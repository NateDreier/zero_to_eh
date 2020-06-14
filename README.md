# Goal
Come up with a nice toolchain to go from nothing to a Kubernetes cluster + arbitrary deployments to that cluster.

## Current Idea
Built on AWS  
- Future goal, build on AWS and GCP, going for a little multicloud spicyness.
- Prometheus for monitoring

Packer to build the AMI's  
- That Packer Build will have an Ansible playbook(s) run against it to prep it to be a Kubernetes Node (or Master) as well as general hardening.

Terraform to manage the infrastructure.  

TBD: Ansible to manage deploying to Kubernetes.
