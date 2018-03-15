---
layout: LandingPage
title:  Windows Mixed Reality Layout Tests
description: A place to test docs platform layouts for the Mixed Reality docs.
keywords: mixed reality developer docs 
---

# Design guidance overview

This guidance is authored by Microsoft designers, developers, program managers, and researchers, whose work spans holographic devices (like HoloLens) and immersive devices (like the Acer and HP Windows Mixed Reality headsets). So, consider this work as a set of topics for ‘how to design for Windows head-mounted displays’.

## Markdown

>[!IMPORTANT]
>one

>two

Extra space

>  [!NOTE]
> here's note

## Markdig 

> [!IMPORTANT]
> one
> 
> two

> [!NOTE]
> here's note

* Does a Bullet list have spacing
* between each bullet
* even if there is no line break

1. But a numbered list
2. does not have spacing between lines
3. with no line break?

# Get apps for HoloLens

As a Windows 10 device, HoloLens supports many existing UWP applications from the app store, as well as new apps built specifically for HoloLens. On top of these, you may even want to [develop](development-overview.md) and install your own apps or those of your friends!


### Installing an application package with the Device Portal
1. Establish a connection from [Device Portal](using-the-windows-device-portal.md) to the target HoloLens.
2. Navigate to the **Apps** page in the left navigation.
3. Under **App Package** Browse to the .appx file associated with your application.
  >[!IMPORTANT]
  >Make sure to reference any associated dependency and certificate files.

4. Click **Go**.

![Install app form in Windows Device Portal on Microsoft HoloLens](images/deviceportal-appmanager.jpg)<br>
Using Windows Device Portal to install an app on HoloLens

### Deploying from Microsoft Visual Studio 2015
1. Open your app's Visual Studio solution (.sln file).
2. Open the project's **Properties** .
3. Select the following build configuration: Master/x86/Remote Machine.
4. When you select Remote Machine:
   * Make sure the address points to the HoloLens' WiFi IP address.
   * Set authentication to Universal (Unencrypted Protocol).
5. Build your solution.
6. Click the **Remote Machine** button to deploy the app from your development PC to your HoloLens. If you already have an existing build on the HoloLens, select yes to re-install this newer version.<br>
  ![Remote Machine deployment for apps to Microsoft HoloLens in Visual Studio](images/vs2015-remotedeployment.jpg)<br>
7. The application will install and auto launch on your HoloLens.

-  a
   * b
 
1. a
   1. b
## Article categories

