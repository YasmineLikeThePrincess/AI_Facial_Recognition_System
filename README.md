# AI Facial Recognition System
![image](https://github.com/user-attachments/assets/6bf9d517-2bdd-4c99-8c2c-14168df43374)

I'm a student in Matser Degree Data & AI applied to buisness in Paris, and I am very interesting about Data Science.

For train my self on Data Science project, we imagine with my colleague Hoda Dades, a system of attendance based on facial recognition. 
It's my first project in Data Science or Machine Learning, so it's pretty basic but I have learned a lot and it's takes a lot of hours. Whenever it was first a lot of pleasure. 

# The process

So we have a data base where is our list of student who must be present at courses. And each student is associate to his picture. 
To make the attendance, the students have came in front of a camera for a photo. The photo go in download and then we have to run the notebook. This photo will be compared with all the pictures in the pictures in the folder "positive" (where is
the picture of all the student). To compare we use a Face Net modal from PyTorch, who calculate the embedding of the face to recognize a person. 
If it's True, that's mean that the result of the modal is less than 1 and it's an student of our data base, and so he will be add on the attendance list. 

# The interface

We made something very simple with html code and run it in local with the XAAMP server. 

# To be continued

It's my first project so there is so much things to improve, like I didn't succes to connect directly the html code and the python code. So I would like to have some advice for improve 
this project.
