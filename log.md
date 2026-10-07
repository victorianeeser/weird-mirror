# This is my build log

## 09/09/2026 — I started this project 

## 09/15/2026 — Homework 1: TouchDesigner
I really wanted to understand TouchDesigner first, without the use of Claude doing it all for me. To do so, I found a great crash course on Youtube by **The Interactive & Immersive HQ** (https://www.youtube.com/watch?v=g20Qwg8gMBE&list=PLpuCjVEMQha9rjhDET3uuE0T3UeIcROJu). Although it is 27 videos, I only followed along and went through the first 20 and felt like I had enough knowledge to continue to play around with it myself. * Note - it did take me roughly 5 hours * 

At first, it was confusing because you had to jump right in, but this channel does a great job of introducing you to new concepts and then building off of them. The videos were honestly great at explaining COMP, TOP, CHOP, SOP, MAT, & DAT. I feel like I have an understanding of when you would use each instance now. 

After completing the tutorials and doing the assignments per each video, I was able to create an effect where it is raining bananas from the top of the screen, and when you move, so do the bananas. My next goal is to get Claude connected to TouchDesigner.

## 09/16/2026 — MCP
I was able to conntect the Claude to TouchDesigner, but it took a lot of back and forth to understand what to do and how to connect everything. After I got everyhting, it was pretty easy to do and manage.

However, I am glad I did all of the TouchDesigner learning yesterday because once Claude did it's thing, I was able to go back in and look at the file and **actually understand what Claude did.**

When I connected it to Claude, I just asked it to do a simple function. When you move your hand from left to right, it impacts the color value on the screen. Going to your right, makes it really green. Going to the left makes it really purple. Inbetween are all the colors of the rainbow.

## 09/19/2026 - 3 designers & 10 concepts
**Dominic Harris — "Origins of Imagination" (2024, Naturalis Biodiversity Center)** 
Visitors hand-draw a butterfly, which an AI trained on the museum's real specimens turns into a realistic-looking digital butterfly that then joins a swarm flying free across a projected space. https://fadmagazine.com/2024/11/27/ai-powered-new-interactive-artwork-from-dominic-harris-unveiled/
- Inputs: a visitor's hand-drawn butterfly, scanned in. 
- Outputs: an AI-generated digital butterfly added to an evolving projected swarm. 
- Concept: inspired by Darwin's children doodling on his manuscript — visitors become co-creators in a continuously evolving digital ecosystem.

**TeamLab — "Flutter of Butterflies Beyond Borders, Ephemeral Life Born from People" (touring 2022–2024, now permanent at ArtScience Museum Singapore)**
Standing still causes a chrysalis to appear on a visitor's body and a butterfly to emerge and fly off, but touching a butterfly kills it.
https://www.teamlab.art/w/butterflies_ephemerallife_people/ 
- Inputs: a visitor's presence/stillness (birth) and touch (death). 
- Outputs: real-time-rendered butterflies that dance through the space and cross into neighboring artworks. 
- Concept: people usually notice butterflies being born from others before realizing they're doing it too — interconnectedness rippling through a shared space.

**Ronen Tanchum — "Human Atmospheres" (2026, World Economic Forum, Davos)**
An interactive generative landscape that merges live climate data with visitor movement and live music, turning the room into a shifting mountain/cloud environment that responds to the people in it.
https://prforartists.com/human-atmospheres-ronen-tanchum-world-economic-forum-davos/ 
- Inputs: attendees' physical movement (slow steps draw drifting clouds, sudden gestures summon storms) and live musical performance, layered on real-time Davos weather data. 
- Outputs: a dynamic projected landscape of mountains, clouds, and weather that shifts in response to both. 
- Concept: Tanchum calls it "an emotional mirror of the climate we live within and the presence we project into it" literally framed as a mirror, which lines up nicely with your project's own name.

My 10 concepts are in concepts.md

## 09/22/2026 - Concept Rough Draft
Today I wanted to explore what my final concept is going to be and how I am going to do it. For my final concept, I want to do something with earth and show how it has changed overtime, showing the result of climate change and other factors. I think this could be really cool overall if I had one hand controll the timeline of everything and the other hand could zoom in and out on the globe.

As I was trying to get Claude and TouchDesigner running together I encountered many errors a long the way. I tried to start with handtracking the globe so as you move, so does it. However, after 5 errors of it not working, I took a step back and made just a rotating globe to start. 

![alt text](<Screenshot 2026-09-22 at 5.32.18 PM.png>)

![alt text](<Screenshot 2026-09-22 at 9.26.13 PM.png>)

## 09/25/2026 - Flow
After a few more tries of running everything and after it crashed 3 more times, I was able to get it to work!!! Here is my concept: As your hand moves, so does the globe. I was able to find a video from NASA that already had everything laid out in the way I wanted. 

My goal was to get everything working and show my proof of concept. I don't know if my final version could be built out on an actual globe or something. I also want to add a feature where you can zoom in and out. 

To see the video, It is 9:25.mov. 

## 09/29/2026 - Claude pulling data to make globe
I was able to have Claude pull the points and I wanted to try making it manually. It could work but I think my version needs a lot more work. Claude was able to make the basics with a globe and rotating, but it couldn't really create the same visual when it comes to the data points. 

Maybe I will go back to the video version, but make some more tweaks instead, to make it more customized. 

Here is the version Claude made when given that data only. 
![alt text](<Screenshot 2026-09-30 at 5.48.17 PM.png>) 

## 10/03/2026 - Figuring out the globe 
I first started by importing my video into CapCut. Then I removed the background. I then put that video into TouchDesigner. 

 **Version 1:** I played around with what it would look like on a black screen with a timeline at the bottom and a viewfinder in the top right corner. I think this works, but I want something more that the viewer would think is interesting
    ![alt text](<Screenshot 2026-10-04 at 4.41.28 PM.png>)

 **Version 2:**  I took the globe and timeline and put it on the viewfinder screen. I made sure to offcenter it so the viewer knows where to position themselves. I think I like this version the best because as you scroll, you are able to see the effect happening to you as well. 
    ![alt text](<Screenshot 2026-10-04 at 5.11.01 PM.png>)

Now that I have my protoype in the final state, I am going to user test with people!

I was able to go to Morning Fog Cafe and get some user testing done during breakfast time. I went up to three people who looked like they weren't too busy. Two were okay were okay with a photo, one prefered not to be. For this usertesting, my focus was to see **which version they liked.**

**User 1:** 
He liked the version where you could see themselves better. He thought that it was more engaging to the user because they are getting impacted by the climate change.

**User 2:** 
She liked the second version, but wanted the time line to get a little bigger. Maybe it gets more red once you get more into recent years. 

**User 3:**
She took more of the pulling the timeline approch, which was interesting. The other two moved their hands back and forth. She wanted the "melting" animation at the end to be a little smoother, don't flash the red, it becomes more of a graident instead.

![alt text](UserTesting.png)

## 10/05/2026 - Final Changes
After user testing and getting my final round of feedback here are changes I made to enhance the experience
1. Make the auto play stop at the 2000's. This allows the user to see that the screen gets a little red, but doesn't see the extreme effects just yet.
2. When the users hand is up, the big timeline number turns red and gets a little bigger. This is another affordance that could help the user figure out what to do.
3. Sharpen the quality of the globe to the best of my ability. Claude said it is at it's max due to this being the free version of TouchDesigner. It said we could split the video up and get it clearer, but then we risk the scrubbing not working properly and since this has to run without breaking, I'd rather not risk it. 
4. Make the globe bigger, so it almost is a half and half on the screen. 
5. Make the smaller timeline numbers bigger.

I am going to do one more quick round of testing with my peers before I turn in the final. After a quick check in, I made a small tweak to the numbers at the bottom, but besides that, it functions properly. 

![alt text](<Screenshot 2026-10-05 at 8.12.12 PM.png>)
 

## 10/06/2026 - Final Project
Here is the link to the final video demonstration 
https://vimeo.com/1233886693?share=copy&fl=sv&fe=ci

Overall, I really did like this project. Although I had some setbacks at the start, I think my final version is able to capture what I had envisioned in my head. The project was challenging at times with Python or my computer crashing, but the best thing I could do, was just to keep making and trying out new prompts in order to get it how I want.

If I were to continue working, I would start by making the video clearer. Claude said that would be possible, but we would have to break up the original video into multiple parts, which can lead to more room for error and breaking with the scrubbing, so it advised me to hold off on that for now. For this class, I wanted everything to run properly, but if I were to continue working, that would be my next step.
