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

{% capture ceph %}

## Ceph 

  * Install new clusters
  * Import existing clusters
  * Create storage pools
  * Create RADOS block storage
  * Integrated dashboard with trends for utilization, network, and more
  * Alerting based on important events and thresholds
  * OpenStack integration via TripleO

{% endcapture %}

{% capture gluster %}

## Gluster 

  * Install clusters
  * Import existing clusters
  * Create bricks 
  * Create 2 and 3 way distributed replicated volumes
  * Create erasure coded volumes
  * Setup access protocols (CIFS/NFS v3,v4) with HA

{% endcapture %}

<div class="frontpage">
  <div class="mission mission-text intro">{{ intro | markdownify }}</div>
  <div class="grid">
    <div class="col-6_md-12">{{ ceph | markdownify }}</div>
    <div class="col-6_md-12">{{ gluster | markdownify }}</div>
  </div>
</div>

