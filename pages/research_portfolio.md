---
layout: page
title: "Research Portfolio"
permalink: /portfolio/
---

<style>
	.portfolio-image {
	  width: 200px;
	  height: 150px;
	  object-fit: cover;
	  border-radius: 8px;
	  transition: box-shadow 0.3s;
	  cursor: pointer;
	  box-shadow: 0 2px 8px rgba(0,0,0,0.12);
	  position: relative;
	  z-index: 1;
	}

	/* Add an overlay image style for enlarged view */
	.portfolio-image.enlarge {
	  position: fixed;
	  top: 50%;
	  left: 50%;
	  width: 600px;
	  height: auto;
	  transform: translate(-50%, -50%);
	  z-index: 1000;
	  box-shadow: 0 12px 32px rgba(0,0,0,0.30);
	  background: white;
	  border-radius: 20px;
	}
	
	/* Special larger enlarged style */
	.portfolio-image-large.enlarge {
	  width: 900px;
	  max-height: 90vh;
	  border-radius: 32px;
	}
	
	/* Extra large */
	.portfolio-image-xlarge.enlarge {
	  width: 1200px;
	  max-width: 98vw;
	  max-height: 95vh;
	  border-radius: 48px;
	  z-index: 9999;
	}

</style>
<script>
document.addEventListener('DOMContentLoaded', function() {
  var imgs = document.querySelectorAll('.portfolio-image');
  imgs.forEach(function(img) {
    img.addEventListener('mouseenter', function() {
      this.classList.add('enlarge');
    });
    img.addEventListener('mouseleave', function() {
      this.classList.remove('enlarge');
    });
  });
});
</script>




<p class="research-portfolio-intro">
  Selected research projects reflecting my journey in self-regulated learning, human-centered design, educational technology, and learning analytics.
</p>


---

## Personalized AI Hints: Human-in-the-Loop (2025, L@S)


<div class="portfolio-images">
  <img src="/images/research/loop_interface.png" alt="A screenshot of interface on student end" class="portfolio-image">
  <img src="/images/research/loop_interface2.png" alt="A screenshot of interface on instructor end(2)" class="portfolio-image">
</div>

*(left) Student interface for requesting AI hints. (right) Instructor interface for giving feedback as a single-
page website*
*Both images created by Tung Phung, the first author (2025)*

The study develops and investigates an impact of a novel human-in-the-loop personalized AI help framework; Students can first request AI-generated hints directly in their coding environment (JupyterLab). If they find an AI hint unhelpful, they have the option to escalate the request for human instructor feedback, with additional context if needed. I supported study finding analysis to draw insights from the learner-AI-instructor feedback loop; Interestingly, we found that human-provided feedback was also wrong for a half of the time, in cases when students escalated their problems. This might imply that there are certain programming problems that are difficult for both humans and AI to provide helpful assistance to learners. 

📰 [arXiv Preprint](https://arxiv.org/pdf/2510.14457.pdf)

---

## Personalized AI Hints: Enhancing SRL (2025, AIED)


<img src="/images/research/plan_interaction.png" alt="Illustration describing a flow of learner-AI interaction" class="portfolio-image">

*Learners' interaction steps with our intervention*

<img src="/images/research/plan_illustration_hint_types.png" alt="Each hint button image with corresponding description" class="portfolio-image portfolio-image-xlarge">

*Examples of each hint type.*
*Both images created by Tung Phung, the first author (2025)*

The study investigates how integrating metacognitive principles into AI-generated assistance can enhance programming learning experiences. It finds that students highly value and most benefit from planning hints, which are consistently associated with improved performance. In this work, I designed personalized AI hints aligned with key phases of self-regulated learning (SRL): planning, debugging, and optimization. 

📰 [arXiv Print](https://arxiv.org/pdf/2509.03171)

---

## MetaLAD: Dashboard Supporting Metacognition (2023, LWMOOCs)


<img src="/images/research/dashboard_screenshot.png" alt="Screenshots of subtitle designs of each experiment condition" class="portfolio-image portfolio-image-large">

*A screenshot of MetaLAD, a dashboard designed to support working professionals taking online certificate courses*

Led a project to develop a dashboard, ground in self-regulated laerning theory, for students enrolled in the Supply Data Analytics course of MITx MicroMasters in Supply Chain Managment. The dashboard was featured in the official [MIT Open Learning blog](https://medium.com/open-learning/new-dashboard-supports-online-learners-self-regulated-learning-and-performance-86ca4c0d0d8e).

📰 [Published paper in LwMOOCs conference 2023](https://heeryung.github.io/assets/files/heeryung-lwmoocs23.pdf) *Nominated as a Best Paper*

---

## Pairing Hints with Reflection (2023, Internet and Higher Education)

<img src="/images/research/dls_process.png" alt="Four screenshots of the intervention showing how learners' interactions with the intervention were." class="portfolio-image portfolio-image-xlarge">

*Screenshots of the intervention. (a) Each task has a ‘Show Hint’ button below the task text. (b) When a learner clicks the ‘Show Hint’ button, a pop-up appears and shows a list of available hints. (c) The full text of the chosen hint is shown on a pop-up and also inscribed below the associated task so that a learner can see hints after closing the pop-up. (d) When a learner clicks a button to submit the current task, a reflection prompt pop-up appears. Upon completing the prompt, the learner’s submission is graded by an autograder.*

<img src="/images/research/dls_flowchart.png" alt="Four screenshots of the intervention showing how learners' interactions with the intervention were." class="portfolio-image">

*A flowchart illustrating the steps in the submission and revision process for assignments.*


This study, that I led, investigates whether providing reflection prompts alongside hints can meaningfully improve learning outcomes in an online programming course. I conducted a randomized field experiment in a four-week online data science master’s course. Findings showed that learners who received both hints and reflection prompts showed significantly higher performance on both immediate and delayed transfer tasks than those who received only hints.

📰 [Published Paper in Internet and Higher Education, 2023](https://heeryung.github.io/assets/files/heeryung-the-internet-and-higher-education-hint-jovanovic.pdf)

---

## Textual Aid Design Recommendations (2022, SIGCSE)

<img src="/images/research/subtitle_screenshot.png" alt="Screenshots of subtitle designs of each experiment condition" class="portfolio-image portfolio-image-xlarge">

*Examples of subtitle designs of five experiment conditions*

Conducted a randomized controlled trial to evaluate "subtitles", or textual aids in lecture video recordings of Jupyter Notebook, affect learners' performance in programming-based multimedia learning. This study provides empirical evidence that thoughtfully designed textual aids can enhance accessibility and learning outcomes in computer science education.

📰 [Published Paper at SIGCSE 2022](https://dl.acm.org/doi/abs/10.1145/3478431.3499290)

---
