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
- [Section 2 Test](#section-2-test)
  - [Instructions](#instructions)
    - [Full Test Instructions](#full-test-instructions)
    - [Test Answer Response Sheet](#test-answer-response-sheet)
  - [Section 2 Test Questions](#section-2-test-questions)

## Supervisor Cluster Components

VMware Tanzu Kubernetes Grid Service for vSphere is a Kubernetes experience that is tightly integrated with vSphere 7.0. Tanzu Kubernetes Grid Service runs on Supervisor Clusters in vSphere with Tanzu to create Kubernetes conformant clusters that have been optimized for vSphere.  

{{< youtube VA66bXKw-aA >}}

## Supervisor Cluster Namespaces

{{< youtube wLIV9knoBVg >}}

## Harbor and the Content Library

### Registry Service

The Registry Service is one of the Cloud Foundation services provided by vSphere with Tanzu. You can enable a private image registry on a Supervisor Cluster using the Registry Service. Enabling the Registry Service will deploy an instance of Harbor on the cluster. All Namespaces created on a Supervisor Cluster are represented as projects in the private registry and appropriate RBAC is configured based on the permissions of the Namespace object.

### Content Library

The virtual machine images used to deploy Tanzu Kubernetes Grid cluster on vSphere with Tanzu are sourced from a public content delivery network (CDN).  vSphere with Tanzu uses a subscribed Content Library to automatically download and synchronize new versions of the TKG virtual machine image and corresponding Kubernetes releases.

{{< youtube wzegdUYnttU >}}

## Managing vSphere Lab

Please complete "Module 2 - Managing vSphere with Tanzu" in the Hands-on-lab [HOL-2213 vSphere with Tanzu](https://labs.hol.vmware.com/HOL/catalogs/lab/10402)

## Section 2 Test

All Modernapps Ninja learning content is publicly accessible and available openly, however a free membership is required to take tests and recieve a certificate of completion for the course. You must first [join the community](https://modernapps.ninja/about/membership/) and register for this course per the instructions in the course introduction section before attempting to submit a test.

Ninja tests use devops tools and processes so the testing system itself provides both experience with and validation of foundational devops skills. 

<details><summary>Expand this section to see a video overview of test taking instructions.</summary>
{{< youtube J_nV5YPypqs >}}
</details>

### Instructions

This test uses automated grading, you must follow the instructions exactly to ensure automated grading will complete successfully. 

To complete the test you must review the questions on this page, and fill in your answers on a seperate answer sheet provided below. We recommend opening the answer sheet for the test in a seperate browser tab so you can fill in the answers as you proceed through the questions. 

Every question in this test is titled "Question" followed by its order, for example Question1, Question2 etc...

All questions will provide a list of possible answers. Each possible answer is represented by a lowercase letter, the first response is option "a", the second is option "b" and so on, as shown in the example questions below. 

The Answer sheet will open in Github's web-based editor, similar to the image shown below:

![Example Test Response Sheet](/vspheretanzu201_vt4599/admin/assets/images/blank_test_screen_example.png)  

After you fill in your answer sheet, you will submit  your responses as a git [pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) following the instructions provided below, which will trigger a workflow that will grade your responses and provide your test grading sheet. 

#### Full Test Instructions

If this is the first test you have taken, or if you have an questions at all about how to propely complete the test answer sheet or the test grading service, please review the full [How to Take a Test Instructions](https://modernapps.ninja/course_repo_template_ct8279/docs/reference/testinstructions/).  

It is important that you follow the instructions carefully to ensure the automated grading process completes successfully.

#### Test Answer Response Sheet

Please right click the following link to the test answer response sheet and select to open it in a new tab. The questions for this test will be provided below in this page, but you will need to enter your responses in the answer response sheet. 

[test2 Answer Response Sheet](https://github.com/modernappsninja/vspheretanzu201_vt4599/edit/main/static/admin/userdata/tests/test2.yml)  

### Section 2 Test Questions

#### **Question1:** vSphere with Tanzu Services include:  <!-- omit in toc -->

**Please select 5 choices:**

```yml
Answers:
  a: Registry Service
  b: Load Balancer Service
  c: Storage Service
  d: Network Service
  e: Tanzu Kubernetes Grid Service
  f: Cluster Service
  g: vSphere Pod Service
```

**Section Complete. Please use the navigation bar to proceed to the next page**
