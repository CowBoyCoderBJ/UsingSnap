# UsingSnap
1. (a) Build any Snap script that you like, as long as it includes the following:
• some interaction with the user,
• some form of repetition,
• a decision based on a yes-or-no answer,
• at least one variable,
• at least one user-defined block.
Be creative! Think about creating an interesting image, or telling a story, or playing a
game. Submit one XML file that contains your Snap script. Optionally, you can also
submit any written instructions that you think the user should have.
(b) In 1-2 paragraphs, describe a problem or a challenge you encountered while
you were developing your Snap script, and how you overcame it. This can be something
you tried that did not work as expected, or a feature you wanted to implement that
turned out to be more difficult than you first thought.

2. (a) In Snap, make a user-defined block called Snowflake in the Motion palette.
Have it receive one number, called length. Define this block as follows:
• If length is greater than 5, the sprite should draw the shape shown below, in
whatever direction it is facing. All four line segments are length/3 steps long, and
so is the distance between the two vertices. (What must the angles in the triangle
be?)
• If length is not greater than 5, the sprite should simply move length steps.
(b) [1 mark] Save your definition of Snowflake so that it appears in the Motion palette.
Right-click on this block in the Motion palette and open the editor. Notice that you can
drag the Snowflake block into its own definition. (This is called recursion.)
In the definition of Snowflake, edit the case where length> 5 so that wherever the
sprite originally moved length/3 steps, now it uses the Snowflake block with input
length/3. When this is done, you should be able to draw images like the following.
(c) Finally, use your Snowflake block, a repeat block, and a turn command to
draw this shape. Try to find a good starting position for the sprite so that the entire
snowflake is visible on the stage.
