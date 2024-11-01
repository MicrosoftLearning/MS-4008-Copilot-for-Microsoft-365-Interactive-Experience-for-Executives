---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# MS-4008: Microsoft 365 Copilot interactive experience for executives 

## Content Directory

The demos for this course are based on the demos from the accelerator kit [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

It is important that you familiarize yourself with the demos prior to delivering this training. For several labs, you'll utilize sample documents and pre-created Teams meetings and emails.

- Pre-download all sample documents [here](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles).
- Setup Teams meetings and email threads by following the instructions [here](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Familiarize yourself with the Interactive experience's:
    - Option 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - Option 2: [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **NOTE:** If particpants do not have a Microsoft 365 Copilot license, they can utilize the free commercial version of the expereience found at [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE).

## Course Description

Discover how Microsoft 365 Copilot elevates workplace productivity and innovation. This experience, tailored for the modern business leader, provides insights on crafting contextual prompts for Copilot and includes engaging use case exercises that showcase seamless integration into daily workflows.

The primary objectives for this delivery is to:

- Introduce partipcants to Microsoft 365 Copilot and teach them how to craft an effective prompt
- Demonstrate Microsoft 365 Copilot in office apps (up to 3 demos)
- Guide participants through an interactive experience
- Invite participants to download and try Microsoft Copilot for Mobile

## Course Timing (Estimate) 

| # | Topic                                 | Total Time      |
|---|---------------------------------------|-----------------|
| 1 | Introudction to Microsoft 365 Copilot | 10 minutes    |
| 2 | An executive's guide to crafting effective prompts | 30 minutes      |
| 3 | Microsoft 365 Copilot Interactive Experience  | 20 minutes      |
|   |                                       | **Total time 60 minutes** |


Hyperlinks to each of the demos are listed below.

## Demos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
