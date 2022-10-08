---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<!-- <style> -->
<!-- iframe { -->
<!--   height: 100%; -->
<!--   width: 175px !important; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   width: 175px; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   border: 1px solid red; -->
<!-- } -->
<!-- .col-md-3 { -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   overflow:hidden; -->
<!--   display: table-cell; -->
<!--   text-align:center; -->
<!--   background: white; -->
<!--   width: 175px; -->
<!--   border: 0px solid transparent; -->
<!--   border-radius:20px; -->
<!-- } -->
<!-- </style> -->

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
  <!-- border: 1px solid black; -->
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

  <!-- border: 5px solid red; -->
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- float: none; -->

## Research

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Design of WebRTC based Real Time Streaming System</h4>
<a href="{{ site.url }}{{ site.baseurl }}/papers/BTP-1.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a>
<br>
With the start of pandemic, there was an increase in the demand of video conferencing systems. These systems were highly scalable but 
they were always criticised for their lack of data security. This project aimed at creating a video conferencing system 
with a distributed architecture, keeping data security at the helm. I developed a web application with a mesh architecture using WebRTC. 
I also added a discovery server, capability to view multiple screens and selective display. This design could support 5 users with 
video but wasn't scalable beyond that. 

I also developed an alternate architecture that uses supernodes to improve the scalability of the system.
Certain nodes are elected to become supernode which provide additional processing for the system.
</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4>Cluster Middleware: Fenrir</h4>
<a href="{{ site.url }}{{ site.baseurl }}/papers/Cluster-Middleware.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a>
<br>
An cluster middleware for resource management with a master-worker architecture. The master node accepts tasks along 
with their requirements such as cpu and memory. Then, It identifies the appropriate worker node from the available pool 
and allocates the task. Some features of this system are: 
* The master node has a backup node and works in an active-passive mode. 
* The worker nodes continuously send heartbeats to the master node for failure detection. Upon failure of a node, The 
master node reassigns any tasks on that node to a separate node.
* The system is priority aware and uses dynamic priority scheduling of tasks to prevent job starvation
</div>
<div class="col-md-3 col-sm-12" >
</div>
</div>
</div>
 

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Efficient task scheduling for autonomous driving DNN workloads</h4>
<a href="{{ site.url }}{{ site.baseurl }}/papers/HP3_Project.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a>
<br>
This work is an implementation of the paper <a href="https://ieeexplore.ieee.org/document/8430082">S3DNN</a>.  
DNN workloads for autonomous driving typically consists of relatively reduced load near the last layers. 
This work leverages this to improve the efficiency of resource usage.
</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent" >
</div>
</div>
</div>
