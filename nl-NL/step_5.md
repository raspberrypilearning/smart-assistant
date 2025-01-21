## Create the assistant

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/R3e8nX4vKXo?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

Now that your model can distinguish between commands, you can use it in a Scratch program to create your smart assistant.

\--- task ---

- Klik op de link **< Terug naar project** en klik vervolgens op **Leer & Test**.

- Click on **Make**.

- Click on **Scratch 3**.

- Click on **Open in Scratch 3**.

\--- /task ---

\--- task ---

- Click on **Project templates** at the top and select the 'Smart classroom' project to load the fan and light sprites. This project also contains pre-made yellow `broadcast` blocks, which can be found under **Events**.

![Smart classroom project is selected in the Scratch templates](images/smart-classroom.png)

\--- /task ---

Machine Learning for Kids has added some special blocks to Scratch to allow you to use the model you just trained. Find them at the bottom of the blocks list.

![New 'smart assistant' blocks shown in the menu underneath Images](images/new-blocks-menu.png)

\--- task ---

- Make sure you have the **Classroom** sprite selected, then click on the **Code** tab and add this code:

![New scratch code: when flag clicked, forever, ask 'enter your command' and wait. If recognise text (answer) label = fan on, then broadcast turn-fan-on ](images/turn-fan-on.png)

\--- /task ---

\--- task ---

- Right click on the `if` block and select **Duplicate** to add a copy of the whole block of code, and put it directly underneath the first `if`.

- Change the second copy of the block so that it recognises the text for turning the fan **off**, and broadcasts **turn-fan-off**.

![New scratch code: If recognise text (answer) label = fan off, then broadcast turn-fan-off](images/turn-fan-off.png)

\--- /task ---

\--- task ---

- Click the **green flag** and type in a command to turn the fan on or off. Check that it has the result you expected.

- Make sure you test that the assistant performs the correct action **even for commands that you didn’t include as examples**.

\--- /task ---
