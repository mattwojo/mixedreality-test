---
description: Anything can be an Interactable object that triggers an event. It could be represented as a coffee cup on the table or a balloon floating in the air.  
title: Interactable object
author: randyw
---

# Interactable object

<link rel="stylesheet" href="https://az835927.vo.msecnd.net/sites/uwp/Resources/css/custom.css"> 
<link rel="stylesheet" href="https://az835927.vo.msecnd.net/sites/uwp/Resources/css/holographic.css"> 

A button has long been a metaphor used for triggering an event in the 2D abstract world. In the three-dimensional mixed reality world, we don’t have to be confined to this world of abstraction anymore. Anything can be an Interactable object that triggers an event. An interactable object can be represented as anything from a coffee cup on the table to a balloon floating in the air. We still do make use of traditional buttons in certain situation such as in dialog UI. The visual representation of the button depends on the context.

![Interactible object hero](../images/640px-InteractibleObject_Hero.jpg)

## What is a button?

In the two-dimensional world, a button control is commonly used to trigger an event or action. Typically, it's presented as a rectangular shape with different visuals for each interaction state such as idle, hover and pressed. To reinforce this affordance, buttons sometimes include additional visual cues such as shadow or bevel - this was typical in the early days of UI design. Buttons have gradually become flat and more abstract with modern design trends.

![Any type of object can now be a button.](../images/640px-InteractibleObject_CoffeeCup.jpg)

Any type of object can now be a button.

## Interactable object samples

**Mesh button**

![Mesh button](../images/640px-InteractibleObject_MeshButton.jpg)

These are examples using primitives and imported 3D meshes as Interactable objects. You can easily assign different scale, offset and color values to respond to each input interaction state.


**Holographic button**

![Holographic button](../images/640px-InteractibleObject_HolographicButton.jpg)

This is an example of a holographic button used in the Start menu and in [App bar and bounding box](Controls/App-bar-and-bounding-box.md). This example uses Unity's animation controller and animation clips.


**Toolbar**

![Toolbar](../images/640px-InteractibleObject_Toolbar.jpg)

A toolbar is a widely used pattern in mixed reality experiences. It is a simple collection of buttons with additional behaviors such as Billboarding and tag-along. This example uses a Billboarding and tag-along script from HoloToolkit. You can control detailed behaviors including distance, moving speed and threshold values.


**Traditional button**

![Traditional button](../images/640px-InteractibleObject_TraditionalButton.jpg)


**Other examples**

![Traditional button](../images/640px-InteractibleObject_PushButton.jpg)

![Real life object](../images/640px-InteractibleObject_RealLifeObject.jpg)

With HoloLens, you can leverage physical space. Imagine a holographic push button on a physical wall. Or how about a coffee cup on a real table? Using 3D models imported from modeling software, we can create an Interactable object that resembles real life object. Since it's a digital object, we can add magical interactions to it.


## Gallery of user projects

<table class="wdg-noborder">
	<tr class="wdg-noborder">
		<td class="wdg-noborder wdg-4-column-table"><a href="Get-started-with-design/index.md">![placeholder](../images/placeholder-square-150x150.png)<br/>
		User sample project 1</a></td>
		<td class="wdg-noborder wdg-4-column-table"><a href="Interaction-design/index.md">![placeholder](../images/placeholder-square-150x150.png)<br/>
		User sample project 2</a></td>
		<td class="wdg-noborder wdg-4-column-table"><a href="Style/index.md">![placeholder](../images/placeholder-square-150x150.png)<br/>
		User sample project 3</a></td>
		<td class="wdg-noborder wdg-4-column-table"><a href="App-patterns/index.md">![placeholder](../images/placeholder-square-150x150.png)<br/>
		User sample project 4</a></td>
	</tr>
</table>

## Related articles

Scripts and prefabs for Interactable object on Mixed Reality Design Labs GitHub

Object collection test

Billboarding and tag-along

