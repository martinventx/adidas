---
title: Kubernetes Essentials
revealOptions:
    transition: 'none'
    slideNumber: 'true'
---

# Outline

* Deploy your first application
* **Pod**s
* **Service**s
* **Deployment**s

---

# Connecting to a VM

We have created a VM that has everything you need to get started with docker and kubernetes.

We will distribute an SSH key (the same one for everyone) and an IP address (different for everyone).

Then ssh into the VM using ssh (linux/mac) or Putty (Windows):

ssh -i participant-key traininguser@<IP ADDRESS>

---

# Creating a cluster

Once logged into the VM, run the provided script (if you haven't done already) `./create-cluster-gke-norbac.sh`.

This creates a kubernetes cluster on Google Container Engine. This has a similar feature set to the open source version of Kubernetes, but is fully managed.
