## Best Eclipse Setup for non-Java Development
My typical Eclipse IDE setup has evolved over the years to a simple clean 
layout with influences from JetBrains and Visual Studio Code tools. 
For example, I prefer to do the majority of my work within a single 
common Eclipse perspective including debug activities. The experience is 
more similar to tools like Android Studio. From VS Code I like the dark theme, 
cleaner search dialog, command palette and terminal integration. From Eclipse 
I still rely heavily on the Java & XML tools and occasionally GIT tools. Almost 
all other programming tasks use the CodeMix editors for a VS Code editing 
experience.

## Files

`eclipse-dev-plugins-min.p2f` - import to load the following plugins
- Eclipse Marketplace plugin
- Git Tools plugin
- [DevStyle](https://marketplace.eclipse.org/content/darkest-dark-theme-devstyle) UX plugin
- [CodeMix](https://marketplace.eclipse.org/content/codemix) editor & coding tools plugin

`eclipse-dev-prefs-min.eps` - import as preferences to set 
 - dark theme (darkest dark theme)
 - custom syntax coloring & editors
 - custom perspective that layouts out coding, debug & git tools 
 in a common perspective (minimize context switching)

## Installation
When setting up a new Eclipse instance do the following:
1. Import plugins file:  eclipse-dev-plugins-min.p2f - loads CodeMix & DevStyle plugins from marketplace  
   File menu > Import > Install > Install Software Items from File > "eclipse-dev-plugins-min.p2f"

2. Import colors and perspective (window layout) file: eclipse-dev-prefs-min.eps - setup the syntax coloring theme & editors associated with the CodeMix editor   
   File menu > Import > General > Preferences > "codemix-essentials-prefs.eps"

3. Configure workbench layout, choose   
   Window menu > Perspective > Customize > Other > "CodeMix-Custom"

4. Optional - install ShowInSystemExplorer plugin   
   Copy dropins/com.genuitec.devstyle.showinsystemexplorer_xxx.jar into your Eclipse dropins foloder

5. Restart Eclipse 

## New Workspace Configuration
When starting a new workspace do the following: 
1. Import colors and perspective (window layout) file: codemix-essentials-prefs.eps - setup the syntax coloring theme & editors associated with the CodeMix editor   
   File menu > Import > General > Preferences > "eclipse-dev-prefs-min.eps"

2. Configure workbench layout, choose   
   Window menu > Perspective > Customize > Other > "CodeMix-Custom"

## Screenshot 
![](https://raw.githubusercontent.com/wayneparrott/eclipse-configuration/master/docs/codemix-perspective.png) 
