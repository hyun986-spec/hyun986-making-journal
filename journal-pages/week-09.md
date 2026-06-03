---
layout: default
---

# Week 09
---

[← Back to Home](../index.md)

# In-Class Activities
---
1. Project Statement: First Draft
2. Making Sprint
3. Round Robin Rapid Reactions


---

## 1. Project Statement: First Draft


### 1.1 Case Study

During this activity, I worked with a partner to explore Xeno Computer 0.1: Labor by Tega Brain and Sam Lavigne on the Miro board. We used sticky notes to respond to the provided questions and discuss the ideas presented in the project. This helped me think more deeply about the relationship between labour, technology, and data.

![alt text](../assets/week-09/week9-1.png) 
![alt text](../assets/week-09/week9-2.png)
(figures: screenshot of miroboard my opinion)

<br>

### Drafting with NotebookLM
저는 NotebookLM을 활용하여 프로젝트와 관련된 자료들을 정리하였다. 새로운 노트북을 생성한 뒤, Reflective Proposal, 7주차와 8주차 저널, 시각적 참고 자료, 데이터 출처 관련 자료 등을 업로드하였다. 이후 수업에서 제공된 프롬프트를 활용해 프로젝트 설명문(Project Statement) 초안을 생성해보았다.

![alt text](../assets/week-09/week9-3.png)

![alt text](../assets/week-09/week9-4.png)

<br>

### 1.2 Evaluation

**Strengths of the Draft:** I found that the draft generated with NotebookLM explained the overall intention and theme of the project effectively, but some parts no longer aligned with the project's current direction. In particular, the initial concept I had envisioned focused on a human figure composed of thousands of particles, whereas the project has since evolved to represent each participant’s data as a single individual particle. Therefore, I will revise the draft so that it more accurately reflects the structure and interaction methods of the current prototype.

**Areas That Need Further Development:** Although the section explaining the project’s purpose and intentions was generally accurate, the writing felt too abstract and broad. It did not sufficiently describe the specific elements that are central to the project, such as the unread message data, participant selection process, and the movement of the particles. Overall, the draft focused more on conceptual ideas than on the actual project itself, making it difficult to clearly understand what I am creating.

**Further Research and Next Steps:** I would like to further explore how communication avoidance is related to digital fatigue, managing relationships, and social expectations. I also want to find out what kinds of interactions work best when showing each participant’s data as individual particles. Another area I would like to research is how to make the data more visually interesting and easier to understand. This includes looking at how particle shape, movement, density, and connections can be used to show participants’ experiences and emotions in a clearer and more engaging way.

**Current Project Direction:** This project explores how leaving messages unread functions as a form of digital communication through an interactive particle visualisation based on survey responses, encouraging viewers to reflect on this behaviour and their own experiences.

<br>

### 1.3 Peer Share
Finally, I shared my draft and evaluation with a peer and exchanged feedback. After each of us spent about five minutes explaining our project, we discussed which aspects were communicated clearly and which areas could be further improved. This process helped me identify both the strengths and weaknesses of my current project and reflect on possible directions for future development.

**Feedback from Peer:**
- **What is clear and compelling?:** <br>"The connection between unread messages and communication avoidance is clear and interesting. I also think using particle movement as a way to represent behaviour has strong visual potential."
- **What still needs to be developed or resolved?:**<br> "I would like to see a stronger connection between the survey data and the interaction. It may also be useful to further explore how different participant responses can be distinguished visually."


<br>

---

## 2. Making Sprint

### 2.1 Sprint Planning (10 mins)

Before starting the making sprint, I reviewed the feedback and organised the main ideas into bullet points. I then used Gemini to help develop a prompt for the next stage of the project. I decided to display male and female participants together in a single view instead of separating them into different screens, making comparison easier. I also changed the colour mapping. Previously, colour represented the number of unread messages, but I reassigned it to gender: female participants are shown in pink (#ff00cc) and male participants in blue (#0efcfe). Since the unread message count is already displayed next to each particle, using colour for the same data felt unnecessary.

The main goals for this sprint were:

Represent each participant as a particle showing:
- Gender
- Whether they have unread/unanswered messages
- Number of unread/unanswered messages

*(The project also collected data on why participants did not read or reply to messages, but I have not yet found an effective way to visualise it. For now, I focused on the three data types above.)*

The planned visual mappings were:

- Background: Black
- Gender (colour)
  - Female: Pink (#ff00cc)
  - Male: Blue (#0efcfe)
- Unread message status and quantity (movement)
  - No unread messages: attracted to the mouse cursor
  - Has unread messages: avoids the mouse cursor
  - Avoidance strength:
    - 1–5 messages: 10
    - 6–20 messages: 20
    - 21–40 messages: 30
    - 40+ messages: 50

I also wanted to test whether this interaction effectively communicates communication avoidance and explore ways to incorporate the survey responses about why messages were left unread in future iterations.

<br>

### 2.2 Making Sprint Progress (35 mins)

<iframe src="https://editor.p5js.org/hyun986/full/GFdeqJ0E_" height="600" width="600"></iframe>


---

## 3. Round Robin Rapid Reactions

# AI Usage Statement
---
- Google. (2026). Gemini [Large language model]. https://gemini.google.com

- OpenAI. (2026). Codex [AI coding model]. https://openai.com


Google Gemini and OpenAI Codex were used only for coding assistance during the development of the p5.js prototype. These tools helped generate and explain example code for experimentation and testing. All final implementation and project decisions were completed by me.
