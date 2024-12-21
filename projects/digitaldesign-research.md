---
layout: project
type: project
image: img/webgazer.png
title: "Exploring the Impact of Digital Design on Augmented Cognition"
date: 2024-12-13
published: true
labels:
  - Digital Design
  - Augmented Cognition
  - Research
summary: "A project to investigate how variations in instructional website design influence retention and cognitive processing using Webgazer.js eye tracking software"
---
<br />
## Overview
My project titled "Exploring the Impact of Digital Design on Augmented Cognition" was for a research study under the mentorship of Dr. Michael-Brian Ogawa and Branden Ogata. This project was presented at the Fall 2024 Undergraduate Showcase at UH Manoa.

As students increasingly engage with digital interfaces, understanding how technology influences learning has become essential. This study investigates how variations in instructional website design affect learning outcomes, focusing on identifying specific design elements that enhance engagement, knowledge retention, and cognitive processing in digital environments. For this project

## Methodology
Two instructional websites on Python programming fundamentals were developed using **HTML**, **CSS**, **Javascript**, **Typescript**, **React**, **Bootstrap**, **PostgreSQL**, and **Node.js**. Each website incorporated distinct human-computer interaction (HCI) principles to assess their impact on learning behaviors. User interactions were tracked using the **WebGazer.js** and **heatmap.js** eye-tracking libraries, with data stored locally via the **IndexedDB LocalForage** database. Screen recordings were also utilized to analyze user flows and interaction patterns.

<div style="display: flex; justify-content: space-around; align-items: center; margin: 20px 0;">
  <div style="display: flex; flex-direction: column; align-items: center;">
    <img src="/img/website-1.gif" alt="Website 1 Gif" style="width: 300px; height: 200px; object-fit: cover;">
    <p style="text-align: center;"><em>Scrollable Website format</em></p>
  </div>
  
  <div style="display: flex; flex-direction: column; align-items: center;">
    <img src="/img/website-1-heatmap.png" alt="Website 1 Heatmap" style="width: 300px; height: 200px; object-fit: cover;">
    <p style="text-align: center;"><em>Scrollable Website heatmap</em></p>
  </div>
</div>

<div style="display: flex; justify-content: space-around; align-items: center; margin: 20px 0;">
  <div style="display: flex; flex-direction: column; align-items: center;">
    <img src="/img/website-2.gif" alt="Website 2 Gif" style="width: 300px; height: 200px; object-fit: cover;">
    <p style="text-align: center;"><em>Multi-paged Website format</em></p>
  </div>
  
  <div style="display: flex; flex-direction: column; align-items: center;">
    <img src="/img/website-2-heatmap.png" alt="Website 2 Heatmap" style="width: 300px; height: 200px; object-fit: cover;">
    <p style="text-align: center;"><em>Multi-paged Website heatmap</em></p>
  </div>
</div>

A sample of 16 students enrolled in introductory computer sciences courses with minimal prior experience in Python were selected to ensure a consistent baseline for learning gains. These students were separated into groups of 8 and randomly assigned to a scrollable or multi-paged website. After exploring the websites, participants took a 10-question quiz that reviewed material covered in the websites. Participants explored the websites, completed a quiz on the content, and provided feedback through post-study surveys that captured their perceptions of the websites’ designs and their influence on the learning experience. Data analysis were conducted using ANOVA and t-tests to evalute the influence of user interface (UI) variations on cognitive processing and retention metrics. 

## Data Analysis & Discussion
Findings indicate that for this group of participants, scrollable websites improved their overall retention, as reflected by the average 63.76% average quiz score mean of the scrollable website group in compariso to the 56.25% average quiz score mean of the multi-paged website. When analyzing the results of the quizzes in a t-test we see that the p value for the two tailed test is above the 0.05 threshold to be considered statistically significant. However, after analyzing the data more closely, specific questions stood out in relation to how much time students spent on it and their correctness.

When analyzing a t-test based on the time spent on specific questions, the one-tailed p-value is 0.1013583416, which is closer to the less than 0.05 threshold, thus marking it as a trending value. In addition, for the question with the largest time difference between the two groups, the one-tailed p-value is 0.06286948428, which is also very close to the 0.05 threshold, suggesting a trend toward statistical significance. This indicates that the observed difference may not be due to chance and could point to a meaningful difference in how the groups approached this question. Thus, can determine that the scrollable website encourages more review, with certain question types aligning better with specific designs. Both websites were effective learning tools, though limitations such as the small sample size and small effect size should be considered.

## Future Considerations
Moving forward, there are several opportunities to expand on this study and address some of the limitations. Future research could focus on testing with a larger sample size to increase the reliability of the findings. Additionally, investigating how these design variations perform on mobile platforms would be valuable, given the growing use of mobile devices in education. Finally, embedded testing, where assessments are conducted in real-time after each section, could provide more immediate insights into student engagement and learning. These results emphasize the role of intentional digital design in fostering engagement, reducing visual overwhelm, and supporting effective cognitive processing. This study contributes to educational technology by emphasizing how intentional digital design best enhances engagement, information processing, and learning outcomes. These insights into HCI principles inform best practices for designing educational interfaces that decrease cognitive load to optimize student experiences and promote effective learning in digital environments.

## Research Reflection
This research provided me with invaluable experience in website development, particularly as it was my first time building two instructional websites entirely on my own. While I had previously worked on web development projects within a team, this self-led project required me to take full ownership, solving problems and debugging challenges independently. This experience, while sometimes difficult, was ultimately rewarding and greatly enhanced my technical skills. I hope this research highlights the importance of intentional digital design in enhancing student learning, particularly in the context of our rapidly evolving digital educational environments.

To view this project's Undergraduate Showcase presentation, click <a href="https://docs.google.com/presentation/d/14ttyQXkX_0pzTstjHHnKnqCS2nw2uBWTEVD7mS75Co0/edit?usp=sharing">here.</a>
