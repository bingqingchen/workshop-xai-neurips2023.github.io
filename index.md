---
layout: article
title: "XAI in Action: Past, Present, and Future Applications Across Diverse Use Cases"
excerpt: NeurIPS 2023 Workshop
menu: true
show_info: true
titles:
  en      : &EN       Home
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
key: page-home
article_header:
  type: overlay
  theme: dark
  align: left
  actions:
    - text: 15 Dec 2023 | New Orleans, USA 
  background_image:
    src: /assets/images/l2r_banner3.png
#    gradient: 'linear-gradient(135deg, rgba(52, 140, 96, 0.4), rgba(136, 73, 107, 0.4))'
---

<style>
.schedule-table-heading {
    display: inline;
    font-weight: bold;
    font-size: 20px;
    color: #999999;
    padding:0 0 20px 0;
}

.schedule-table-timecol {
    padding:0 50px 0 50px;
    display:inline;
}

.schedule-table-eventcol {
    display:inline;
    display:inline-block;
    inline-size: 300px;
}

.schedule-table-contentcol {
    display:inline;
    display:inline-block;
    inline-size: 250px;
    font-size:14px;
    line-height: normal;
}

.schedule-table-row-even {
    display:block;
    width:800px;
    background-color: #EEEEEE;
    padding:10px;
}

.schedule-table-row-odd {
    display:block;
    width:800px;
    padding:10px;
}

.article__header--overlay .overlay {
    min-height: 36rem;
    padding-top: 5rem;
    padding-bottom: 5rem;
}

.article__header {
    margin: 0 0 0 0;
}

.article__header h1 {
    display: inline;
    font-size: 2.5em;
    letter-spacing: -0.04em;
    line-height: 0.9;
    text-shadow: -20px -8px 17px rgb(0 0 0 / 30%);
    word-wrap: break-word;
}

.overlay__excerpt {
    margin: 20px 0 0 0;
}

ul.menu li::after {
    content:"15 Dec 2023 | New Orleans, USA";
}

ul.menu a {
    display: none;
}

.pc-column {
    width:270px;
    display:inline-block;
    vertical-align: top;
}

.pc_list_item {
    display:inline-block;
    width:200px;
}

.organiser_profile {
    font-weight:normal;
    color: black;
}

.organiser_profile a:link a:visited a:hover a:active {
    font-weight:normal;
    color: #000000;
}

.organiser_profile p {
    font-weight:normal;
    color: #000000;
}

.logos-organizers {
    display: flex;
    align-items: center;
    flex-direction: row;
    flex-wrap: nowrap;
}

.img-fluid {
    max-width: 100%;
    height: auto;
}

img {
    vertical-align: middle;
    border-style: none;
}
</style>

<script>
  var x = setInterval(function() {
    var d = new Date();
    var n = d.toLocaleTimeString("en-US", {timeZone: "America/New_York", hour: '2-digit', minute:'2-digit', hour12: false})
    document.getElementById("edt").innerHTML = n
  }, 1000);
</script>

<script>
  var x = setInterval(function() {
    var d = new Date();
    var n = d.toLocaleTimeString("en-US", {timeZone: "Europe/Vienna", hour: '2-digit', minute:'2-digit', hour12: false})
    document.getElementById("cet").innerHTML = n
  }, 1000);
</script>

<script>
  {%- include scripts/lib/swiper.js -%}
  var SOURCES = window.TEXT_VARIABLES.sources;
  window.Lazyload.js(SOURCES.jquery, function() {
    $('.swiper-demo').swiper();
  });
</script>

<script>

  var countDownDate = new Date("Feb 15, 2022 23:59:59 UTC").getTime();  
  countDownDate = countDownDate + 1000 * 3600 * 12


  var x = setInterval(function() {


    var now = new Date().getTime();


    var distance = countDownDate - now;


    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);


    var countdown = days + "d " + hours + "h " + minutes + "m " + seconds + "s ";


    if (distance < 0) {
      clearInterval(x);
      countdown = "(expired)";  
    }

    document.getElementById("countdown").innerHTML = countdown

  }, 1000);
