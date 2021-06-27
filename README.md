# Test Screen

When I was a kid, I often viewed the test screen on our TV and wondered if I could recreate it. Now, 40 years later, I did it. And I plan to expand it with lots more functions.

# Process
This test screen is based on the Dutch Ziggo test screen which is transmitted on a channel to test the colors of your set. I took a photograph and used it as a basis for a design build in Figma. When done, I decided this test screen should also be coded. I choose to build it in vanilla CSS, to learn about its variables and calculations functions. I use these on a mid-regular base in Sass, but wanted to use a non-compiler language. To challenge myself. To learn.

# Variable sizes
I initially just winged the size, but soon decided that the squares should be 150px... and their white-space should be 10px. Its just easier to calculate things. In hindsight a good decision, because all squares are related to eachother and their white space, which you will find out of you check the code.

Not soon after the 10px white-space was created, I decided that its better to use margins of 5px, on all sides of the squares and rectangles. This way it became a lot easier to build the HTML structure. Later it also became easier to calculate the different sizes.

> You can in-/decreasing the size of the test screen, by changing the '--devided' var. If you enter the number 1, all squares will be 150px, resulting in a huge screen. Use the number 2, the size of the test screen will be recalculated and present squures of 75px, with all other spacing, margins, images* etcetera being recalculated to their respective sizes.

\* Images are set to 'contain' their divs, so will scale automatically. I've yet to devise a plan on how to create them in a non-image format. To be continued.

# Future plans (to be decided)
- Adding a slider/form that changed the size of the --devided var.
- Changing test screen based on viewport. Probably with vw and vh.
- Creating more formats and/or other test screens
- Creating funny test screens, like a smiley, etc.
- Creating monochrome or other weird test screens.
- And lots more.

# Copyright
Since I do not own the original rights to this test screen, I have chosen for an MIT License. Feel free to use it, but please reference me as the original code creator. The design is not mine, the code is.
