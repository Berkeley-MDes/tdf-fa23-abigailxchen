## Quick Links ##

- [TDF Wiki](https://github.com/Berkeley-MDes/desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/folders/1OjFgu4llHn-2WayQFVWRKFyOkQ_WaQRx?usp=drive_link) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1528355) - where the grading happens

 ---
 
# 💡 Report 1 - Week of 08/28/23
## Abigail Chen, Technology Design Foundations

## 📎 Description

✨📱 This week, I designed a cool phone stand. 

I played around with the Rhino sliders and adjusted the following parameters:

🔺 phone width: 77mm


🔺 phone length: 153 mm


🔺 phone depth: 22.6 mm (my phone is quite phat because it has a cardholder with several cards) 


🔺 material width: 3mm 


I chose acrylic as my material because I think it looks cool, and it was the only thick scrap material that I could find.


## :bug: The nasty bugs I encountered and how I fixed them!
1. **Weird Bugs**
   
   Whenever I closed the control panel, Grasshopper would start tweaking and throw a Display Error that evilly forced me to quit the program. This turned out to be a strange Mac bug that I solved with the classic Restart.
3. **Perspective**
   
   The first time I tried baking my model, I baked at the wrong perspective and got an angled bake. Oops! I solved this by switching to top view (Cody said that in all his 17 years of using Rhino he has only ever used Top, Perspective, and 4Views).
5. **Baking**
   
   I forgot to change the default bake scale, so my first bake was **way** too small. After this, I changed the scale to 1:1.
   The second baking challenge (This feels like the Great British Bake-Off) was that after I baked to an Illustrator file, I would open the file to a blank page. This was because my model was not centered in Rhino and thus when converted to Illustrator it was **way** too far off of the artboard to be seen. To solve this, I used the Move command in Rhino and moved my model to 0.

## 📷 Photos

![image](illustrator.jpg)

![image](smiley.jpg)

![image](stand.jpg)



Depiction of The Triumph of Successful Laser Cutting (2023, colorized) 💖

![gif](joy.gif)

---

# 💡 Report 2 - Week of 09/07/23
## Abigail Chen, Technology Design Foundations

## 📎 Description

![image](tjvideo.jpeg)

This week, I watched TJ's video tutorial titled "Cell Phone Stand Design, Evaluation, and Publication" and worked off of it to create a 3D-printable phone stand customized to the parameters of my own phone, using the same parameters as the previous report. 

## 🧠 What I Learned
- I **finally** learned the syntax of naming in Grasshopper. In the gray rectangles, the first word is what it represents, and everything following that is the name customized by the user.
- I also **finally** learned what Brep means. Boundary representation!!! Brep rep!!
- I learned how to create models from scratch using parametric modeling.
- I learned how to check if a model is stable and how to implement a color-coding system to determine this

### 📷 My Model!
![image](rhinostand.jpeg)

### 🤔 Important Questions to Ask Before Baking
- Is the model stable?
- Do any sections of the model seem too thin or easily breakable when printed?
- Is there unnecessary volume that can be removed before printing to reduce waste? 


## 💭 Takeaways
This tutorial helped me better understand the power of computational design and parametric modeling. As a designer who has only 3D modeled from scratch in software like Cinema 4D and Blender, this was my first time designing for scalable designs computationally. This is an extremely powerful tool that allows designers to include the decisions that they care about in the tool where they're making the decisions. No more redesigning your entire model if its position changes. No more finnicking with tiny details that will end up having to be changed. I also appreciate the open source spirit of ShapeDiver, the cloud application for Grasshopper. Anyone with access to the Internet can play with these models! Everyone gets a model! 

## ➡️ Future Considerations
In the future, I can 3D print the model that I designed today and test it further to see how this design works physically. Getting my hands dirty and simply printing something will be very exciting and help me improve for my next iteration!

---

 
# 💡 Report 3 - Week of 09/14/23
## Abigail Chen, Technology Design Foundations

## 📎 Description

This year, I recently bought an iPad Pro for school. Unfortunately, I haven't gotten around to buying an iPad stand, so that it can be a part of my **triple** monitor setup at home (very useful when using Rhino and Grasshopper). But no worries! I can **BUILD** my own iPad stand with the skills that I've learned in TDF!! 

## 🔍 Research

I began my research portion of this assignment by browsing the Interwebs of existing iPad stand models to use as inspiration. I stumbled upon a few models on Cults, a 3D printing marketplace that allows makers to share free and paid models meant for 3D printing (it's also a social network for 3D printing enthusiasts!) Two, in particular, caught my eye. 

### [iPad Stand 1️⃣](https://cults3d.com/en/3d-model/gadget/ipad-stand-juribe2)

![iPad1](ipad1.jpeg)

![iPad1](ipadstand1.jpeg)

iPad Stand 1 seemed like a really nice standard mdoel. However, as a novice, I was a bit befuddled at how to create the geometries that would go into this, especially the curve and the volumes to create the gaps in the model. 

### [iPad Stand 2️⃣](https://cults3d.com/en/3d-model/gadget/tablet-stand-for-ipad-pro-with-options)

![iPad1](ipad2.jpeg)

![iPad1](ipadstand2.jpeg)

This model I really enjoyed first of all because it has an AirPods holder! This is definitely something that I need for my desk as I often misplace my AirPods (I've lost two AirPods/cases before. I'm on my third. Wish me luck). Also, this model included a screenshot of the model in the software, which would help when designing. 

#### Winner: iPad Stand 2! 🥳 


## 🏛️ Modeling


![model](myipadstand.jpeg)

![modelwphone](myipadstandwphone.jpeg)

![grasshopper](grasshopper.jpeg)

## ➡️ Future Considerations

For my final submission, I would like to tweak the parametrics of my Grasshopper file, so that the iPad stand will adjust dynamically to changes of the iPad. I also want to print and see how it turns out! 

Check out my video [here](https://www.youtube.com/watch?v=OEmV8QkV3yI)!








