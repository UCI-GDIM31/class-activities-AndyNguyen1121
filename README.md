# in-class-activities-finished

## Devlogs

### W1

I learned how to upload games on itch.io that allows people to play immediately. I learned how hierarchies work and that the children always follows the parent's transform position. Components allow for values such as speed and rotation values to be edited individually.

### W2
1. The RGB values are floats because not all colors can be represented with integers. Color values can be decimals, which is why it must be a float.
2. _bounce is an int because the number of bounces can not be represented as a decimal. You can not have 1.5 bounces. The bounces have to be whole numbers.
3. The step 4 error has a missing semicolon at the end of the statement which prevented the game from running.
   
### W3
Table #14
The function's return type should be void. The function should have one parameter for the player's sanity level and use that to change the light brightness accordingly.

Components is a skinwalker and the skin suit is the classes. Member variables tell the skinwaker are its traits and the methods are what tells the suit what to do.

Because the balls' brightness is not capped, the balls will keep getting brighter and brighter.

### W4
Table #14
Line 17 declares the variable _isGrounded, setting its default value to false. Line 28 checks if the player is pressing the space bar and if the cat is grounded. If the line 28 condition is true, the _isGrounded boolean on line 32 is set to false because the cat is now jumping in the air.

For the collider activity, we added a rigidbody and collider to the cat and ball, and a trigger collider on the goal. 

Some issues that arised was that the ball was not passing through the goal collider, but bouncing off of it. To solve this we made the collider a trigger instead. For the cat to jump and the ball to bounce we needed to add rigidbodies.

### W5
Table #14 
When is using a Vector3 overkill?

Never. You use it when you need to and there's no way around it.

### W5
I worked on the Unity Coding section [link](https://docs.google.com/document/d/1lmiUEvktjmcBWJmVSkGWRt156K5VDO01tHGCc-V7qak/edit?tab=t.0)

Methods: Start(), Update()
Variables: bool isChasing, float speed, Transform playerLocation;

Start() is where the bat will start following the player.

### W6
The problem is step 2 is that it is using the world's forward direction instead of the local direction.

## Open-Source Assets

### W1

* Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727
* Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153
