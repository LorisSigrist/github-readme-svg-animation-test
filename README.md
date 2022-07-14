Just a quick test to see if Github would display SMIL svg animations.

![Animated SVG](animation.svg)

Turns out, the answeri is yes! But, you must have the svg in a seperate file. You cant just inline the svg code, as it will not render. 

Put your animated svg into a seperate file and import it using
```markdown
![alttext](relative/path/from/readme/to/animation/)
```