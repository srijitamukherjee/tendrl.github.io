---
layout: default
---

{% capture intro %}
# Software Defined Storage Controller

Tendrl is Open Source and designed to manage today’s and tomorrow’s SDS technologies. 

It provides for installation, storage provisioning, lifecycle management, monitoring, alerting, trending, and analytics for Ceph and Gluster storage, while providing a framework to encompass other SDS technologies in the future.
{% endcapture %}


{% capture getstarted %}
# Get Started

Right now you can download Tendrl from our [GitHub repository](http://github.com/Tendrl). We are working on setting up binary builds as well, to make it easier 
to test-drive Tendrl

For now, please follow either one of the following quick start guides to install
the common Tendrl components and the matching bridge for your storage solution. 
If you have both Gluster and Ceph storage in use, you can naturally adapt both
guides to install both bridges and use one instance of Tendrl to view it all
in one place.

### [Instructions for Ceph Storage](https://github.com/Tendrl/ceph_bridge/blob/master/doc/source/installation.rst) | [Instructions for Gluster Storage](https://github.com/Tendrl/gluster_bridge/blob/master/doc/source/installation.rst)

{% endcapture %}


{% capture community %}
# Join our Community

The Tendrl project is a community of developers who aim to solve the central management problems for software defined storage. Mrugesh Karnik (_brainfunked_ on the [Tendrl IRC channel](irc://irc.freenode.net/tendrl) is the architect. Nishanth Thomas and Rohan Kanade (irc: k4n0) lead the development. There are also contributors from the [Ceph](http://www.ceph.com) and
[Gluster](http://www.gluster.org) communities and the aim is to leverage existing successful open source projects that have solved key aspects of the problems we aim to address.
{% endcapture %}


<div class="frontpage">
  <div class="mission mission-text intro">{{ intro | markdownify }}</div>
  <div class="getstarted">{{ getstarted | markdownify }}</div>
  <div class="community">{{ community | markdownify }}</div>
</div>

