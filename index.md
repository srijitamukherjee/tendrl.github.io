---
layout: default
---

{% capture intro %}
# Tendrl is a Software Defined Storage Controller

It is Open Source and designed to manage today’s and tomorrow’s SDS technologies. 
{:.lead}

It provides for installation, storage provisioning, lifecycle management, monitoring, alerting, trending, and analytics for Ceph and Gluster storage, while providing a framework to encompass other SDS technologies in the future.
{% endcapture %}


{% capture getstarted %}
# Get Started

You can download Tendrl from our [GitHub repository](http://github.com/Tendrl). Binary builds are also available at FIXME. See our Quick Start Guide for instructions on getting started.

[Get Started](/documentation/quickstart)
{% endcapture %}


{% capture community %}
### Community

Tendrl is a community of developers who aim to solve the central management problems for software defined storage. It is lead on the architecture front by Mrugesh Karnik. There are key contributors from the Ceph and Gluster communities and the aim is to leverage existing successful projects that have solved key aspects of the problems we aim to address.
{% endcapture %}


<div class="frontpage">
  <div class="mission mission-text intro">{{ intro | markdownify }}</div>
  <div class="getstarted">{{ getstarted | markdownify }}</div>
  <div class="community">{{ community | markdownify }}</div>
</div>