</script>

<br>

## About

As AI models continue to advance in complexity and sophistication, understanding how they work and make decisions is becoming increasingly challenging. This challenge has prompted a surge of research into developing methods and tools that can enhance the transparency and explainability of these models. Nowadays, there are many such methods available, to the point that their specific applications have become somewhat unclear.

This workshop will specifically explore the diverse applications of explainable artificial intelligence (XAI) methods in various areas. The areas will include, but not limited to XAI in Healthcare, Natural Science, Auditing, Fairness, Natural Language Processing and Law. By examining the use of XAI in these fields, the workshop will provide attendees with insights into the latest trends and challenges within the different domains. 

The workshop discussions aim to delve into the latest advancements in applied XAI and devise ways to further progress the field. The objective is to foster an open and productive dialogue that enhances our understanding of the potential opportunities and constraints of XAI and its impact across different domains. The purpose of this discourse is to identify strategies that can extend the frontiers of applied XAI and make notable progress in this rapidly evolving area. Specifically, the workshop aims to:


### Topics covered

<div>
<div style="width:49%; display:inline-block; font-size:14px; vertical-align:top">
<ul>
<li>Examine various applications of XAI from the past and present </li>
<li>Discuss potential applications of XAI in the future</li>
<li>Identify the obstacles that hinder progress in each use case and how can we overcome them</li>
<li>Explore the necessary methodological requirements for applying XAI</li>
</ul>
</div>
<div style="width:49%; display:inline-block; font-size:14px; vertical-align:top">
<ul>
<li>Identify new domains where XAI can be useful in the future</li>
<li>Understand the inherent limitations of XAI</li>
<li>Explore whether insights gained from one use case can be transferred to other use cases</li>
</ul>
</div>
</div>

The workshop will provide a valuable learning opportunity for researchers, practitioners, and students seeking to apply XAI in their work, as it will feature presentations by experts in the field, as well as interactive discussions and insights into the latest trends and future directions in applied XAI. By bringing together a diverse group of participants with a shared interest in XAI, the workshop aims to foster collaboration, innovation, and knowledge sharing in this rapidly growing field.

## Dates

Note: all deadlines are in <b>Anywhere on Earth</b>.

### Paper Submission

<div>
<b>Submissions open:</b> 23 March 2022<br>
<b>Submissions due:</b> <p style="display:inline; text-decoration:line-through;">20 May 2022</p><p style="display:inline; color:red;">&nbsp;27 May 2022</p><br>
<b>Notification:</b> 6 June 2022<br>
<b>Camera Ready</b>: 17 June 2022<br>
<b>Oral/Poster video upload</b>: 1 July 2022
</div>

### Workshop Event

<b>Date:</b> 22 July 2022

## Schedule

Friday, 22 July, 2022. All times are in Eastern Daylight Time (EDT). Current time is <span id="edt"></span>.

