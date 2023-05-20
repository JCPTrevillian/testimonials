# testimonials
**Testimonials responsive page:  HTML | CSS | JAVASCRIPT**
\
\
This is a responsive patient testimonials page that slides from patient testimonial page to patient testimonial page by clicking the round buttons 
below the image and text box. The elongated oval button informs user where they are within sequential order of the 4 testimonials. 
\
\
\
***This is the rendering for each patient testimonial when you click the button:*** 
\
\
![pt1](https://github.com/JCPTrevillian/testimonials/assets/95890754/076cab5c-ef46-4eaa-9eda-24c906250a1c)
\
\
\
![pt2](https://github.com/JCPTrevillian/testimonials/assets/95890754/bbe45a18-cf57-410f-b213-030dfccd91b8)
\
\
\
![pt3](https://github.com/JCPTrevillian/testimonials/assets/95890754/8e682ebf-be94-4909-bede-0786c9c7531d)
\
\
\
![pt4](https://github.com/JCPTrevillian/testimonials/assets/95890754/8622a983-e597-479f-b06f-8157abd44a9e)
\
\
\
**The setup for each of the 4 patients testimonial page (image, testimonial, patient name, and patient location) was initially set up
with the first patient and once I verified everything looked the way it was intended, I repeated it for the next 
3 patients.** 
\
\
![1](https://github.com/JCPTrevillian/testimonials/assets/95890754/c87dc46c-9be7-47ac-923a-2b5e262c50fd)
\
\
**The setup for the patient testimonials opened with a list of classes of the element that allow CSS and Javascript to select 
and access specific elements via Document.getelementsByClassName() and/or Document.getelementsByID() you will see used later in 
lines 67 and 68 of index.HTML**
\
\
![2](https://github.com/JCPTrevillian/testimonials/assets/95890754/afa4f86a-df2d-42d6-a478-76f634c4142e)
\
\
![3](https://github.com/JCPTrevillian/testimonials/assets/95890754/db993531-a316-4793-9dfd-20adea74cd6c)
\
\
**The event handler that responds when user clicks (onClick) the buttons below the testimonials. Each button counts where it is +1
to advance "active" to the next testimonial and remove active from the previous one.**
\
\
![4](https://github.com/JCPTrevillian/testimonials/assets/95890754/d91f3f6f-389f-4556-b983-3d89973cbcd7)
\
\
**Container and indicator classes for button when the event handler is initiated. First button has "active" which means the elongated button for whichever of the 4 options are chosen (index 0 so buttons are 0,1,2,3)** 
\
\
![5](https://github.com/JCPTrevillian/testimonials/assets/95890754/b3a8b343-42c0-4fcb-8aa1-806847a63f5e)
\
\
**The CSS challenges: overlaying the textbox with the image without imposing too much on the image space. Initially the text box UR and LR corners were tucked behind the image. z-index (line 52) resolved that by bringing the right corners tucked behind the image forward but it was imposing too much onto the image. Not wanting to sacrifice the size of the image, I reduced the text box width and height to maintain the rectangular shape while allowing reasonable overlap. Border-radius rounded the corners for a polished look.** 
\
\
![6](https://github.com/JCPTrevillian/testimonials/assets/95890754/1ff95dae-084e-4b30-95d6-3e14ece71328)

