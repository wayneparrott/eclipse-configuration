## CodeMix & DevStyle Preferences
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

`codemix-essentials-plugins.p2f` - import to load the [CodeMix](https://marketplace.eclipse.org/content/codemix) & [DevStyle](https://marketplace.eclipse.org/content/darkest-dark-theme-devstyle) plugins

`codemix-essentials-prefs.eps` - import for CodeMix prefs, e.g., custom syntax coloring & editor 

## Installation
When setting up a new Eclipse instance do the following:
1. Import codemix-essentials-plugins.p2f - loads CodeMix & DevStyle plugins from marketplace
2. Import codemix-essentials-prefs.eps - setup the syntax coloring theme & editors associated with the CodeMix editor
3. Configure workbench layout, choose 
   Window menu > Perspective > Customize > Other > "CodeMix-Custom"
4. Optional - install ShowInExplorer plugin
   Copy & paste com.genuitec.devstyle.showinsystemexplorer_xxx.jar into your Eclipse dropins foloder
5. Restart Eclipse 

## New Workspace Configuration
When you start a new workspace do the following: 
1. Import codemix-essentials-prefs.eps - setup the syntax coloring theme & editors associated with the CodeMix editor
2. Configure workbench layout, choose 
   Window menu > Perspective > Customize > Other > "CodeMix-Custom"

## Screenshot
![](https://content.screencast.com/users/wparrott/folders/Snagit/media/a577ff03-ef9f-4f37-bf66-7a489eb2cc05/2018-04-23_13-13-03.png) 
![](https://https://github.com/wayneparrott/eclipse-configuration/docs/codemix-perspective.png) 
