# Notes from Transitions and Animations
 - For a transition to take place, an element must have a change in state, and different styles must be identified for each state. 
 - The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target psuedo-classes.
 - The *transition-property* property determines exactly waht properties will be altered in conjunction with the other transitional properties. 
 - Not all properties may be transitioned, only properties that have an identifiable halfway point.
 - The *transition-timing-function* property is used to set the speed in which a transition will move. 
 - The keyframes for animations are @keyframes which includes the animation name, any breakpoints, and the properties intended to be animated.
 - By default, animations run their cycle once from beginning to end. To have an animation repeat itsel, use the *animation-count* property to include an integer or the *infinite* keyword. 
 