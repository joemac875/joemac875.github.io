---
title:  "Woo Game Jame"
date:   2018-04-15 18:00:00 -0400
categories: leadership
---

<script type="text/javascript" src="../../dist/vis.js"></script>
  <link href="../../dist/vis-network.min.css" rel="stylesheet" type="text/css" />

  <style type="text/css">
    #mynetwork {
      width: 600px;
      height: 400px;
      border: 1px solid lightgray;
    }
  </style>

<div id="mynetwork"></div>

<script type="text/javascript">
  // create an array with nodes
  var nodes = new vis.DataSet([
    {id: 1, label: 'Node 1'},
    {id: 2, label: 'Node 2'},
    {id: 3, label: 'Node 3'},
    {id: 4, label: 'Node 4'},
    {id: 5, label: 'Node 5'}
  ]);

  // create an array with edges
  var edges = new vis.DataSet([
    {from: 1, to: 3},
    {from: 1, to: 2},
    {from: 2, to: 4},
    {from: 2, to: 5},
    {from: 3, to: 3}
  ]);

  // create a network
  var container = document.getElementById('mynetwork');
  var data = {
    nodes: nodes,
    edges: edges
  };
  var options = {};
  var network = new vis.Network(container, data, options);
</script>

My friend and fellow classmate, Avi Vajpeyi and I decided that we wanted to participate in the [Ludum Dare]() game jam – a global game creation competition that takes place over a single weekend. As we talked, however, we realized it would be much more exciting to get other students at Wooster involved. Thus, we decided to organize a game jam event at the College coinciding with Ludum Dare 41.

![Demoing the Finished Games]({{site.baseurl}}/assets/jam.jpg)

It was a success! We got alumni working in the industry to video call in and share tips for success, consumed a lot of snacks, and even managed to provide tshirts. By the end of the weekend, six teams had created playable games, which we demoed in the campus’s student center.

<iframe width="100%" height="315" src="https://www.youtube.com/embed/eKdHRfMhVDI" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

Avi and I, along with two other students, Thomas Matlak and Alex Iudice fielded our own game as well, which we called Time Turner. The game jam’s theme was ‘two incompatible games,’ so we jammed together turn-based strategy with racing games. The game takes the player through a series of levels in which they must avoid enemy chase cars in the whilst navigating to an objective. The caveat, however, is that the player can drive while the enemy cars are frozen in time, but they themselves, after a short pause, are frozen while the enemy cars drive.
