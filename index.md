Autonomous robots often need to operate with and around humans, to provide added value to the collaborative team, to earn-and-prove trustworthiness, as well as to utilize the support from the human team-mates. The presence of humans brings additional challenges for robot decision-making, but also opportunities for improving the decision-making capabilities with human help. Two major computational paradigms for sequential decision-making are planning and learning.

Planning in multi-stage robotic problems is not trivial, mainly due to computational efficiency (due to the curse of dimensionality) and the need for accurate models. To plan more efficiently, researchers use hierarchical abstractions (e.g. Task and Motion Planning - TAMP). Representing the problem as TAMP enables to incorporate declarative knowledge and to achieve predictable and interpretable behavior. However, creating declarative models requires significant engineering effort and it is practically impossible to account in advance for all possible cases robots might face in the long-term operations in the wild. Therefore, life-long learning presents itself as a necessity and human help as a dependable source of knowledge! 

Learning methods achieved impressive capabilities, solely by improving performance based on the experience (e.g. trial-and-error, human demonstrations, corrections, etc.). However, they generally struggle with the long-term consequences of actions and the problems with the combinatorial structure. They can sometimes give solutions which are contradicting “common sense”, ignore causal effects, and forget previously learned skills (e.g. catastrophic forgetting). These issues are particularly prominent when it comes to life-long learning. Some of these issues might be avoided by using deliberate long-horizon reasoning (e.g. planning methods) and explicit human help.

Recently, a lot of research interest was shown in combined approaches utilizing synergies of planning and learning (e.g. neuro-symbolic AI). But still, principled integration of human input into these combined approaches is missing. Human input can play an important role in bridging planning and learning and enable reliable and trustworthy life-long learning with human help. It can be used for grounding learned models, providing “common sense” knowledge, teaching skills, setting goals, etc.

In this workshop, we aim to bring together researchers from the field of robot learning, symbolic AI (planning), and human-robot interaction to discuss emerging trends and define common challenges and new opportunities for cross-fertilization in these fields. The workshop schedule includes invited talks, spotlight presentations, and interdisciplinary panel discussions.   

We wish to provide some answers to these questions:
- How can we design robots operating side-by-side with humans with long-term autonomy, and capable of intuitively communicating and learning about “common sense” and human goals? 
- How can we utilize human input to improve robot generalization capabilities and skill transfer across tasks?
- How can we utilize learned models and human input for long-horizon deliberate reasoning? 
- How can we ground learned models and plans to be human interpretable? 

### Topics
We focus on enabling life-long learning with human help through:
- Interactive imitation learning
- Learning from demonstration
- Task and motion planning
- Hierarchical reinforcement learning
- Safe reinforcement learning
- Skill learning, cross-domain skill transfer and generalization
- Lifelong learning and curriculum learning
- Learning general robotic task specifications
- Modeling, symbolic model acquisition, representation learning
- Neuro-symbolic AI for robotics 


### Speakers 

<center>
<table style="width: 80%;">
  <tr>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;" > 
      <a href="https://andyzeng.github.io/" target="_blank">
        <img src="/docs/assets/images/speakers/andy.jpg" alt= "">
      </a>
    </td>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="https://dorsa.fyi/" target="_blank">
        <img src="/docs/assets/images/speakers/dorsa2.JPG" alt= "" >
      </a>
    </td>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="https://cs.brown.edu/people/gdk/" target="_blank">
        <img src="/docs/assets/images/speakers/george2.jpg" alt= "" >
      </a>
    </td>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="https://www.chalmers.se/en/persons/karinne" target="_blank">
        <img src="/docs/assets/images/speakers/karinne2.jpg" alt= "">
      </a>
    </td>
  </tr>  
  <tr>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Andy Zeng</b><br>Google AI, USA</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Dorsa Sadigh</b><br>Stanford University, USA</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>George Konidaris</b><br>Brown University, USA</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Karinne Ramirez-Amaro</b><br>Chalmers University of Technology, Sweden</td>
  </tr> 
</table>

<table style="width: 60%;">
  <tr>
    <td width="25%" style="text-align: center; vertical-align: middle; border: none;" > 
      <a href="https://mengguo.github.io/personal_site/" target="_blank">
        <img src="/docs/assets/images/speakers/meng.png" alt= "">
      </a>
    </td>
    <td width="25%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="https://www.robots.ox.ac.uk/~nickh/" target="_blank">
        <img src="/docs/assets/images/speakers/nick.jpeg" alt= "" >
      </a>
    </td>
    <td width="25%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="https://www.cs.utexas.edu/~pstone/" target="_blank">
        <img src="/docs/assets/images/speakers/peter2.png" alt= "" >
      </a>
    </td>
  </tr>  
  <tr>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Meng Guo</b><br>Peking University, China</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Nick Hawes</b><br>University of Oxford, UK</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Peter Stone</b><br>The University of Texas at Austin, USA</td>
  </tr> 
</table>

</center>

### Program (tentative)

TBD

### Important dates

- Workshop paper submission deadline: 28th April 2023 (AOE)
- Author notification: 12th May 2023
- Camera-ready: 24th May 2023
- Finalized workshop program: 25th May 2023
- Workshop date: **29<sup>th</sup> May 2023**

### Organizers 


<table style="width: 100%;">
  <tr>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;" >
      <a href="https://www.linkedin.com/in/zlatanajanovic/" target="_blank">
        <img src="/docs/assets/images/zlatan.jpg" alt= "" >
      </a>
    </td>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="http://jenskober.de/" target="_blank">
        <img src="/docs/assets/images/jens.jpeg" alt= "" >
      </a>
    </td>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="https://sites.google.com/view/janatumova/home" target="_blank">
        <img src="/docs/assets/images/tumova.jpeg" alt= "" >
      </a>
    </td>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="https://www.kth.se/profile/pek2" target="_blank">
        <img src="/docs/assets/images/chris.jpg" alt= "">
      </a>
    </td>
    <td width="20%" style="text-align: center; vertical-align: middle; border: none;"> 
      <a href="https://scholar.google.hr/citations?user=8v5fB_4AAAAJ" target="_blank">
        <img src="/docs/assets/images/selma.jpg" alt= "" >
      </a>
    </td>
  </tr>
  <tr>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Zlatan Ajanović</b><br>TU Delft</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Jens Kober</b><br>TU Delft</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Jana Tumova</b><br>KTH Royal Institute of Technology</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Christian Pek</b><br>KTH Royal Institute of Technology</td>
    <td style="text-align: center; vertical-align: top; border: none;"><b>Selma Musić</b><br>Stanford University</td>
  </tr> 
</table>



### Supporting IEEE RAS technical committees

<table style="border-collapse: collapse; border-spacing:0 " cellspacing="0" >
<thead>
  <tr>
    <td width="25%" style="border: none" rowspan="3">
      <img src="/docs/assets/images/RAS-logo.png" alt= "">
    </td>
    <td style="border: none; border-spacing:0; border-collapse: collapse">Technical Committee on Robot Learning</td>
  </tr>
  <tr>
    <td style="border: none; border-spacing:0; border-collapse: collapse">Technical Committee on Human-Robot Interaction and Communication</td>
  </tr>
  <tr>
    <td style="border: none; border-spacing:0; border-collapse: collapse">Technical Committee on Cognitive Robotics</td>
  </tr>
</thead>
</table>


### Ackwnowledgements



### Contact

[l3h2-workshop@googlegroups.com](mailto:l3h2-workshop@googlegroups.com)
