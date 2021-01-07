## Create a machine learning model

In this activity, you will use the amazing online machine learning engine called Teachable Machine with Scratch to create a project that will recognise different objects!

Teachable Machine is a web-based tool created by Google that makes creating machine learning models fast, easy, and accessible to everyone. As this project requires connection to the cloud based machine learning engine, offline work is not possible.

Let’s get started!


--- task ---
We’re going to use it to create a Vision project, so navigate to the [Teachable Machine](https://teachablemachine.withgoogle.com/train){:target="_blank"} site now and choose ‘Image Project’ from the three options:
 
![starter project](images/starter_project.png)

--- /task ---
What you can see here is your model **Workflow**:
![starter project](images/workflow.JPG)

We are going to add some classes on the left first. ‘Classes’ are the different sets of data we give our teachable machine.

Once we have created our datasets as classes, we will train our machine to recognise similarities and differences between our images in the class. 

Once trained, we’ll test and **export** your model so it can be used in Scratch!

--- task ---
Choose an object or picture to use as your subject. I used a printed out version of the Hacker Hotdog, but you could also use a toy or other image.
![Hotdog Man](images/hotdog-200x250.png)
--- /task ---

--- task ---

In the box labelled Class 1 click the button labelled ‘Webcam’.
![Webcam button](images/webcam.png)

--- /task ---

--- task ---

Take the first of your three objects or images and hold it in front of your webcam.

Hold down the blue ‘record’ button and move your object around in front of the camera so it captures all sides and odd angles you can show the camera.
![Record button](images/record.png)

--- collapse ---
---
title: Pro Tip
---
Try not to sit too still if you’re in the shot - it might mean the AI recognises you instead of the thing you want!

--- /collapse ---

--- /task ---

--- task ---
Rename the class to the thing you are holding up in the picture. This will help when you begin working in Scratch. I've called my class **hotdog**.
![Class Name Edit](images/classname.png)

--- /task ---

The Teachable Machine won't work with just one class. It needs a second one to compare against, so we will create that now.

--- task ---
Change the name of your second empty class to **not** and the name of your object. I called mine **nothotdog**.
![Class Name Edit 2](images/classname2.png)

--- /task ---

--- task ---
Hold down the record button under your empty class and move around in front of your camera, or hold up several things that are **NOT** your object. 

This will train the AI on things that are **not** your object and allow it to compare. 
![Class Name Edit 2](images/classname2.png)

--- /task ---

Now that we have our two datasets created, we will train the model to recognise the difference between them and tell us if it sees a hotdog or something else. 

--- task ---
To the right of the place where you can see your datasets, there is a grey button labelled **Train Model**. 

Click it to begin training the Teachable machine:
![Train Model Button](images/trainmodel.png)
**IMPORTANT:** Do **NOT** close or change your browser tab while you are waiting or the Training won't work!
![Training Warning](images/trainingwarning.png)

--- /task ---

You'll see a progress bar appear where the button was once you click it, showing how far through the training process the Teachable Machine has progressed:
![Training Progress Bar](images/progressbar.png)

--- task ---
Once you have trained your model, you can test that it works correctly by holding up the objects or images one at a time and watching the changing bands at the bottom left which show the AI’s certainty that it is looking at the object shown in one of the classes you made:
![Output Bars](images/outputbar.png)

Switch between different objects and watch the machine predict what it is seeing!

--- /task ---

The next step is to **Export** your model. This means saving the model online so you can use it in your Scratch project.

--- task ---
You can easily export your model by clicking the button shown on the top right of your screen:
![Export Button](images/exportbutton.png)

This will show you a popup asking you to choose few options.

Ensure you have **Upload (shareable link)** selected and click **Upload my model**. This will save your image recognition model to the cloud and return a URL we can use in Scratch.

![Export Options](images/exportoptions.png)

--- /task ---

--- task ---
Copy the URL shown under **Your shareable link:** by clicking the **Copy** button.
![Copy your shareable link](images/copybutton.png)

Leave this tab open, or paste your URL into a text file so you don't lose it - we'll need it for Scratch in just a minute!
--- /task ---
