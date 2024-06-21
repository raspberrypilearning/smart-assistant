## Create the assistant

Now that your model can distinguish between commands, you can use it in a Scratch program to create your smart assistant.

--- task ---
+ Click on the **< Back to project** link.

+ Click on **Make**.

+ Click on **Scratch 3**.

+ Click on **Open in Scratch 3**.

--- /task ---

--- task ---
+ Click on **Project templates** at the top and select the 'Smart classroom' project to load the fan and light sprites. 

![Smart classroom project](images/smart-classroom.png)
--- /task ---

Machine Learning for Kids has added some special blocks to Scratch to allow you to use the model you just trained. Find them at the bottom of the blocks list.

![New blocks](images/new-blocks-menu.png)

--- task ---

+ Make sure you have the **Classroom** sprite selected, then click on the **Code** tab and add this code:

![New scratch code including new machine learning blocks](images/turn-fan-on.png)
--- /task ---

--- task ---

+ Right click on the `if` block and select 'Duplicate' to add a copy of the whole block of code, and put it directly underneath the first `if`. 

+ Change the second copy so that it recognises the text for turning the fan **off**, and broadcasts **turn-fan-off**.

![New scratch code including new machine learning blocks](images/turn-fan-off.png)
--- /task ---

--- task ---
+ Click the **green flag** and type in a command to turn the fan on or off. Check that it has the result you expected. 

+ Make sure you test that the assistant performs the correct action **even for commands that you didn’t include as examples.**

--- /task ---
