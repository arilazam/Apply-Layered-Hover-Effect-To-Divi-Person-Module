# Apply-Layered-Hover-Effect-To-Divi-Person-Module
I will show how to implement a nice layered hover effect for Divi Person Module.

To implement this effect we’ll assign the layered-effect CSS class to the Person Module and use the CSS snippet provided below. No any special settings need to be applied in the Person Module Settings, all you need is to make sure you don’t add too much text to the module, otherwise it will be cut because we will apply the overflow: hidden rule to the module container (the content should not occupy more space than the image). If your text is too long and you cannot shorten it, try to experiment with font size and line height until you achieve your desired result.

Step 1: Add the *layered-effect* CSS class to Person Module Settings -> Advanced -> CSS Class field.

Step 2: We will use the Person module container and its description container :before and :after pseudo elements as “layers”. You can change their background colors on the highlighted lines of the code below.

Person Module Layered Hover Effect.css

Copy the CSS snippet above and add it into the Divi -> Theme Options -> General -> Custom CSS field.

Alternatively, you can add this code into your child theme style.css file.

Save everything and enjoy the effect.
