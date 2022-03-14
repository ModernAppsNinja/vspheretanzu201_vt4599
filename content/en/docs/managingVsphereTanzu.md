---
title: "Managing vSphere with Tanzu"
date: 2020-10-12T18:34:25-07:00
weight: 1010
draft: false
---

- [Supervisor Cluster Components](#supervisor-cluster-components)
- [Supervisor Cluster Namespaces](#supervisor-cluster-namespaces)
- [Harbor and the Content Library](#harbor-and-the-content-library)
  - [Registry Service](#registry-service)
  - [Content Library](#content-library)
- [Managing vSphere Lab](#managing-vsphere-lab)

## Supervisor Cluster Components

VMware Tanzu Kubernetes Grid Service for vSphere is a Kubernetes experience that is tightly integrated with vSphere 7.0. Tanzu Kubernetes Grid Service runs on Supervisor Clusters in vSphere with Tanzu to create Kubernetes conformant clusters that have been optimized for vSphere.

{{< youtube VA66bXKw-aA >}}

## Supervisor Cluster Namespaces

{{< youtube wLIV9knoBVg >}}

## Harbor and the Content Library

### Registry Service

The Registry Service is one of the Cloud Foundation services provided by vSphere with Tanzu. You can enable a private image registry on a Supervisor Cluster using the Registry Service. Enabling the Registry Service will deploy an instance of Harbor on the cluster. All Namespaces created on a Supervisor Cluster are represented as projects in the private registry and appropriate RBAC is configured based on the permissions of the Namespace object.

### Content Library

The virtual machine images used to deploy Tanzu Kubernetes Grid cluster on vSphere with Tanzu are sourced from a public content delivery network (CDN). vSphere with Tanzu uses a subscribed Content Library to automatically download and synchronize new versions of the TKG virtual machine image and corresponding Kubernetes releases.

{{< youtube wzegdUYnttU >}}

## Managing vSphere Lab

Please complete "Module 2 - Managing vSphere with Tanzu" in the Hands-on-lab [HOL-2213 vSphere with Tanzu](https://labs.hol.vmware.com/HOL/catalogs/lab/10402)

**Section Complete. Please use the navigation bar to proceed to the next page**
