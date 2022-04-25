# Start Location
The game starts with Rosella on the beach screen on the top row of the main section (in the middle)

# Screen Transitions
By default, if Rosella hits the edge of the screen she will transition to the next screen in that direction if there are white lines connecting the screens, and she will retain her X and Y position on the new screen. Note that there is an invisible "horizon" partway up the screen that will trigger an upward transition.

The main section is 5 screens tall, and will wrap around if you continue up or down.

# Special Screen Transitions
Special loading zones are indicated with colored bars. Each bar corresponds with a bar of the same color on an adjacent screen. By default, when Rosella hits one of these bars, she'll appear on the point on the corresponding bar closest to her current X-Y position.

A black dot in a bar indicates that Rosella will be warped to that dot if she hits anywhere on the corresponding bar on the adjacent screen, regardless of where she hits it.

Some transitions are only one way. These are indicated by a black dot inside a larger colored dot. 
