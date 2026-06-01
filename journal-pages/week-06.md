---
layout: default
---

# Week 06
---
[← Back to Home](../index.md)

# In-Class Activities
---
1. Data Exploration
2. Visual Research and Precedent Study
3. Project Planning and Skills Roadmap

<br>

## 1. Data Exploration
---
My data source is based on everyday communication behaviour, specifically focusing on the act of intentionally leaving messages unread. This project aims to explore not only the behaviour itself but also the psychological aspects behind it. The data will be collected from approximately 50 design students in this class through a simple survey. This group was chosen because participants are easily accessible within the same class environment. Participants will be asked whether they currently have any messages they are intentionally leaving unread and, if so, how many messages they are leaving unopened at that moment. (The number of participants may be adjusted if necessary.) At this stage, I plan to collect a minimal dataset focused on the presence and quantity of unread messages, keeping the structure simple and manageable.

I have developed two possible directions for visualising this data: 

#### 1. Online interactive outcome
![alt text](../assets/week-06/week6-1.png)
*(Image 1: Online interactive outcome)* 

The first is an online interactive outcome, where all participants’ data can be displayed together in a clear and accessible format. For example, users could view an overview of all data and click on individual entries to reveal more detailed information. This format also opens up the possibility of expanding the dataset in the future, such as including time-based data or categories of unread messages.

#### 2. 3D printed physical output

![alt text](../assets/week-06/week6-2.png)
*(Image 2: 3D printed physical output)*

The second direction is a 3D printed physical output. Due to spatial and technical limitations, it would be difficult to represent all participants’ data at once. Instead, this approach would focus on displaying one individual’s data at a time. For example, a single physical object could change its visual state based on the input data, potentially using LED lights to indicate the number of unread messages being left unattended. A key challenge in this approach is understanding how to connect data input to physical output, particularly how LED elements could be controlled through a system, possibly involving a computer or microcontroller. This is an area that requires further research and discussion with the tutor.


**List of questions for the tutor:**
- What tools or platforms are most suitable for controlling LEDs based on data?
- When linking survey data to LEDs, is real-time data integration necessary, or is manual input also acceptable?
- Is there a simple way to connect web-based data with a physical device such as LEDs?
- For beginners, what is the easiest form of physical computing to implement?

One limitation of this dataset is that it relies on self-reporting, which may lead to inaccuracies, as participants may not accurately remember or may underestimate their behaviour. Additionally, the dataset is relatively small and not representative of a wider population. However, from a Data Humanism perspective, this subjectivity and imperfection can still carry meaningful insight. Therefore, this project focuses more on encouraging reflection on personal behaviour rather than presenting objectively accurate data.

<br>

## 2. Visual Research and Precedent Study
---
### Online interactive outcome


#### 1. Tone.js Nuclear Fission

<a href="https://openprocessing.org/@alwayscodingsomething/2899558"> 
Tone.js Nuclear Fission Link</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/g51HRziXplw?si=n7TKIwFGOTMjwF6k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**What attracts me to it?** <br>
I was impressed by the visual effect where particles multiply exponentially every time the screen is touched, as well as its harmony with the sound. I felt this example is perfect for expressing the digital fatigue of modern people, where accumulating unread messages grow out of control.

**What will I take into my own work?** <br>
I want to reference the sound-responsive elements and the mechanism where the data multiplies and expands like cell division whenever the user interacts with the screen. Applying this to my work, it could be a possibility to show the number of unread messages data multiplying like cell division.

**Does it change or reinforce my direction?** <br>
It suggests a direction to express the pressure of unread messages through the visual metaphor of multiplication. It could be considered as a strong interactive method to visualize the heavy weight of growing data on an online screen.

<br>

#### 2. Verlet Particle Simulation

<a href="https://openprocessing.org/@ntsutae/2845802">
Verlet Particle Simulation Link</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/wxKSfhBJgZQ?si=lxJ2Q8g4fZ2hjkdJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**What attracts me to it?** <br>
I found the physics simulation highly appealing, where particles intentionally avoid and scatter away when the mouse cursor approaches. I thought this is very similar to the avoidance behavior of modern people, who purposely ignore and avoid communication from others even though they know a message has arrived.

**What will I take into my own work?** <br>
I want to incorporate the interactive physics feedback that seems to push away and escape from the user's movement. Applying this to my work, it could be a possibility to replace the cursor shape with a message icon.

**Does it change or reinforce my direction?** <br>
I believe this reference can help me untangle the psychological distance and avoidance tendencies in human relationships through mouse interaction. I can develop this into an interesting path that allows the audience to physically experience the avoidance of communication.

<br>

#### 3. Don't Touch Me