:::row:::
    :::column:::
        ![Get started icon](Design/images/icon_GetStarted.png)
        ### Get started with Design
        [What is mixed reality?](Design/Get-started-with-design/What-is-mixed-reality.md)
    :::column-end:::
    :::column:::
        ![Some image](http://via.placeholder.com/1000x150)
        ### Hello, title
        This is where your content goes.
    :::column-end:::
    :::column:::
        ![Some image](http://via.placeholder.com/1000x150)
        ### Hello, title
        This is where your content goes.
    :::column-end:::
:::row-end:::


<ul class="panelContent cardsF">
    <li>
        <div class="cardSize">
            <div class="cardPadding">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="icon_GetStarted.png" alt="Get started icon"/>
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Get started with Design</h3>
                        <p>
                            <a href="Design/Get-started-with-design/What-is-mixed-reality.md">What is mixed reality?</a>
                        </p>
                        <p>
                            <a href="Design/Get-started-with-design/My-first-year-on-the-design-team.md">About this guidance</a>
                        </p>
                        <p>
                            <a href="Design/Get-started-with-design/The-pursuit-of-more-personal-computing.md">The pursuit of more personal computing</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </li>
    <li>
        <div class="cardSize">
            <div class="cardPadding">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="icon_Interaction.png" alt="Interaction design icon" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Interaction design</h3>
                        <p>
                            <a href="Design/Interaction-design/Interaction-fundamentals.md">Interaction fundamentals</a>
                        </p>
                        <p>
                            <a href="Design/Interaction-design/Comfort.md">Comfort</a>
                        </p>
                        <p>
                            <a href="Design/Interaction-design/Gaze-targeting.md">Gaze targeting</a>
                        </p>
                        <p>
                            <a href="Design/Interaction-design/Gestures.md">Gestures</a>
                        </p>
                         <p>
                            <a href="Design/Interaction-design/Voice-design.md">Voice design</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </li>
    <li>
        <div class="cardSize">
            <div class="cardPadding">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="icon_Style.png" alt="Style icon" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Style</h3>
                        <p>
                            <a href="design/basics/design-and-ui-intro.md">Color, light and materials</a>
                        </p>
                         <p>
                            <a href="design/fluent-design-system/index.md">Spatial sound design</a>
                        </p>
                        <p>
                            <a href="design/controls-and-patterns/index.md">Typography</a>
                        </p>
                        <p>
                            <a href="design/downloads/index.md">Scale</a>
                        </p>                      
                    </div>
                </div>
            </div>
        </div>
    </li>
    <li>
        <div class="cardSize">
            <div class="cardPadding">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="icon_AppPatterns.png" alt="App patterns icon" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>App patterns</h3>
                        <p>
                            <a href="enterprise/index.md">Types of mixed reality apps</a>
                        </p>
                        <p>
                            <a href="packaging/index.md">Room scan visualization</a>
                        </p>
                        <p>
                            <a href="porting/index.md">Cursors</a>
                        </p>
                        <p>
                            <a href="winrt-components/index.md">Billboarding and tag-along</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </li>
    <li>
        <div class="cardSize">
            <div class="cardPadding">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="icon_Controls.png" alt="Controls icon" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Controls</h3>
                        <p>
                            <a href="gaming/e2e.md">Text in Unity</a>
                        </p>
                        <p>
                            <a href="gaming/index.md">Interactable object</a>
                        </p>
                        <p>
                            <a href="gaming/directx-programming.md">Object collection</a>
                        </p>
                        <p>
                            <a href="xbox-apps/index.md">Progress</a>
                        </p>
                        <p>
                            <a href="xbox-live/index.md">App bar and bounding box</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </li>    
</ul>

## Resources

<table style="border-collapse:collapse">

	<tr>
		<td style="border-style: none" width="50%"><img src="CommonControlGallery-test.png" width="100%" alt="Common Control Gallery"><br/>**[Common controls gallery](../layout/index.md)**<br/>What do common controls look like in Mixed Reality? How do they act? Check it out right here, or send them to the headset of your choice.</td>
		<td style="border-style: none"><img src="SampleApps-test.png" width="100%" alt="Sample apps"><br/>**[Sample apps](design/sample-apps/Sample-apps.md)**<br/>Explore and experiment with sample app experiences created for developers by the Windows Mixed Reality team. These apps showcase our approach to designing great experiences and highlight the opportunities in UI, interaction, and integrated services.</td>
	</tr>
       
</table>

## Design tools

<ul class="panelContent cardsF">
    <li>
        <div class="cardSize">
            <div class="cardPadding">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="icon_AppPatterns.png" alt="Get started icon"/>
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Get started with Design</h3>
                        <p>
                            <a href="whats-new/windows-10-build-16299.md">HoloSketch</a>
                        </p>
                        <p>
                            <a href="whats-new/windows-docs-latest.md">Inclusive design at Microsoft</a>
                        </p>
                        <p>
                            <a href="whats-new/experimental-apis.md">Fluent Design System</a>
                        </p>
			 <p>
                            <a href="whats-new/experimental-apis.md">UWP app design and UI</a>
                        </p>
			 <p>
                            <a href="whats-new/experimental-apis.md">3D design tools from Simplygon</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </li>
        <li>
        <div class="cardSize">
            <div class="cardPadding">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="icon_GetStarted.png" alt="Get started icon"/>
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Mixed Reality Toolkit (on GitHub)</h3>
                        <p>
                            <a href="whats-new/windows-10-build-16299.md">Sharing</a>
                        </p>
                        <p>
                            <a href="whats-new/windows-docs-latest.md">Spatial input</a>
                        </p>
                        <p>
                            <a href="whats-new/experimental-apis.md">UnityEditorMotionControllerModel</a>
                        </p>
			 <p>
                            <a href="whats-new/experimental-apis.md">Readme.md</a>
                        </p>
			 <p>
                            <a href="whats-new/experimental-apis.md">Microphone Stream Selector</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </li>
