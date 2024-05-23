Quadruped Autorigging Tool:

1. We have to first import our quadruped model (cat, dog, lion, tiger, or horse). <br>
2. Rename our model in the outliner to "Mesh". <br>
3. We can then start running our code. A GUI window will open called "Quadruped Autorigger" that has two buttons.<br>
4. We have to click on the first button called "Place pivot points" so that we can start adjusting the points that are located at the areas we should have joints at. However, if the points' size does not match the model's size, check number five.<br>
5. Another window opens called "Pivot point adjustment" that includes three buttons:<br>
    A. Maximize / Minimize pivot points: This button helps us scale all the points in order to match the model's size.<br>
    B. Adjust pivot points locations: If we would like to adjust a specific point again after scaling all the points up or down, choose this button.<br>
    C. Confirm: We choose this button to confirm that we have finished the points' adjustments and the window closes so we can get back to our first window.<br>
6. Now, we click on the second button in the "Quadruped Autorigger" window that is called "Finalize rigging". This button creates for us the skeleton at the same places of the pivot points adjusted by the user along with all the controllers and IK handles needed for moving the model.<br>
7. If we try to run the animation code, we get a GUI window for manipulating the speed that has a textbox and a button called "Play / Pause". We have to enter a value in the textbox and press the button so we can see the animal walk for one cycle using the value entered in the textbox as the animation's speed.<br>
