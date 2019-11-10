# Flowcharts # {#flowcharts}
[TOC]

A fundamental concept of %Fungus is the **Flowchart**. Scenes can contain a single Flowchart or multiple Flowcharts.

<!-- **************************************************** -->
# What is a Flowchart? # {#flowchart}

A %Fungus **Flowchart** contains the Blocks in which all your %Fungus Commands are located. A Unity scene can contain multiple Flowcharts, and commands can be executing simultaneously in different Flowcharts. However, for many games it is sufficient for one Block in one Flowcart to be executing at any one time.

Here is an example of a %Fungus Flowchart:

![flowchart example]

<!-- **************************************************** -->
# The Flowchart window # {#flowcharts_flowchart_window}
You'll need the %Fungus Flowchart window when working with %Fungus. Open and dock this window somewhere handy by following these steps:

1. Choose menu: ``Tools | %Fungus | Flowchart Window``

![Menu open %Fungus window]

2. Drag-and-drop the Flowchart window to the location you wish to dock it:

![Drag %Fungus window]

3. The Flowchart window is now docked and part of your Unity window layout:

![Docked %Fungus window]

<!-- **************************************************** -->
# Creating a Flowchart # {#creating_flowchart}
To create a %Fungus Flowchart do the following:

1. Choose menu: ```Tools | %Fungus | Create Flowchart```

![menu create Flowchart]

2. A new **Flowchart** gameObject should appear in the Hierarchy window.

![new Flowchart gameobject]

3. Select the **Flowchart** gameObject in the Hierarchy window, and you'll see the **Flowchart's** properties in the Inspector Window:

![Flowchart properties]

4. If you have not already displayed the Flowchart Window, you can do so by clicking the Flowchart Window button in the Inspector.

5. As you can see, when a new Flowchat is created a single command Block named "New Block" is automatically created, with the Event handler "Game Started" (so it will start executing %Fungus commands as soon as the scene goes into **Play Mode**).

<!-- **************************************************** -->
# Panning the Flowchart # {#panning}
Panning means moving the contents of the Flowchart window as if they are on a piece of paper. Click and drag with the RIGHT mouse button to pan the contents of the Flowchart window.

![pan flowchart 1]

![pan flowchart 2]

![pan flowchart animated]

<!-- **************************************************** -->
# Zooming the Flowchart # {#zooming}
Zooming refers to making the contents larger or smaller. To zoom the Flowchart window contents either click and drag the UI slider, or use the mouse wheel (or trackpad).

![zoom flowchart 1]

![zoom flowchart 2]

![zoom flowchart 2]

[flowchart example]: ./flowcharts/001_what_is/1_example_flowchart.png "flowchart example"
[Menu open %Fungus window]: ./flowcharts/002_docking/1_menu.png "Menu open %Fungus window"
[Drag %Fungus window]: ./flowcharts/002_docking/2_window.png "Drag %Fungus window"
[Docked %Fungus window]: ./flowcharts/002_docking/3_docked.png "Docked %Fungus window"
[menu create Flowchart]: ./flowcharts/005_create_flowchart/1_tools_create.png "menu create Flowchart"
[new Flowchart gameobject]: ./flowcharts/005_create_flowchart/2_flowchart_gameobject.png "new Flowchart gameobject"
[Flowchart properties]: ./flowcharts/005_create_flowchart/3_flowchart_properties.png "Flowchart properties"
[pan flowchart 1]: ./flowcharts/003_panning/1_pan1.png "pan flowchart 1"
[pan flowchart 2]: ./flowcharts/003_panning/2_pan2.png "pan flowchart 2"
[pan flowchart animated]: ./flowcharts/003_panning/animated_drag_to_pan.gif "pan flowchart animated"
[zoom flowchart 1]: ./flowcharts/004_zooming/1_zoom1.png "zoom flowchart 1"
[zoom flowchart 2]: ./flowcharts/004_zooming/2_zoom2.png "zoom flowchart 2"
[zoom flowchart 2]: ./flowcharts/004_zooming/animated_zoom.gif "zoom flowchart animated"
