---
layout: default
title: Thoughts
---

<style>
body { background: #111; color: #00ff00; font-family: 'Fira Mono', 'Consolas', monospace; }
.post { margin-bottom: 2em; background: #222; padding: 1em; border-radius: 10px; }
.post img { 
  max-width: 100%; 
  height: auto; 
  border: 2px solid #00ff00; 
  border-radius: 8px; 
  margin: 1em 0; 
  display: block;
}
.image-caption {
  text-align: center;
  font-style: italic;
  color: #0f0;
  margin-top: 0.5em;
  font-size: 0.9em;
}
.post a {
  color: #00ff00;
  text-decoration: underline;
}
.post a:hover {
  color: #0f0;
  text-decoration: none;
}
</style>

<h1>My own thoughts. Ignore the spelling and grammar mistakes, I'm a CS major.</h1>



<div class="post">
<p><em>7/6/2025</em></p>
<h2>Waze as a navigation tool</h2>
<p>Waze is very inaccurate when it comes to traffic. I had an hour longer commute than their estimated time. Is there not a better way to model/predict traffic? Additionally it routes all the people the same way, leading to more congestion on backroads. I'm not a UI guy, but think I could make something better. I'll that to the list of my projects I'll never start, I suppose. 
</p>
</div>


<div class="post">

<p><em>7/1/2025</em></p>
<h2>CarOps, and why I need a Waymo</h2>
<p>I think a lot about messing with my car to give it increased driving capabilities after the L2/L3 I could get with openpilot. Lidar is cheaper now, there's solid state lidar. Why not use those sensor. Plus I need more cameras, one is not enough. I want to get a new cluster, a digital one, not a fan of Toyota's design. It would be way cool if I could get the driving visualization on that, similar to what the older Tesla model S had. 
My current project is working on a framework/project I like to call "CarOPs". I think Tesla's FSD lacks explainability. It would be cool if you could actually know why the car made an incorrect decision.  Basically I want an end to end iterative self driving system with increased transparency over Tesla and open pilot. I want a framework where users, even those not well versed in AI/ml can understand their driving model, view the trajectory of the vehicle, and if the model makes an incorrect driving decision, be able to tell why it happened. I want the iterative design of mlops and human in the loop. I want a universal framework or something that could be run in all cars, instead of something like open pilot that works by overwriting the cars ecu signals.I am thinking about trying to figure out my own form of communication at the lower level as well. 
</p>
</div>

<div class="post">
<p><em>6/26/2025</em></p>
<h2>Tesla V Waymo </h2>
<p>I've been watching Waymo and Tesla's robotaxis compete in real time. Let's see how this goes. 
</p>
</div>



<div class="post">
<p><em>5/17/2025</em></p>
<h2>Welp I finished college.</h2>

<p> I just finished my ugrad degree and I still think a lot about what I want to do in my future. I have dreams about my future plans, but I'm not sure if I believe them. I have dreams of working for Tesla, Waymo, autonomous companies, but I don't know how to get there, or if that will still exist in the future. The irrational side of my mind wants to create my own self driving car. And build everything from the ground up.


I think about Machine learning. Not the stupid data science stuff or the bs math but the cool stuff. Creating the pipelines. Like an MlOps role. Working with unstructured data (videos, images) to get a prediction. Creating an inference service. Maybe work with LLMs. Maybe get to a point where I can create my own model architecture, but I've heard that's a graduate level thing. 

All geniuses do is modify algorithms, it's the same sh*t. In a couple of years, some car will get hacked or open pilot will be involved in an accident, and the government will get rid of OBD2 and replace it with some encrypted protocol. 

If I could pick anything, I want to develop an end to end self driving system using camera input. Fully autonomous (level 4), F you Tesla. So maybe I will come up with my own form of communication between motors and python. Write some driver in C, make my own complete system from low level to higher level. Deal with edge cases and current data biases. Making merging on the interstate autonomous. 

For now, I'm working a minimum wage job until my internship starts. Afterwards, I think I'm starting a grad school program. I'm going to CMU on Monday to look around and talk to some profs. Hoping that will help. </p>

</div>



<div class="post">
<p><em>5/7/2025</em></p>
<h2>VLMs </h2>
<p> All the cool kids (phds) are leaning towards VLMs. What is the major issue after reading DriveVLM? Latency, 1.9s is too long. Maybe we could apply multi latent attention to reduce the latency. But what do I know about anything, nothing. 
</p>
</div>



<div class="post">
<p><em>4/30/2025</em></p>
<h2>Waymo and Tesla </h2>
<p>Toyota is partnering with Waymo. For whatever it's worth, I had a self driving toyota before the cool kids were doing it. 
</p>
</div>


<div class="post">
<p><em>4/16/2025</em></p>
<h2>Research Papers</h2>
<p>Autonomous driving papers are interesting. Most of them test in ideal conditions, simulators, or just straight up talk about data. I understand that it's hard to replicate, but I want to see something. 
Drive the car autonomously or it didn't happen. Working in sem in ideal conditions is not a problem. The edge case, ie, highway driving are the issue. We don't need another fine tuned yolo model. (coming from someone who, in fact, has fine tuned many yolo models)
</p>
</div>



<div class="post">
<p><em>3/12/2025</em></p>
<h2>Insert LLM buzzword.</h2>
<p>I think this is interesting. https://arxiv.org/abs/2407.08735 
</p>
</div>


<div class="post">
<p><em>2/26/2025</em></p>
<h2>NN</h2>
<p> To quote the esteemed academics: "The deep neural network is very good because it is very deep"
</p>
</div>

<div class="post">
<p><em>1/27/2025</em></p>
<h2>My CS education</h2>
<p> As another fun semester of learning begins, I think more about my classes. I say in general, the CS classes include a week on how to ssh/terminal, explain what the empty set is, and then how do write very basic code in C. I would see that this remains constant for all the 300 levels, and then continues into some of the 400s. 
</p>
</div>




<div class="post">
<p><em>1/26/2025</em></p>
<h2>Attention is not all you need</h2>

<p> I was looking at an implementation of Multi-head Latent Attention (MLA) that was proposed in deep seek's paper. 
If we looked at self-attention, we would look at attention scaling quadratically, which isn't great for high resolution video. 

Ideally, MLA is supposed to introduce a smaller set of latent variables (m) instead of computing attention directly between all of the tokens in a sequence (n). Each token in the input attends to the latent variables, and each latent variable attends back to all of the tokens. There's a bidirectional exchange, but the attention computation is reduced from nxn to nxm. 

Here's what I'm thinking.  
If we take a sequence of 10k (thinking of image pixels), 64 latent variables (size used in paper), and a hidden dimension (d) of 512,

self-attention would compute: O(n^2 * d) = O(5.12 * 10^9)

mla: O(n *  m * d) = O(3.28 * 10^7)

So, that would make mla more efficient for handling video/image inputs, right? I would also think that latent variables would improve explainability, such as summarizing spatial regions of interest (image). I also figure in cases without global information, mla wouldn't be great, but then again, neither would self-attention. Or if input is small mla wouldn't be ideal, as the O(n^2) wouldn't matter as much. MLA also probably wouldn't be great for recurrence (looking a previous frames). I guess in a situation such as that you could do  LSTM + MLA.  I guess it would also be good for combination of sensor data camera + radar + liDAR, they could share a latent representation which would enable cross-modal attention without having to directly compute attention across tokens for each sensor. I don't know, just thinking. I was thinking a lot about multi camera openpilot over break. IE, connecting a backup camera and front facing camera, but turns out the smart people are right and it is difficult to efficiently simultaneously process camera feed on limited compute resources (hence why comma ai hasn't done that) Plus you would need to split an OBD2 connector.  An OBD2 'Y' cable I guess. Again I don't know what I'm talking about.
</p>

</div>



<div class="post">
<p><em>1/11/2025</em></p>
<h2>Katy OBD</h2>
<p>https://github.com/YangChuan80/KatyOBD Yes. Only arduino and canbus shield (MCP2515) to read can bus messages from a vehicle, and use a DBC file to interpret the messages. "Mom, we have openpilot at home." Bro who needs a 1k device when you have open source software and the internet?
Read the canbus messages and then decode using comma ai's opendbc API. Okay, cool. 
</p>
<img src="/photos/canbus.jpg" alt="Canbus." />
</div>


<div class="post">
<p><em>1/8/2025</em></p>
<h2>CES</h2>
<p> I just watched demo from Comma AI at CES on YouTube. I want to be there. Sh*t's cool.  
</p>
</div>



<div class="post">
<p><em>12/17/2024</em></p>
<h2>TensorFlow v PyTorch</h2>
<p> Everyone (one prof) wants to know why I use PyTorch. Despite being forced aganist my will to use TensorFlow in Marty White's class, and then switch back to do the same thing for intro to ml, I'll take PyTorch anyday.
PyTorch uses dynamic execution graphs, so yu can directly use print statements or debugging, TF has static graphs, so you have to define a computation graph to execute it. You cannot look at intermediate values with out doing tf.print. 
Then again, what do I know, as a lowely ugrad student. 
</p>
</div>


<div class="post">
<p><em>11/18/2024</em></p>
<h2>MyraFlow?</h2>
<p> Looking into TinyGrad, George's ML framework used in openpilot. Working on figuring it out by using it to write my own NN. It's got me thinking about optimaization, and writing my own library. 
I'd call in Myraflow, I think that sounds way cooler than MyraTorch. If I had the time, I would rewrite my hw in tingrad, but I don't think my prof would find that funny.
If I didn't have spanish, or anything else, I would make my own ML library from scratch. Not only for optimization, but to learn more about low level. All my ML classes cover the same stuff, I think this could be a cool project. 
</p>
</div>





<div class="post">
<p><em>11/8/2024</em></p>
<h2>SSH</h2>
<p> I'm gatekeeping my .ssh config. although if you ask nicely I'll probably help with it. Or if you go to my office hours and demand help, I'll also probably help you then. 
You wanna use a gpu? Drive to campus. 
</p>
</div>


<div class="post">
<p><em>11/8/2024</em></p>
<h2>Image Net</h2>
<p> Alex Krizhevsky was 26 when he wrote the imageNet paper. I''ve done nothing with my life. I have a not so good ugrad thesis. 
</p>
</div>


<div class="post">
<p><em>11/4/2024</em></p>
<h2>Today's Question</h2>
<p> At what point is a NN too shallow, when does using ReLU and dropout lead to excessive zeroed neurons? Too high dropout + too many zeroed out neurons = ineffective 
Is there a threshold, or just trivial and error? so much of ML is guessed boundary points. Idk, I asked my prof and he didn't know.
</p>
</div>


<div class="post">
<p><em>10/20/2024</em></p>
<h2>EMMA</h2>
<p> Waymo came out with an end to end LLM Driving model (EMMA). It is trained using text data from driving. I see no chance for anything to go wrong there. There will totally be no model hallunications. Plus you have to get the image data for driving, convert into text, then convert into embeddings. That's def slow.
What do I know, I'm not a phd student, or even close. 
</p>
</div>



<div class="post">
<p><em>10/6/2024</em></p>
<h2>Big Flavor</h2>

<img src="/photos/10-6-2024.jpg" alt="RedBull." />
<p> Big Flavor, Big Code. Thanks Mike. Another hackathon has started. Griffin Events? Banger.
After 36 hours of no sleep, I will sleep tonight, and then take two midterms tmrw. Actually, I will probably study tonight. 
</p>
</div>




<div class="post">
<p><em>9/15/2024</em></p>
<h2>Wammy @ VTHacks</h2>


<img src="/photos/vthacks.png" alt="Yep." />


<p>

The homies and I braved the drive via openpilot to VT for a hackathon. We ended up creating an LLM + RAG with Auth fullstack application for homebuying that was crazy accurate over using a traditional LLM. Despite not winning anything, multiple free meals + energy drinks were consumed, and new friends were made. VT has a nice campus, and the waffle house was great. Would return for future hackathon. 




</p>

<a href="https://devpost.com/software/homeview" target="_blank" style="color: #00ff00; text-decoration: underline;">Homeview</a>

</div>



<div class="post">
<p><em>6/8/2024</em></p>
<h2>Not_supercombo</h2>
<p>I'm writing my own more accurate verison of openpilot's supercombo model and I'm calling it Not_supercombo. 
</p>
</div>