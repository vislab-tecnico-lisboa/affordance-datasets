# hand-posture-affordances

This dataset contains results of trials in which the robot executes different actions with multiple hand postures on various objects. Below we show the experimental setup, with the iCub humanoid robot at the beginning of a robot–object interaction trial, and the visual perception routines in the background screen.

<img src="misc/icub_with_different_hands-smaller2_lighter.png" alt="Experimental setup." style="width: 800px;"/>

In the current version of this data, we consider 4 motor actions A (tapFromRight, tapFromLeft, draw, push), 2 objects O (lego piece, pear), and 3 hand postures H (straight fingers, arched fingers, bent fingers). We extract visual features from both O and H. Below is the distribution of the motion effects onto target objects caused by the robot influence when it touches object with its hand manipulator:

<img src="misc/all_hand_effects_2obj.png" alt="Distribution of effects." style="width: 800px;"/>

Each subplot displays the geometrical displacement along horizontal and vertical direction (in meters, measured from the object initial position) from the point of view of the robot (the robot is at the "0" along the x-axis marker). For example, tapping an object from the right (tapFromRight action) usually results in making the object shift to the left direction; drawing (i.e., pulling) an object closer only works if the manipulator morphology is appropriate.

If you use this dataset in your work, please cite the following publication(s):

* Giovanni Saponaro, Pedro Vicente, Atabak Dehban, Lorenzo Jamone, Alexandre Bernardino, José Santos-Victor. Learning at the Ends: From Hand to Tool Affordances in Humanoid Robots. IEEE International Conference on Development and Learning and on Epigenetic Robotics (ICDL-EpiRob 2017).

For more information, please contact gsaponaro at isr dot tecnico dot ulisboa dot pt.
