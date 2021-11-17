# Procedural Generation advanced topic presentation outline

## Presentation 1: Roguelike

* **The importance of procedural generation in a roguelike (~10 min)**
	* Short overview of our game and mechanics
	* Definition of procedural generation
		* Examples of things that are often procedurally generated
	* Reasons why procedural generation is important
	* Examples of games that use procedural generation
* **Heuristics for procedural generation (~10 min)**
	* Things a procedural generation algorithm needs to have
	* Things a procedural generation algorithm could have to improve it
* **Possible strategies for procedural generation in our game (~15 min)**
	* First algorithm we considered (Mike Anderson's Dungeon-Building Algorithm)
		* How it works
		* Advantages
		* Drawbacks
	* Second algorithm we considered (Cyclic Procedural Content Generation)
		* How it works
		* Advantages
		* Drawbacks
* **The procedural generation strategy we chose (~10 min)**
	* How it works
	* Why we chose this algorithm over the others
	* Foreseeable issues with this algorithm in our game

## Presentation 2: Infinite Runner

* **Speaker 1 (10 min)**
	* How procedural generation is used in infinite runners
	* Algorithms we are utilizing
		* Perlin noise
			* Main idea / introduction & common applications
		* Bezier curves
			* Main idea / introduction & common applications

* **Speaker 2 (10 min)**
	* Perlin noise in-depth
		* Premise behind Perlin Noise
		* One dimensional algorithm
		* Two dimensional algorithm
		* Visualizations and use cases
		* Math details

* **Speaker 3: (15 min)**
	* Bezier Curves in-depth
		* Algorithm walk-through
			* Linear interpolation - the main idea of Bezier curves
			* The different kinds of Bezier curves
			* Visualization
			* Written out algorithm and code.
		* The kinds of curves that can be produced.
		* Bezier chaining
				* Examples
				* Bezier chaining code.
		* Types of curves we want to create (ie good for gameplay)

* **Speaker 4: (10 min)**
	* How to integrate Perlin with Bezier
		* 2D mapping
		* Semi-random control points via Perlin Noise
		* Final curves
	* Perlin noise examples w/ code discussion
	* Bezier curve examples w/ code discussion
