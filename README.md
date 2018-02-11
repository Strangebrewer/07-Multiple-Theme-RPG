# Multiple-Theme-RPG

This is the second jQuery project for my coding bootcamp. The project was actually to create one RPG with a prescribed mechanic, but I noticed along the way that if I were to use generic class, id, and variable names, I could add as many more themes (or skins) as I want. So, after getting the original game working, I started adding themes.

The majority of the js code comes from either defining objects for the various themes, or in manipulating the DOM to achieve the look I wanted. The code for the actual game mechanic is minimal by comparison.

When you click a theme button, the game will load with the corresponding images. Then, you choose your character, and the rest of the vatars become defenders. You fight the defenders one-by-one in the order of your choosing until you or all of them reach 0 health.

All of the functionality works as intended but there is one occasional glitch I haven't been able to prevent, and that is that sometimes the attack button doesn't fade in when you choose your first defender. At this point, I'm wondering if it's because I don't yet know how to write more efficient and compact js code, or if it has more to do with the timing of the fade outs and fade ins with the setTimeouts.

(to be continued)
