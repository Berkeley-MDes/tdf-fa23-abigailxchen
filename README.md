## Quick Links ##

- [TDF Wiki](https://github.com/Berkeley-MDes/desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/folders/1OjFgu4llHn-2WayQFVWRKFyOkQ_WaQRx?usp=drive_link) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1528355) - where the grading happens

 ---
 
# Report 1 - Week of 08/28/23
## Abigail Chen, Technology Design Foundations

This week, I designed a cool phone stand. ✨📱

I played around with the Rhino sliders and adjusted the following parameters:
🔺 width: 77mm
🔺 length: 153 mm
🔺 depth: 22.6 mm
🔺 material width: 3mm


### Here are the nasty bugs :bug: I encountered and how I fixed them! 
1. **Weird Bugs**
   
   Whenever I closed the control panel, Grasshopper would start tweaking and throw a Display Error that evilly forced me to quit the program. This turned out to be a strange Mac bug that I solved with the classic Restart.
3. **Perspective**
   
   The first time I tried baking my model, I baked at the wrong perspective and got an angled bake. Oops! I solved this by switching to top view (Cody said that in all his 17 years of using Rhino he has only ever used Top, Perspective, and 4Views).
5. **Baking**
   
   I forgot to change the default bake scale, so my first bake was **way** too small. After this, I changed the scale to 1:1.
   The second baking challenge (This feels like the Great British Bake-Off) was that after I baked to an Illustrator file, I would open the file to a blank page. This was because my model was not centered in Rhino and thus when converted to Illustrator it was **way** too far off of the artboard to be seen. To solve this, I used the Move command in Rhino and moved my model to 0. 


<img width="200" alt="Cool Phone Stand made of rocks" src="https://github.com/s-almeda/tdf-template-repo/assets/21287693/bc2f1864-af5a-456d-9a71-e1d80d51190c">


