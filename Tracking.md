# Tracking

## What do we track?

We think of trackable things as rigid bodies in the environment, each with a fixed shape and size. Therefore, we can represent each item with a single position and rotation. The things we track in VR can mainly be considered in one of three categories:
1. The user's sense organs
	- The user's sense organs have DOFs that must be accounted for (or "undone") when rendering virtual worlds.
		- For example, the position and orientation of the user's eyes is used to render the world from their viewpoint.
		- The same goes for the user's ears, and audio rendering -- a similarly hard problem that we hear less of in modern games.
		- Both of the above are achieved in modern headsets by tracking the user's head orientation. However, alternatives do exist, like [eye tracking technologies.](https://en.wikipedia.org/wiki/Eye_tracking)
2. The user's body
	- In order to aid immersion and to give the user a sense of their location in a virtual space, it is helpful to track the user's body and recreate it in the experience.
	- Body tracking can also provide another, more intuitive layer of interaction with the virtual environment.
	- Unlike sensory organs, perfect tracking is less of a requirement with body parts
		- For comfort and ease of use, interactions with virtual objects can be simplified. For example, the act of picking up an object can be simplified to a press of a button.
3. Items in the environment


---
### References
1. Steven M. LaValle (2016), Virtual Reality, http://vr.cs.uiuc.edu/
