## Make an image detector

ANow you're going to take your exported model and make an image detector in Scratch!

--- task ---
Open the blank Machine Learning Scratch project (if you haven't already) [by clicking here.](http://rpf.io/ml-scratch){:target="_blank"} 

--- collapse ---
---
title: Pro Tip
---
You can open a blank Machine Learning Scratch project any time by going to [rpf.io/ml-scratch](http://rpf.io/ml-scratch){:target="_blank"}!

--- /collapse ---

--- /task ---

You should see a normal looking Scratch environment (with a few small differences) containing a single Sprite named Dani.

--- task ---

Make sure the sprite is selected before you start coding.
![Dani sprite](images/Dani.png)

--- /task ---

On the left, you'll notice some new menus that don't exist in the normal version of Scratch. These are special extensions created by MIT to work with some really cool new technology and they make this fork incompatible with the normal version of Scratch you usually use. 

What that means is that any projects you make here, won't work there. 

--- collapse ---
---
title: Saving Your Work
---
Because this fork of Scratch is different to the normal one, you won't be able to save your work the same way and your project will be incompatible with your Scratch account. You will need to download your project to your machine, and open it again **in this specific online version of Scratch** to use or edit it.

--- /collapse ---

--- task ---
For this project, you need to open the `Teachable Machine`{:class="block3extensions"} menu:
![Teachable Machine Menu Icon](images/tm_menu.png)

--- /task ---

--- task ---
Paste the URL you copied from the Teachable Machine in the previous step into the `Use Model`{:class="block3extensions"} block at the top of the menu:
![Teachable Machine Menu Icon](images/usemodelblock.png)

This will direct Scratch to access the model we just created and stored on the cloud, so it can detect *your* images.

--- /task ---

--- task ---

Add the updated `Use Model`{:class="block3extensions"} block, along with a `When green flag clicked`{:class="block3events"} block to your workspace.
![Script blocks 1](images/script1.png)

--- /task ---

This means that when we start our program, Scratch will immediately access your model from where it is stored. This takes a little time to initiate the first time you use it, so be patient when you run your project later.

--- task ---

Now add a `Turn video on`{:class="block3extensions"} block to make sure your camera can detect things, and a `Set video transparency to 0`{:class="block3extensions"} block so that the picture it provides is as clear as possible:
![Script blocks 2](images/script2.png)

--- /task ---

--- task ---

Click the green flag to instantiate your model and check to see if the camera is working.

--- /task ---

Now we need to create the script that will detect our two different classes, using the model we have just linked.

--- task ---

Drag a `When model detects`{:class="block3extensions"} block into your workspace and choose the first class name from the dropdown. In my example, it's ```hotdog```.
![Script blocks 3](images/script3.png)
--- /task ---

--- task ---

Drag a `say`{:class="block3looks"} block into your workspace and add a message that will indicate what is detected.
![Script blocks 4](images/script4.png)

--- /task ---

--- task ---

Repeat the above step, for your alternate class. In my example it's ```nothotdog```.
![Script blocks 5](images/script5.png)

--- /task ---

--- task ---

Click the green flag to run your new image detector!
![Running program](images/running.png)
--- /task ---
