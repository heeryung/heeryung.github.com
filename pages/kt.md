---
layout: page
subheadline:  
title:  "KT Project"
teaser: 
breadcrumb: true
categories:
- project
permalink: "/project/kt/"
header: no
---

<iframe width="420" height="315" src="https://www.youtube.com/embed/kQlr-k_XtuQ" frameborder="0" style = "center" allowfullscreen></iframe>

<h4> Summary </h4>
In this research, we propose a kinetic typography (KT) layout engine, which generates sentence-level KT text to convey emotions in text-based communication. KIWEE(KT Instant messenger With Emotional Expression) allows users to automatically create KT effect, encouraging deliver emotions through text. KT(KT) enables users to better convey emotions in text-based communication. In this project, we propose a sentence-level KT system that generates and assigns effects to the text input. We believe that our system improves the utilization of KT for broader applications. The system consists of 5 steps, and we focused on creating an algorithm for automated processing and layout of text, as in a sentence.


<h4> Keywords </h4>
KT, emotion, messenger

<h4> Research methods </h4>
Text-processing, semi-structured interview, qualitative research, prototyping

<h4> Publications </h4>
<ul>
    <li><a href="http://www.dbpia.co.kr/Article/NODE06228881">Evaluating System-Generated KT Effects for Sentence-Level Text Layout</a><br>
Joonhwan Lee, Donghwan Kim, Inho Won, Jieun Wee, Yaena Jang, Sooyeon Jang, <strong>Heeryung Choi</strong><br><em>The Korean Institute of Information Scientists and Engineers 2014</em></li>
    <li><a href="http://www.dbpia.co.kr/Article/NODE06139482">Sentence-level KT Generating System</a><br>Joonhwan Lee, Donghwan Kim, Inho Won, Jieun Wee, Yaena Jang, Sooyeon Jang, <strong>Heeryung Choi</strong><br><em>HCI Korea 2015</em></li>
    <li><a href="http://heeryung.github.com/assets/files/multimedia_kt.pdf">The Architecture of Automatic KT Effects Generating System</a><br>Joonhwan Lee, Donghwan Kim, Inho Won, Jieun Wee, Yaena Jang, Sooyeon Jang, <strong>Heeryung Choi</strong><br><em>Korea Multimedia Society 2014</em></li>
</ul>


<h4> People </h4>
Joonhwan Lee, Donghwan Kim, Inho Wohn, Jieun Wee, Sooyeun Jang, Yaena Jang (Seoul National University) 
Younghoon Kim (University of Washington)

<h4> Acknowledgement </h4>
This work was supported by the IT R&D program of MKE/KEIT, (10041794, Development of the KT Technology for Emotional Representations in Social Media Environment).


<hr>


<h4> Research Motivation </h4>
<ul>
    <li> To develop a <strong>sentence-level</strong> KT generator. </li>
    <li> To build an <strong>automatic</strong> KT generator in order to faciliate more end users applying KT. </li>
    <li> To build a <strong>real-time</strong> KT generator in order to deliver emotion in CMC. </li>
</ul>


<h4> KT Layout Engine - Study 1 </h4>
<div id = "large_image_container">
    <div style = "padding: 5px;">
    <div id = "images_container">
    <div style ="padding: 10px; text-align: center">
        Figure 1. Workflow of KT Layout Engine <br>
        <img src = "http://heeryung.github.com/images/kt_workflow.png">
    </div>
    <div class = "row">
        <div class="medium-6 columns">
            Figure 2. The prototype of KT Layout Engine <br>
            <img src = "http://heeryung.github.com/images/kt_prototype.png">
        </div>
        <div class="medium-6 columns">
            Figure 3. An automated KT generator for real-time messenger <br>
            <img src = "http://heeryung.github.com/images/kt_messenger.png">
        </div>
    </div>
</div>

<ul>
    <li> Emotions were coded on the moods (positive/negative) - energy (arousal) dimension. </li>
    <li> <a href="http://dl.acm.org/citation.cfm?id=571997">Preliminary research</a> findings indicate how mood and energy level can be represented through KT moods. </li>
    <li> Figure 1 reveals the architecture of the proposed system, a KT layout engine, which generates sentence-level KT text to convey emotions in text-based communication.
    <li> Using the KT effect library we had built, the prototype for the KT system was established using JavaScript toolkits (figure 2). </li>    
    <li> An experiment was carried out to see how well KT effects created by the designed algorithm represent feelings. </li> 
    <li> The result shows that the proposed KT system creates, assigns, and displays the effects in a way that conveys emotion through a sentence- level text: both of the two dimensions of emotion were effectively delivered, i.e. mood (positive-negative) and energy level (high-low). </li>
    <li> Verifying the validity of the proposed system, an automated KT generator for a real-time messenger developed.
</ul>

        

    