<div style="display:block; width:900px; padding:20px; border:solid 4px #CCCCCC;">
<div class="schedule-table-heading" style="margin-left:57px; display:inline-block; inline-size:100px;">Time</div>
<div class="schedule-table-heading" style="display:inline-block; inline-size:295px;">Event</div>
<div class="schedule-table-heading">Content</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">08:50</div>
<div class="schedule-table-eventcol">Welcome</div>
<div class="schedule-table-contentcol">Opening Remarks</div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">09:00</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/david_held.png" alt="David Held">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">David Held</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987747/selfsupervised-3d-perception-for-autonomous-driving?ref=folder-105306" target="_blank"><i>Self-supervised learning for autonomous driving</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">09:30</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/melanie_zeilinger.png" alt="Melanie Zeilinger">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Melanie Zeilinger</p>
<p style="margin:0 0 0 10px; font-size:10px;">ETH Zürich</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987741/learning-for-high-performance-yet-safe-control?ref=folder-105306"><i>Learning for High Performance yet Safe Control</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">10:00</div>
<div class="schedule-table-eventcol">Social + Poster Session</div>
<!--div class="schedule-table-contentcol">Paper IDs: 1, 2, 3, 4, 5, 6, 9, 10, 13, 17, 18, 21, 22</div-->
<div class="schedule-table-contentcol"><b>Gathertown</b> and in-person displays</div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">11:00</div>
<div class="schedule-table-eventcol">Spotlight Talks</div>
<!--div class="schedule-table-contentcol">Content</div-->
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Zijian Guo</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987752/constrained-modelbased-reinforcement-learning-via-robust-planning?ref=folder-105306"><i>#16: Constrained Model-based Reinforcement Learning via Robust Planning</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Linrui Zhang</p>
<p style="margin:0 0 0 10px; font-size:10px;">Tsinghua University</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987764/saferlkit-evaluating-efficient-reinforcement-learning-methods-for-safe-autonomous-driving?ref=folder-105306"><i>#12: SafeRL-Kit: Evaluating Efficient Reinforcement Learning Methods for Safe Autonomous Driving</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">11:30</div>
<div class="schedule-table-eventcol">Autonomous Racing Virtual Challenge: Contributed Talks</div>
<!--div class="schedule-table-contentcol">Content</div-->
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Shivansh Beohar</p>
<p style="margin:0 0 0 10px; font-size:10px;">IIIT Allahabad</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987763/solving-learntorace-autonomous-racing-challenge-by-planning-in-latent-space?ref=folder-105306"><i>#11: Solving Learn-to-Race Autonomous Racing Challenge by Planning in Latent Space</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">James Bockman</p>
<p style="margin:0 0 0 10px; font-size:10px;">U Adelaide</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987768/the-edge-of-disaster-a-battle-between-autonomous-racing-and-safety?ref=folder-105306"><i>#14: The Edge of Disaster: A Battle Between Autonomous Racing and Safety</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">12:00</div>
<div class="schedule-table-eventcol">Lunch Break</div>
<!--div class="schedule-table-contentcol">Content</div-->
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">13:30</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/peter_stone.png" alt="Peter Stone">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Peter Stone</p>
<p style="margin:0 0 0 10px; font-size:10px;">UT Austin; Sony AI</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987742/reward-misdesign-for-autonomous-driving-and-accumulating-safety-rules-from-catastrophic-action-effects?ref=folder-105306"><i>Reward (Mis)design for Autonomous Driving and Accumulating Safety Rules from Catastrophic Action Effects</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol">14:00</div>
<div class="schedule-table-eventcol">Spotlight Talks</div>
<!--div class="schedule-table-contentcol">Content</div-->
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Weiran Yao</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987757/distributionaware-goal-prediction-and-conformant-modelbased-planning-for-safe-autonomous-driving?ref=folder-105306"><i>#23: Distribution-aware Goal Prediction and Conformant Model-based Planning for Safe Autonomous Driving</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">&nbsp;</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
&nbsp;
</div>
<div style="display:inline-block; width:150px; line-height:1.4; margin:0 0 0 40px">
<p style="margin:0 0 0 10px;">Zuxin Liu</p>
<p style="margin:0 0 0 10px; font-size:10px;">CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol" style="margin:0 0 0 35px;"><a target="_blank" href="https://slideslive.com/38987751/on-the-robustness-of-safe-reinforcement-learning-under-observational-perturbations?ref=folder-105306"><i>#15: On the Robustness of Safe Reinforcement Learning under Observational Perturbations</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">14:30</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/todd_hester.png" alt="Todd Hester">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Todd Hester</p>
<p style="margin:0 0 0 10px; font-size:10px;">Amazon Scout</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987743/multimodal-sensor-fusion-for-the-amazon-scout-robot?ref=folder-105306"><i>Multi-modal sensor fusion for the Amazon Scout robot</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">15:00</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/chelsea_finn.png" alt="Chelsea Finn">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Chelsea Finn</p>
<p style="margin:0 0 0 10px; font-size:10px;">Stanford + Google Brain</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987744/robots-that-learn-to-be-safe?ref=folder-105306"><i>Robots that Learn to Be Safe</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">15:30</div>
<div class="schedule-table-eventcol">Social + Poster Session</div>
<!--div class="schedule-table-contentcol">Paper IDs: 1, 2, 3, 4, 5, 6, 9, 10, 13, 17, 18, 21, 22</div-->
<div class="schedule-table-contentcol"><b>Gathertown</b> and in-person displays</div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">16:30</div>
<div class="schedule-table-eventcol">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/andrea_bajcsy.png" alt="Andrea Bajcsy">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Andrea Bajcsy</p>
<p style="margin:0 0 0 10px; font-size:10px;">UC Berkeley / CMU</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987745/practical-safety-assurances-for-dynamic-humanrobot-interactions?ref=folder-105306"><i>Practical Safety Assurances for Dynamic Human-Robot Interactions</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol" style="vertical-align: 10px;">17:00</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/jeff_schneider.png" alt="Jeff Schneider">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Jeff Schneider</p>
<p style="margin:0 0 0 10px; font-size:10px;">Carnegie Mellon University</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987746/safety-and-reinforcement-learning-for-selfdriving-cars?ref=folder-105306"><i>Reinforcement Learning for self-driving cars</i></a></div>
</div>

