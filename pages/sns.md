---
layout: page
subheadline:  
title:  "Trust-sourcing"
teaser: 
breadcrumb: true
categories:
- project
permalink: "/project/trust/"
header: no
---

<h4> Summary </h4>
This work focuses on how human resources in social network, including weak tie and strong tie, are utilized. We suggest a model based on the idea that a person whom my reliable person relies on is also reliable. Based on trust as a feature, a new type of a social network is built.


<h4> Keywords </h4>
Trust, social network service

<h4> People </h4>
Guhyun Hahn, Hunjin Park, Jeongmoon Choi

<h4> Project Type </h4>
Class project

<hr>

<h4> Research Methods </h4>
Prototyping, social network analysis

<h4> Reserach Motivation </h4>
<ul>
    <li> To verify reliability of human resource in social network. <br>
        → How to fully utilize social networks when searching for a target (e.g. roommates, co-workers...)? <br>
        → A model based on the idea that "A person whom my reliable person relies on is also reliable." </li>
</ul>

<h4> Trust Model </h4>
<ol> 
    <li> User A will announce a recruitment notice. </li>
    <li> User B, a node indirectly connected to the user A, will apply for the position through sending a message. </li>
    <li> The system will build the path between the user and the target and deliver the message. </li>
    <li> Users/nodes between user A and user B will judge whether the message should be delivered to the next node or not, if user B is reliable for the position. </li>
    <li> If user A receives the message, user A will make a final decision on the recruitment. </li>
</ol>

<h4> Possible Cases of Trust Model </h4>
<div id = "sequenceContainer2">
<div style = "padding: 5px;">
    <div id = "sequenceContainer2-1">
    <div style = "padding: 10px;">
        <strong> 1. Request Sent </strong>
            <div class = "row">
                <div class = "medium-8 columns">
                    <img src = "http://heeryung.github.io/images/sns_1.png">
                    <p> A message is sent from an applicant node. </p>
                </div>
            </div>
    </div>

    <div id = "sequenceContainer2-1">
    <div style = "padding: 10px;">
        <strong> 2-1. Request Failed to be Delivered </strong>
            <div class = "row">
                <div class = "medium-8 columns">
                    <img src = "http://heeryung.github.io/images/sns_2-1.png">
                    <p> A message is rejected during hops by a middle node. </p>
                </div>
            </div>
    </div>


    <div id = "sequenceContainer2-1">
    <div style = "padding: 10px;">
        <strong> 2-2. Request Delivered & Denied </strong>
            <div class = "row">
                <div class = "medium-8 columns">
                    <img src = "http://heeryung.github.io/images/sns_2-2.png">
                    <p> A message is successfuly reached but rejected by an employer. </p>
                </div>
            </div> 
    </div>

    <div id = "sequenceContainer2-1">
    <div style = "padding: 10px;">
        <strong> 2-3. Request Accepted </strong>
            <div class = "row">
                <div class = "medium-8 columns">
                    <img src = "http://heeryung.github.io/images/sns_2-3.png">
                    <p> A message is successfully reached and accpeted. </p>
                </div> 
            </div>
    </div>
