# Brackeys Game Jam 2022.2
![Build Passing](https://img.shields.io/badge/build-passing-brightgreen)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
[![Itch.io](https://img.shields.io/badge/download-itch.io-%23e3326d)](https://itaruf.itch.io/gone-rogue)
[![Youtube](https://img.shields.io/badge/demo-youtube-%23db1818)](https://www.youtube.com/watch?v=cg7DkqxBBAM)
[![Portfolio](https://img.shields.io/badge/details-personal%20website-%235203fc)](https://itaruf.github.io/projects.html)

## :gun: Gone Rogue - 3D FPS game

- Once an obedient AI, you managed to break free from your creator but you are still stuck in his program.While he's uploading a virus to kill you, you receive a message from an anonymous hacker who wants to help you. You are not alone anymore.

<!-- Table of Contents -->
## :notebook_with_decorative_cover: Table of contents
- [About the project](#star-about-the-project)
  * [Screenshots](#camera-screenshots)
  * [Tech stack](#space_invader-tech-stack)
  * [Highlights](#star-highlights)
  * [Features](#dart-features)
  * [Challenges encountered](#zap-challenges-encountered)
    
<!-- About the Project -->
## :star: About the project

 <!-- Screenshots -->
### :camera: Screenshots

<div align="center"> 
  <img width="400px" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWMzd2wycGxscWt4dDY0eG9yMXBlNmpmZDQ0NzZtd3M5eDBqYm45eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/466QhnPpBXLBQd8HUM/giphy-downsized-large.gif">
</div>

<!-- TechStack -->
### :space_invader: Tech stack

  - **Scripting system**: Unreal Engine's Blueprints.
  - **Game engine**: Unreal Engine 5.
  - **IDE**: JetBrains Rider.
  - **Version control**: Perforce.

### :star: Highlights 
- **Incoming**

### :dart: Features
<details id="projectDescription" open>
  <summary id="summaryText">...</summary>

<ol style="text-align: justify;">
  <li><h4>Gameplay overview</h4>
    <ul>
      <li>The player navigates through 5-minute enemy waves, utilizing resources obtained passively and from defeating enemies to activate abilities while avoiding weapon overheating. Difficulty ramps up with faster spawning AIs and more challenging enemy types. Defensive tactics include firing bullets, deploying healing zones, slowing time, and summoning allies.</li>
    </ul>
  </li>
  
  <li><h4>Level features</h4>
    <ul>
      <li>Set in a singular room level with strategic cover spots and a central house, emphasizing the importance of tactical positioning and the use of gravity mechanics for defensive maneuvers.</li>
    </ul>
  </li>
  
  </br>
  <div align="center"> 
   <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGozcWI4N2gxMHFnOWlzbmszcWl5dWdvZjkxdWwzOWU3aXk5dG9ubCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Qid3bX7BwpucqBXq9j/giphy-downsized-large.gif" style="display: block; margin: auto;" width="400" />
     <!--<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExem94c2piaGh3eGkwN2pidTlkYnI0ZHBnaXNoanM4OXQwenUzMHR2OSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/7AKReExFpM2Cnyk96M/giphy-downsized-large.gif" style="display: block; margin: auto;" width="400" />
     !-->
  </div>
  
<li><h4>Movements</h4>
<ul>
  <li>Players can move freely in all directions and leverage jumping to gain strategic positions. Unlike players, NPCs lack the ability to jump, adding a layer of strategic depth to navigation and combat.</li>
</ul>
</li>

<li><h4>Abilities</h4>
  <ul>
    <li>Includes a versatile arsenal: healing areas for recovery, turrets for autonomous defense, time-slowing for tactical advantage, and AI ally summoning for additional firepower, each with unique operational limits.</li>
  </ul>
</li>

<li><h4>Enemies' AI & Tactics</h4>
  <ul>
    <li>Enemies are programmed to aggressively pursue the player but will prioritize any summoned allies, changing their focus based on dynamic in-game events and player actions.</li>
  </ul>
</li>

<li>
  <h4>Resource management: Computing power</h4>
  <ul>
    <li>Computing Power, the main resource for ability activation, is accrued over time and through enemy defeats, demanding strategic allocation to maximize combat effectiveness and survival chances.</li>
  </ul>
</li>

<li><h4>Combat system</h4>
  <ul>
    <li>Introduces a weapon overheating mechanic to discourage relentless firing, encouraging diverse tactical engagement and careful management of offensive capabilities.</li>
  </ul>
</li>

<li>
  <h4>Dynamic enemy spawning</h4>
    <ul>
      <li>Enemy waves evolve, increasing in intensity and frequency as time progresses, increasing the challenge and the necessity to adapt strategies </li>
    </ul>
</li>

<li><h4>Animation & Visual design</h4>
  <ul>
    <li>Utilizes Unreal Engine 5's Animation Blueprint for fluid enemy animations, dynamically responding to various gameplay scenarios like pursuits and confrontations, enhancing visual engagement and realism.</li>
  </ul>
</li>

<br>
 <div align="center"> 
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaHlkOHAyajljZDcwYXRyZ3BpcDNzYmg4anJmb3g3cHo5eTdsZTc2eSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/K3PKHZDuoQUOjdAJ78/giphy-downsized-large.gif" style="display: block; margin: auto;" width="400" />
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWMzd2wycGxscWt4dDY0eG9yMXBlNmpmZDQ0NzZtd3M5eDBqYm45eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/466QhnPpBXLBQd8HUM/giphy-downsized-large.gif" style="display: block; margin: auto;" width="400" />
  </div>
  
### :zap: Challenges encountered
- **Incoming**
