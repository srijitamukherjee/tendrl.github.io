---
layout: default
---

{% capture intro %}
# About Tendrl

{:.lead}
Tendrl is an open source Software Defined Storage management system that is designed for SDS technologies of today and tomorrow. 

It provides for installation, storage provisioning, lifecycle management, monitoring, alerting, trending, and analytics for [Ceph](http://www.ceph.com) and 
[Gluster](http://www.gluster.org) storage, 
while providing a framework to encompass other SDS technologies in the future. 
It will feature a modern dashboard based on the look and feel of PatternFly.
{% endcapture %}
{% capture features %}

# Planned Features

Tendrl is work in progress, and we invite you to participate in its development
&mdash; [Read more on how you can contribute]("/about/").

Tendrl will feature a graphical dashboard with trend data for utilization, network usage, and other parameters, including alerts based on important events and thresholds.

{% endcapture %}
{% capture ceph %}

## Features specific to Ceph

  * Installation of new clusters
  * Import of existing clusters
  * Creation of storage pools
  * Creation of RADOS block storage
  * OpenStack integration via TripleO

{% endcapture %}

{% capture gluster %}

## Features specific to Gluster 

  * Installation of new clusters
  * Import of existing clusters
  * Creation of bricks 
  * Creation of 2 and 3 way distributed replicated volumes
  * Creation of erasure coded volumes
  * Setup of access protocols (CIFS/NFS v3,v4) with HA

{% endcapture %}

<div class="frontpage">
  <div class="mission mission-text intro">{{ intro | markdownify }}</div>
  <div class="grid">
    <div class="col-12">{{ features | markdownify }}</div>
    <div class="col-6_md-12">{{ ceph | markdownify }}</div>
    <div class="col-6_md-12">{{ gluster | markdownify }}</div>
  </div>
</div>

