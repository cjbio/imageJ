## Protocol to estimate percentage of GFP positive cells 
#### Open "imageJ -> Process -> batch -> Macro"
#### Select "input" and "output" files
#### Enter script below:
```
run("Invert");
setAutoThreshold("Default");
//run("Threshold...");
run("Analyze Particles...", "size=0.02-Infinity summarize");
```
#### Click on "Process" to run