<div class="schedule-table-row-even">
<div class="schedule-table-timecol" style="vertical-align: 10px;">17:30</div>
<div class="schedule-table-eventcol"><div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:60px;">
<img style="width:50px; height:50px; position: relative; bottom: 10px;" src="{{ site.baseurl }}/assets/images/speakers/sergey_levine.png" alt="Sergey Levine">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Sergey Levine</p>
<p style="margin:0 0 0 10px; font-size:10px;">UC Berkeley</p>
</div>
</div>
</div>
<div class="schedule-table-contentcol"><a target="_blank" href="https://slideslive.com/38987748/learning-plannable-representations-and-planning-with-learnable-skills?ref=folder-105306"><i>Learning Plannable Representations and Planning with Learnable Skills</i></a></div>
</div>

<div class="schedule-table-row-odd">
<div class="schedule-table-timecol">18:00</div>
<div class="schedule-table-eventcol">Conclusion</div>
<div class="schedule-table-contentcol">Closing Remarks</div>
</div>

</div>

<!--Poster Presentation Gathertown link: https://app.gather.town/app/wLuHBtWDuNBoHgun/SL4AD%2022  -->

## Speakers

<div style="display:block; padding:10px 0 0 0; width:900px;">

<a href="https://davheld.github.io/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/david_held.png" alt="David Held">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">David Held</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>Carnegie Mellon University</p>
</div>
</div>
</a>

<a href="https://idsc.ethz.ch/research-zeilinger/people/person-detail.MTQyNzM3.TGlzdC8xOTI5LDg4NTM5MTE3.html" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/melanie_zeilinger.png" alt="Melanie Zeilinger">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Melanie Zeilinger</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor<br>ETH Zürich</p>
</div>
</div>
</a>

<a href="https://www.cs.utexas.edu/~pstone/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/peter_stone.png" alt="Peter Stone">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Peter Stone</p>
<p style="margin:0 0 0 10px; font-size:10px;">Professor; Exec. Director, Sony AI America; Assoc. Chair, CS<br>UT Austin</p>
</div>
</div>
</a>

<a href="https://www.cs.utexas.edu/~todd/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/todd_hester.png" alt="Todd Hester">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Todd Hester</p>
<p style="margin:0 0 0 10px; font-size:10px;">Applied Scientist Lead<br>Amazon Scout</p>
</div>
</div>
</a>

<a href="https://ai.stanford.edu/~cbfinn/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/chelsea_finn.png" alt="Chelsea Finn">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Chelsea Finn</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor, Stanford; Google Brain</p>
</div>
</div>
</a>

<a href="https://people.eecs.berkeley.edu/~abajcsy/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/andrea_bajcsy.png" alt="Andrea Bajcsy">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Andrea Bajcsy</p>
<p style="margin:0 0 0 10px; font-size:10px;">PhD Candidate, UC Berkeley; incoming Assistant Professor, CMU</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/jeff-schneider-1593b322/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/jeff_schneider.png" alt="Jeff Schneider">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Jeff Schneider</p>
<p style="margin:0 0 0 10px; font-size:10px;">Professor<br>Carnegie Mellon University</p>
</div>
</div>
</a>

