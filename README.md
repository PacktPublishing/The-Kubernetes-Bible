


# The Kubernetes Bible

<a href="https://www.packtpub.com/product/the-kubernetes-bible/9781838827694?utm_source=github&utm_medium=repository&utm_campaign=9781838827694"><img src="https://static.packt-cdn.com/products/9781838827694/cover/smaller" alt="The Kubernetes Bible" height="256px" align="right"></a>

This is the code repository for [The Kubernetes Bible](https://www.packtpub.com/product/the-kubernetes-bible/9781838827694?utm_source=github&utm_medium=repository&utm_campaign=9781838827694), published by Packt.

**The definitive guide to deploying and managing Kubernetes across major cloud platforms**

## What is this book about?
With its broad adoption across various industries, Kubernetes is helping engineers with the orchestration and automation of container deployments on a large scale, making it the leading container orchestration system and the most popular choice for running containerized applications. 

This book covers the following exciting features:
* Manage containerized applications with Kubernetes
* Understand Kubernetes architecture and the responsibilities of each component
* Set up Kubernetes on Amazon Elastic Kubernetes Service, Google Kubernetes Engine, and Microsoft Azure Kubernetes Service
* Deploy cloud applications such as Prometheus and Elasticsearch using Helm charts
* Discover advanced techniques for Pod scheduling and auto-scaling the cluster
* Understand possible approaches to traffic routing in Kubernetes

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1838827692) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
apiVersion: v1
kind: Pod
metadata:
 name: nginx-Pod
```

**Following is what you need for this book:**
This book is for software developers and DevOps engineers looking to understand how to work with Kubernetes for orchestrating containerized applications and services in the cloud. Prior experience with designing software running in operating system containers, as well as a general background in DevOps best practices, will be helpful. Basic knowledge of Kubernetes, Docker, and leading cloud service providers assist with grasping the concepts covered easily.

With the following software and hardware list you can run all code files present in the book (Chapter 1-21).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-21 | Kubernetes >= 1.17 | Windows, Mac OS X, and Linux (Any) |
| 1-21 | Kubectl >=1.17 | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781838827694_ColorImages.pdf).

## Errata
 * Page 109: **kubectl run nginx-Pod --image nginx --label " tier=frontend"** _should be_ **kubectl run nginx-pod --image nginx --labels " tier-frontend"**

### Related products
* Operational challenges with Kubernetes [[Packt]](https://www.packtpub.com/product/kubernetes-in-production-best-practices/9781800202450?utm_source=github&utm_medium=repository&utm_campaign=9781800202450) [[Amazon]](https://www.amazon.com/dp/1800202458)

* Cloud Native with Kubernetes [[Packt]](https://www.packtpub.com/product/cloud-native-with-kubernetes/9781838823078?utm_source=github&utm_medium=repository&utm_campaign=9781838823078) [[Amazon]](https://www.amazon.com/dp/1838823077)

## Get to Know the Author
**Nassim Kabbani**
is an experienced software engineer with deep expertise in Kubernetes and the Amazon Web Services cloud provider. He has an extensive background both in software development and operations teams, implementing all the spectrum of a DevOps lifecycle chain, from application code to pipelines and monitoring in various industries such as e-commerce, media, and financial services.
He implemented numerous cloud-native architectures and containerized applications on Docker and AWS and holds both Kubernetes CKA and CKAD certification

**Piotr Tylenda**
is an experienced DevOps and software engineer with a passion for Kubernetes and Azure technologies. In his projects, he has focused on the adoption of microservices architecture for monolithic applications, developing big data pipelines for e-commerce, and architecting solutions for scalable log and telemetry analytics for hardware. His most notable contribution to Kubernetes' open source ecosystem is the development of Ansible automation for provisioning and deploying hybrid Windows/Linux Kubernetes clusters. Currently, he works at Microsoft Development Center Copenhagen in Denmark in a team developing a Microsoft Dynamics 365 Business Central SaaS offering.

**Russ McKendrick**
is an experienced system administrator who has been working in IT and related industries for over 25 years. During his career, he has had varied responsibilities, from looking after an entire IT infrastructure to providing first-line, second-line, and senior support in both client-facing and internal teams for large organizations.
Russ supports open source systems and tools on public and private clouds at N4Stack, a Node4 company, where he is the practice manager (SRE and DevOps). In his spare time, he has written several books including Mastering Docker, Learn Ansible and Kubernetes for Serverless Applications, all published by Packt Publishing.

## Other books by the authors
* [Hands-On Kubernetes on Windows](https://www.packtpub.com/cloud-networking/hands-on-kubernetes-on-windows?utm_source=github&utm_medium=repository&utm_campaign=9781838821562)

* [Learn Ansible](https://www.packtpub.com/virtualization-and-cloud/learn-ansible?utm_source=github&utm_medium=repository&utm_campaign=9781788998758)
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781838827694">https://packt.link/free-ebook/9781838827694 </a> </p>