<a href="https://openprocessing.org/@noel/2812705"> 
Don't Touch Me Link</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/bvB5vSIyEtY?si=RP4d_wq1pX3opAUg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**What attracts me to it?** <br>
Like the previous example, the particles scatter away from the mouse cursor, but I found it fascinating how they have an elastic property to maintain their original circular shape without any gravity. It was impressive to see them break apart when the cursor approaches and then return to their original shape and become isolated again when the cursor moves away.

**What will I take into my own work?** <br>
I want to reference this self-maintaining property and implement the basic shape of the particles as a 'human silhouette' instead of a circle. I am planning an interaction where the human shape shatters to avoid contact from others, represented by the mouse, which I plan to change into a message icon, and then pieces back together into the form of an isolated individual once the mouse leaves.

**Does it change or reinforce my direction?** <br>
I learned that the psychology of avoiding communication can be attractively expressed through the visual narrative of destruction and restoration of a shape. I can use this to try a psychological visual effect on an online interactive outcome, where the human shape organically deconstructs and recombines based on the user's mouse movements.

<br>

#### 4. Multitap Text

<a href="https://openprocessing.org/@u110137/2703303"> 
Multitap Text Link</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/9sf_0VguScc?si=VXjLa2opVFd3fMmg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**What attracts me to it?** <br>
I was deeply impressed to see a phone model that I had originally planned to build as a physical 3D object, created digitally on a web browser screen and functioning smoothly at the click of a button.

**What will I take into my own work?** <br>
I want to incorporate the digital 3D spatial layout and dimensional text design techniques that respond three-dimensionally to mouse movements within a web screen.

**Does it change or reinforce my direction?** <br>
I found this to be the definitive turning point to pivot entirely toward an online interactive outcome between my two original options of an online vs. physical 3D project. Through previous assignments in my DES 240 class, I learned vibe coding and became comfortable enough with software implementation, but I had a lot of concerns because physical fabrication was completely new to me. I felt realistic limitations in sourcing the necessary LED components and building a hardware control system from scratch within a limited timeframe. This reference gave me the confidence that I can achieve the same tactile depth and even stronger interaction in a web environment without needing a complex offline structure.

<br>

#### 5. 250430a

<a href="https://openprocessing.org/@okazz/2631454"> 
250430a Link</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZSUqH0pB_uk?si=172tJQcSFBFsJ2_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**What attracts me to it?** <br>
I was impressed by how countless lights and dots move repeatedly to form a single pattern. In particular, I found it fascinating that while the individual elements are simple, they collectively create a complex and captivating visual effect.

**What will I take into my own work?** <br>
I want to bring the idea of individual data representation, which I originally planned to implement with physical LEDs, into an online grid layout, borrowing the structure to display the data of the 50 design students I surveyed neatly on a single screen.

**Does it change or reinforce my direction?** <br>
I saw the potential to absorb the limitations of physical LEDs into a web grid. I can use this to develop my project to visualise the collected data from 50 participants into a clean, organised 2D or 3D dashboard format that simultaneously displays both collective and individual data.

<br>

#### 6. V6 Puppet

<a href="https://openprocessing.org/@raizada/2654309"> 
V6 Puppet Link</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/p05LhdgdMr0?si=OHxMZF0r2J9qbtRK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**What attracts me to it?** <br>
I found the interaction fascinating, where computer vision technology tracks the user's joints and links them to a digital puppet's movements in real time.

**What will I take into my own work?** <br>
Applying this idea, I am considering a visual effect where the camera recognizes the user's body, and a human-shaped graphic is helplessly dragged around, tied to heavy objects or strings that represent the number of unread messages. Since this is not yet finalized, I might try this approach of linking the audience's physical movements and data as a potential option for my project.

**Does it change or reinforce my direction?** <br>
I discovered new technical possibilities to move beyond simple mouse clicks and explore interaction driven by body tracking, such as using a camera or sound. To maximize the immersion of the piece, I could explore this as a completely new narrative approach that integrates the audience's real-time physical data.

<br>

#### 7. Verlet Particle Simulation

<a href="https://openprocessing.org/@alwayscodingsomething/2899558"> 
Verlet Particle Simulation Link</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/wxKSfhBJgZQ?si=lxJ2Q8g4fZ2hjkdJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


<br>

#### 8. Verlet Particle Simulation

<a href="https://openprocessing.org/@alwayscodingsomething/2899558"> 
Verlet Particle Simulation Link</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/wxKSfhBJgZQ?si=lxJ2Q8g4fZ2hjkdJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>





### Physical output




## 3. Project Planning and Skills Roadmap

3.1 What do I need to make?

3.2 What do I need to learn?

3.3 What are my next steps?




## AI Usage Statement

*Document any use of AI tools under an AI Usage Statement heading. Explain which tools you used and describe how you used them. Reference any AI-generated content (see [QuickCite](https://auckland.libguides.com/referencing-generative-ai-tools) for guidance).*