<a href="https://people.eecs.berkeley.edu/~svlevine/" target="_blank" class="speaker_profile">
<div style="display:inline-block; width:270px; margin:20px 0 0 0;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/speakers/sergey_levine.png" alt="Sergey Levine">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Sergey Levine</p>
<p style="margin:0 0 0 10px; font-size:10px;">Associate Professor<br>UC Berkeley</p>
</div>
</div>
</a>

</div>

## Organisers

<div style="display:inline; width:900px; vertical-align: top;">

<a href="https://www.linkedin.com/in/jonmfrancis/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/jonathan_francis.png" alt="Jonathan Francis">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Jonathan Francis</p>
<!--p style="margin:0 0 0 10px;">CMU + Bosch</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Research Scientist at Bosch Research, focusing domain knowledge-enhanced representation learning, applied to robotics and autonomous driving</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/hitesharora11" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/hitesh_arora.png" alt="Hitesh Arora">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Hitesh Arora</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Researcher at Amazon, focusing on multimodal perception and reinforcement learning, applied to autonomous driving</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/bingqing-chen-631b754a/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/bingqing_chen.png" alt="Bingqing Chen">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Bingqing Chen</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Machine Learning Research Scientist at Bosch Research, focusing on constraint-based optimisation, physical mechanisms, and safe learning, applied to autonomous driving</p>
</div>
</div>
</a>

<a href="https://xinshuoweng.com/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/xinshuo_weng.png" alt="Xinshuo Weng">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Xinshuo Weng</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Research Scientist at NVIDIA Research; focusing on 3D computer vision and generative models for autonomous systems</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/sidgan/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/siddha_ganju.png" alt="Siddha Ganju">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Siddha Ganju</p>
<!--p style="margin:0 0 0 10px;">NVIDIA</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Researcher and Data Scientist at NVIDIA, focusing on computer vision optimization for vehicle autonomy and medical instruments</p>
</div>
</div>
</a>

<a href="https://www.linkedin.com/in/bhat-manoj/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/manoj_bhat.png" alt="Manoj Bhat">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Manoj Bhat</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Machine Learning Researcher at Amazon, focusing on Neural Radiance fields, reinforcement learning, and representation learning applied to autonomous driving</p>
</div>
</div>
</a>

<a href="https://danielomeiza.github.io/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/daniel_omeiza.png" alt="Daniel Omeiza">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Daniel Omeiza</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">PhD student at Oxford, focusing on explainable AI and decision-making, in autonomous driving</p>
</div>
</div>
</a>

<a href="https://www.cs.cmu.edu/~./jeanoh/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/jean_oh.png" alt="Jean Oh">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Jean Oh</p>
<!--p style="margin:0 0 0 10px;">CMU</p-->
<p style="margin:0 0 0 10px; font-size:10px;">Research Professor in Robotics Institute at CMU and Director of Bot Intelligence Group; multimodal perception, navigation, and artificial intelligence</p>
</div>
</div>
</a>

<a href="https://www.cs.cmu.edu/~ehn/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/eric_nyberg.png" alt="Eric Nyberg">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Eric Nyberg</p>
<p style="margin:0 0 0 10px; font-size:10px;">Professor of Computer Science at CMU and Program Director, Masters of Computational Data Science; hybrid reasoning systems and artificial intelligence</p>
</div>
</div>
</a>

<a href="https://sylviaherbert.com" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/sylvia_herbert.png" alt="Sylvia Herbert">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Sylvia Herbert</p>
<p style="margin:0 0 0 10px; font-size:10px;">Assistant Professor at UCSD and Director of Safe Autonomous Systems Lab; uncertainty modeling in control, safety-aware learning, autonomy</p>
</div>
</div>
</a>

