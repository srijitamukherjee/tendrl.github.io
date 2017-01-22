---
layout: default
---

{% capture intro %}
# Join our Community

The Tendrl project is a community of developers who aim to solve the central management problems for software defined storage. Mrugesh Karnik (_brainfunked_ on IRC) is the architect. Nishanth Thomas and Rohan Kanade (irc: k4n0) lead the development. There are also contributors from the [Ceph](http://www.ceph.com) and
[Gluster](http://www.gluster.org) communities and the aim is to leverage existing successful open source projects that have solved key aspects of the problems we aim to address.
{% endcapture %}

{% capture the-rest %}

## Find Out More

To get involved, please join the discussion on either IRC (internet relay chat) or on the mailing list.

  * Find us on [irc.freenode.net #tendrl-devel](https://webchat.freenode.net/?channels=#tendrl-devel)
  * Subscribe to the [tendrl-devel mailing list](https://www.redhat.com/mailman/listinfo/tendrl-devel)
  * Follow our development on [our GitHub](https://github.com/Tendrl) and
    the issue tracker of each module.
  * Participate in development planning at the [upstream Jira](http://tendrl.atlassian.net)

{% endcapture %}

<div class="frontpage">
  <div class="mission mission-text intro">{{ intro | markdownify }}</div>
  <div>{{ the-rest | markdownify }}</div>
</div>

