# Bellatrix
## AR gaming platform - Winner, Yahoo! Japan Hackathon

We create an augmented reality gaming platform. We project a game on a screen, and a camera records the user interaction with the screen.


The project was inspired by [Interactive Squash][1] who seem to have centered their product around making a 21st-century squash arena which is capable of detailed analysis and assisting with advanced training. However, we figured that we could use this for any game. You can see a video of a game of darts being played over [here](https://www.youtube.com/watch?time_continue=16&v=v_A9FpL3Sa4). <br/>

The most trivial interaction is hitting the screen, say a softball hitting the screen in a game of “darts” and the area where it hit determining the score. The key challenge here was accurately determining a foreign object in the camera recording and deciding if it touches the screen. We use the difference of the image being projected and that being recorded to localize the foreign object and then track its speed to determine the hit location. The frame rate of the camera and lighting conditions put limitations on our implementation, as with most CV applications.

We created this during a hackathon organized by Yahoo! Japan and won the Best Tech Prize. 

Thanks to _Abhijit Tomar, Shievani Upadhyay, Kumar Ayush and Meet Udeshi_ for working with me on this project.


[1]: http://interactivesquash.com/
