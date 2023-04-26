# responsive-sizes-mixin

This Mixin allows you to make responsive sizes and spacings for any object on your webpage.
It doesn't depend on etheir you're tryin' to make responsive fonts, margins, paddings, width, height, coordinates, etc.
You can define the "$type" variable (for example, "margin-top", "font-size" or "left"), define specify the measurement system(px, rem, em ...) and values.
Please, draw your attention that firstly you should define "old values" (values for max-width (for my screen => 1920px)) and "new values" (in this example => 320px).
Also, don't forget to create "$maxTempWidth" variable and define it as Max-Width of the template of your webpage.

This mixin can accept several "old" and "new values" if you need it. For example, it can be useful for "panding" or "margin" when you specify several values for each side.

ENJOY!
