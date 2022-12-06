# Workflow of Project 3      

**Output** - 

![webpage](output.png)

## Approach that i followed was - 
1. First i target the nav section where i align all the elements using `display:flex` and then i set the `height` and the `padding` of navbar and then after it i style logo, list and button.
2. Now I target the container below the navbar where i used  `display`,`position` property and some `margin`,  `padding`, `height` properties to set the heading, paragraph and button.
3. The Problem i faced was in to set the star image and the problem was that both star image was in `span` tag separately and both the `span` tag have same class name and i was wanting according to the output that one star should be on right top corner and another star should be on left bottom corner. so then tried a lot and finally i set those image with the help of `sibling selector`. That time i realise that how basics will help us.