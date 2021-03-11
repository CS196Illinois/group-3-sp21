How to make a player character?
1.	Import the "standard assets" package into to project 
2.	Look in the project view, in Standard Assets -> Prefabs.
3.	Drag the "First Person Controller" into our hierarchy.
4.	Use the scene view to position the new first-person controller wherever we would like it to start.
5.	Disable the old "Main Camera" by clicking it and un-checking the checkbox next to its name at the top of the inspector window.
6.	Hit play. We should now have a fully functional mouse-controlled first-person character.

Some quick notes about Unity:
1.	To make some places walkable: Navigation—Object—walkable
2.	To control the player: Add component—Player Controller—write code here
3.	To focus on the ground: Add a nonmovement mask—add new layer ground—select movement mask(ground)
4.	To set the viewpoint of the camera: create and add camera controller—add code

