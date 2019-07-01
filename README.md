
# Data Applications with Panel 

**Objectives**
1. Discuss use cases of interactive vs static visualizations
2. Illustrate use of interactive, reactive, and parametrized functions
3. Extend knowledge to new dataset, including a ML model

## Panel 

Panel can be used to make a first pass at an app or dashboard in minutes, while also allowing you to fully customize the app's behavior and appearance or flexibly integrate GUI support into long-term, large-scale software projects. To make all these different ways of using Panel possible, four different APIs are available:

**Interact functions:** Auto-generates a full UI (including widgets) given a function

**Reactive functions:** Linking functions or methods to widgets using the pn.depends decorator, declaring that the function should be re-run when those widget values change

**Parameterized class:** Declare parameters and their ranges in Parameterized classes, then get GUIs (and value checking!) for free

**Callbacks:** Generate a UI by manually declaring callbacks that update panels or panes


Code found in notebook