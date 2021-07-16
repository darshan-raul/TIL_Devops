# TIL_Devops

## AWS

### Ec2
- Nitro vs Xen Hypervisor 
https://www.metricly.com/aws-nitro/

### Lambda

- Lambda Extensions
https://aws.amazon.com/blogs/compute/introducing-aws-lambda-extensions-in-preview/
-https://docs.aws.amazon.com/lambda/latest/dg/runtimes-extensions-api.html

### VPC
- Vpc reacahability analyzer
https://docs.aws.amazon.com/vpc/latest/reachability/getting-started.html

### Cert preparation

https://towardsaws.com/solutions-architect-associate-exam-cheat-sheet-saa-c02-1d22b798d9ac

### Aurora

https://www.youtube.com/watch?v=I4uOEoUYPC8
https://www.youtube.com/watch?v=3DClteE-AUc&list=PLiH9_MU-6RjI9gdFqmvUfKRfw_zRxIb6o&index=23&t=634s

### Aurora serverless:
https://www.youtube.com/watch?v=ciRbXZqBl7M
### IAC:
Pulumi
https://www.youtube.com/watch?v=vIjeiDcsR3Q



# Monitoring

## ElasticSearch

- Elasticsearch Curator helps you curate, or manage your indices.
https://github.com/elastic/curator
So if you need to rollover the old indexes, a simple command like `curator --host localhost delete indices --older-than 30 --time-unit days --timestring '%Y.%m.%d'`
can help


# Docker

## Basics

- Overlay file system 
https://napicella.medium.com/how-are-docker-images-built-a-look-into-the-linux-overlay-file-systems-and-the-oci-specification-51d65c73c416

## K8s

https://learnk8s.io/kubernetes-autoscaling-strategies
https://blog.datacamp.engineering/understanding-the-kubernetes-docker-deprecation-notice-by-dummies-for-dummies-c9f2685486e0

## Helm

https://www.youtube.com/watch?v=5_J7RWLLVeQ

# Linux

https://github.com/chassing/linux-sysadmin-interview-questions/blob/master/README.md#simple
https://www.youtube.com/playlist?list=PL426FzyFBwBphstVtquPX2THCD8ESzyMD

## Boot process

https://www.youtube.com/watch?v=DpaANVe-uI4

## Hardening
https://www.howtogeek.com/118222/htg-explains-what-apparmor-is-and-how-it-secures-your-ubuntu-system/
https://github.com/decalage2/awesome-security-hardening https://www.tecmint.com/linux-server-hardening-security-tips/ https://www.ubuntupit.com/best-linux-hardening-security-tips-a-comprehensive-checklist/ https://github.com/trimstray/linux-hardening-checklist/blob/master/README.md https://github.com/imthenachoman/How-To-Secure-A-Linux-Server https://madaidans-insecurities.github.io/guides/linux-hardening.html
 
## Kernel and boot process (TLDR)
https://charmanderander.gitbooks.io/deep-dive/content/

https://www.howtoforge.com/how-to-increase-the-disk-space-of-an-aws-ec2-ubuntu-instance/
# https://www.gnu.org/software/parallel/

# Networking

# TCP/Ip Model

- It is also sometimes referred to as the Department of Defense (DoD) Model,

# HTTPS:
https://www.youtube.com/watch?v=10aVMoalON8

# What are sockets:
A socket is just a logical endpoint for communication.
They exist on the transport layer. 
You can send and receive things on a socket, you can bind and listen to a socket.
A socket is specific to a protocol, machine, and port, and is addressed as such in the header of a packet.
https://unix.stackexchange.com/a/193824
https://www.youtube.com/watch?v=uXve8WYiGts

# Devops Learning

https://medium.com/@devfire/how-to-become-a-devops-engineer-in-six-months-or-less-366097df7737


# Devops principle blogs

- https://nordicapis.com/the-bezos-api-mandate-amazons-manifesto-for-externalization/
- https://lambda.grofers.com/devops-for-self-determination-28f37cc7dc82
