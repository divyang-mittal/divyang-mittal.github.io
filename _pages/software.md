---
title: "Software"
layout: gridlay
sitemap: false
permalink: /software/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}
</style>

## Software

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>Appdynamics Software Engineer (July 2021-July 2023)</b></h4>
- I am working in the data platform team, developing the new product of AppDynamics, AppdCloud. 
- My usual activities involve designing, developing and optimising microservices that perform transforming operations on milions of data packets every minute.
- Additional duties include investigating and solving bugs, taking up oncall and deploying to production.
- My biggest contributions here includes creating a library that is used to report slo metrics by all kafka based services in Appdynamics.
- Tech Stack: JAVA, Apache Kafka, Kubernetes, Micronaut, RocksDB, ReactiveX, Prometheus, etc
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>Appdynamics Software Engineering Intern (Summer, 2021)</b></h4>
- Created an indexing mechanism over data present in AWS s3 buckets to speed up query.
- Worked with hadoop distributed file system(HDFS) and leveraged map-reduce to provide a faster
solution. The tech stack also included Spark and Zeppelin. 
- Took care of small file problem in the proposed solution by generating equivalent size files.
- The final solution was able to reduce the query time by 40 percent in our tests
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>Distributed Key Value Store</b></h4>
<br>
- Implemented paxos library using Golang to create a distributed log to maintain sequential consistency of operations.
- Utilized distributed log to serve client requests, ensuring at most once semantics.
- Implemented model checking for verification of the logic as a state machine.

</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>Lexical Complexity Prediction</b></h4>
<br>
- Developed a system to predict lexical complexity of words in English Sentences on a 5 - point scale.
- Designed a Hybrid Machine Learning Model, achieving Pearson’s r of 0.74 on test data.
- Experimented with models GPT2, RoBERTa achieving best Pearson’s r of 0.8 on test data.
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>File System for Linux Kernel</b></h4>
<br>
- Devised a file system to perform CRUD operations on files and directories. Programmed in C for linux kernel.
- Tested the file system by emulating a memory system of 4KB blocks.
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>Studdy Buddy</b></h4>
<a href="{{ site.url }}{{ site.baseurl }}/papers/ERDiagram.pdf" target="_blank"><button class="btn btn-danger btn-sm">ER Diagram</button></a>
<br>
- A database app that can be used by students to find their studdy partners or tutors.
- Different user modes for students and teachers. Teachers able to add courses. 
- Used features of PostgreSQL; triggers and text search to implement gpa calculation and text query.

</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>Meet-Hobby</b></h4>
<a href="https://github.com/divyang-mittal/Meet-hobby" target="_blank"><button class="btn btn-danger btn-sm">Web App Code</button></a> <a href="https://github.com/divyang-mittal/android-meet-hobby" target="_blank"><button class="btn btn-danger btn-sm">Mobile App Code</button></a>
<br>
- A social networking app that can be used by people of similar interest to form groups.
- Use cases include creating groups, group creators having admin access such as adding/removing people from group and creating new admins. 
- Group members can create posts within the group and all users have ability to like and comment on these posts. 
- We created elaborate designs of the database to optimise the fetch operations. 
- The app was built using Django and MySQL.

</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>Computer Networks Projects</b></h4>
<br>
- Created a peer to peer network where peers communicate using rpc calls. Used a discovery server to identify various peers in the network.
- Developed a proxy server which reads all the requests and redirects them to appropriate destination.
- Developed an API over udp sockets to provide reliable communication.

</div>
</div>
</div>

 
<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4><b>HereIAm</b></h4>
- A web application that can be used to organise our life.
- Use cases include scheduling meetings, providing reminders, creating resume, a movie recommender, etc.
- Used standard software engineering practices like creating SRS document and DFD.
- Tech Stack: Javascript, Flask and MySql.
</div>
</div>
</div>
