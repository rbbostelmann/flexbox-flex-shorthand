# flexbox-flex-shorthand

Playing and testing the implicitt flex properties:

    flex-grow;
    flex-shrink;
    flex-basis;

Default value for the flex property:

flex: 0 1 0%;

Sometimes helpful to set flex-basis: auto;

*** Using auto as a flex-basis tells the item to check for a width declaration (width: 250px). 
***

TOP:

In practice you will likely not be using complex values for flex-grow, flex-shrink or flex-basis. Generally, you’re most likely to use declarations like flex: 1; to make divs grow evenly and flex-shrink: 0 to keep certain divs from shrinking.

It is possible to get fancy, and set up layouts where some columns relate to each other in a specific ratio, so it’s useful to know that you can use other values, but those are relatively rare.