<a href="http://www.cs.columbia.edu/~lierranli/" target="_blank" class="organiser_profile">
<div style="display:inline-block; width:270px;">
<div style="display:inline-block; width:101px;">
<img style="width:100px; height:100px; position: relative; bottom: 40px;" src="{{ site.baseurl }}/assets/images/organizers/li_erran_li.png" alt="Li Erran Li">
</div>
<div style="display:inline-block; width:150px; line-height:1.4;">
<p style="margin:0 0 0 10px;">Li Erran Li</p>
<p style="margin:0 0 0 10px; font-size:10px;">Head of Science/HIL at Amazon AWS AI and Adjunct Professor at Columbia; Computer Vision, Machine Learning Systems, and Algorithms</p>
</div>
</div>
</a>

</div>

## Program Committee

<!-- column 1 -->
<div class="pc-column">
<ul>
<li>Arav Agarwal (<b>ER</b>, <b>TR</b>)</li>
<li>Eren Aksoy</li>
<li>Raghuram Mandyam Annasamy</li>
<li>Tiago Cortinhal</li>
<li>Xiaoxiao Du (<b>TR</b>)</li>
<li>Isht Dwivedi</li>
<li>Hesham Eraqi</li>
<li>Xiangyu Gao</li>
<li>Sahika Genc (<b>ER</b>)</li>
<li>S. Alireza Golestaneh (<b>TR</b>)</li>
</ul>
</div>

<!-- column 2 -->
<div class="pc-column" style="margin:0 30px 0 0;">
<ul>
<li>David Held (<b>SMR</b>)</li>
<li>Todd Hester (<b>SMR</b>)</li>
<li>Zehao Huang</li>
<li>Fabian Hüger</li>
<li>Arec Jamgochian (<b>TR</b>)</li>
<li>Rowan McAllister (<b>SMR</b>)</li>
<li>Kunal Menda</li>
<li>Aarati Noronha</li>
<li>Praveen Palanisamy</li>
<li>João Pinho (<b>ER</b>)</li>
</ul>
</div>

<!-- column 3 -->
<div class="pc-column">
<ul>
<li>Daniele Reda</li>
<li>Nazmus Sakib</li>
<li>Pranjay Shyam</li>
<li>Mark Schutera</li>
<li>Zhaoen Su</li>
<li>Ram Vasudevan</li>
<li>Yujie Wei</li>
<li>Weiran Yao</li>
</ul>
</div>

---

<b>ER</b> — <i>Recognises PC member who served ("+" additionally) as an Emergency Reviewer.</i><br>
<b>TR</b> — <i>Recognises PC member who, according to Chair ratings, ranked in the Top 15% of Reviewers.</i><br>
<b>SMR</b> — <i>Recognises PC member who agreed to provide their services as a Senior Meta-Reviewer.</i>

## Sponsors

<img src="{{ site.baseurl }}/assets/images/sponsors/sponsor_banner.png">

<!--
<div class="col-lg-12 col-xl-6">
            <div class="logos-organizers">
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/arrival_logo.png">
              </div>
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/cmu_logo.png">
              </div>
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/aicrowd_logo.png">
              </div>
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/aws_logo.png">
              </div>
              <div class="logo-organizer">
                <img class="img-fluid" src="{{ site.baseurl }}/assets/images/sponsors/bosch_logo.png">
              </div>
            </div>
          </div>
-->
<!--
<div style="width:900px; display:inline-block;">
<img style="height:100px; width:186px;" src="{{ site.baseurl }}/assets/images/sponsors/arrival_logo.png">
<img style="height:100px; width:157px;" src="{{ site.baseurl }}/assets/images/sponsors/cmu_logo.png">
<img style="height:100px; width:100px;" src="{{ site.baseurl }}/assets/images/sponsors/aicrowd_logo.png">
<img style="height:100px; width:98px;" src="{{ site.baseurl }}/assets/images/sponsors/aws_logo.png">
<img style="height:100px; width:272px;" src="{{ site.baseurl }}/assets/images/sponsors/bosch_logo.png">
<img style="height:100px; width:354px;" src="{{ site.baseurl }}/assets/images/sponsors/honda_logo.png">
</div>
-->
