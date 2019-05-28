
<img src="images/black_SP_logo@3x.png" width=400>

# SpectatAR Integration Guide - https://www.spectatar.co

The future of spectating your favorite Triple A titles is here! SpectatAR is an augmented reality broadcasting platform that redefines that way spectators view and interact with games. Traditional, 2D broadcasting doesn't capture the magic of games - SpectatAR allows you to treat fans to an unrivaled viewing experience by giving them full interactive control over their viewing experience. SpectatAR provides simple game integration for private, professional and esport titles to be broadcasted and/or viewed in Augmented Reality. 

## Engine Support

- Unreal Engine 4.22.1 (Source Control Build) – https://github.com/EpicGames
- Unity 2019.3.0a2 – https://unity.com
- SceneKit 5.0 – https://developer.apple.com/scenekit/
- Proprietary/Privately owned engines

## How it works
SpectatAR is the first solution that enables game developers to broadcast their games in augmented reality. The SpectatAR platform is a Broadcasting/Viewership tool that uses Augmented Reality to give an in-depth and fully customizable experience to the game spectating enthusiast as well as to professional broadcasters/producers. Gone are the days where viewers are locked into player cameras. SpectatAR gives viewers full control and exploration of the map to get right in the action. For esports broadcasters, game developers, and publishers, the SpectatAR livestreaming platform lets you produce groundbreaking high-fidelity 3D spectating experiences from any perspective.

## Platform Overview

The SpectatAR solution allows developers to easily integrate their games into an augmented reality viewership platform, hosted by SpectatAR on Amazon's game tech cloud infrastructure. Depending on your game engine, SpectatAR provides an easy-to-use plugin to automatically capture game content and create a AR broadcast. We also offer customized integrations for proprietary engines. 

## Unreal Engine 4.22.1 - Plugin UI in the Editor

Due to the unique nature of Unreal Engine 4.22.1 and the use of Blueprints along with Visual Scripting, integration requires a Plugin to be installed.

- Navigate to the main development environment
- Click Settings in the Header Bar
- Click on Plugins
- Using the search bar at the top right, type SpectatAR
- Select the SpectatAR Plugin
- Tap Install
- Restart UE4
- Full access is now granted in the World Outliner as well as the Content Browser. 

##  Unity 2019.3.0a2

Due to the unique nature of Unity 2019.3.0a2 and the use of Prefabs for scene building, integration requires a Plugin to be installed.

- Navigate to the main development environment
- Select the Assets tab in the top Browser tool bar
- Select Import Package
- Navigate to the SpectatAR .unity file and import
- Restart Unity
- Full access is now granted in the Assets Hierarchy


## SceneKit 5.0

Installation into Xcode is available via CocoaPods. For CocoaPods documentation and installation into the terminal, visit https://cocoapods.org

**Sudo**

- $ sudo gem install CocoaPods

**Sudo-less installation**

If you do not want to grant RubyGems admin privileges for this process, you can tell RubyGems to install into your user directory by passing either the --user-install flag to gem install or by configuring the RubyGems environment. The latter is, in our opinion, the best solution. To do this open up terminal and create or edit your .bash_profile with your preferred editor. Then enter these lines into the file:

- export GEM_HOME=$HOME/.gem
- export PATH=$GEM_HOME/bin:$PATH
- Navigate to the Terminal
- CD into the main project’s directory
- Run pod init
- Run ls
- Run vi PodFile
> - Insert pod ‘SpectatAR’
- Run the installation
- Close the current Xcode project
- Open up the newly created XCWorkspace
- Full access is now granted in the Assets Hierarchy

## Proprietary/Privately owned engines – For in depth personalized assistance, please visit https://www.spectatar.co

For Proprietary/Privately owned engines, there are two options for easy integration due to the unique nature of exclusive engines. 

**Option 1:** 

- For hands free installation:

SpectatAR can easily host your game with full access to the Games Models (Assets, Textures and Meshes), Animations and Particles systems. Along with the assets, an endpoint with access to Telemetry data is needed. Telemetry data should be in JavaScript Object Notation (JSON) and include all pertinent player and game data. This is easily achievable by giving SpectatAR access to the builds Repository. 

**Option 2:** 

- For manual installation: 

The Game Engine and supplementary literature will be needed to better understand the engines structure and game implementation. Along with the Game/Scene Levels and all models as a .zip/.rar extension. Lastly, an API with all player data endpoints with supplementary documentation. 

**An in-depth response to the following questions to be emailed to info@spectatar.co**

- Company/Game name along with all relevant information
- Engine platform being used (General Overview)
- Is it publicly available? If not, are we able to get access and permissions?
- What are the main coding languages used for game logic? (C++ and C#)
- What format are the assets? (fbx, dae)
- What format or how are the VFX’s built? (Blueprints, Prefabs, Custom Particle/Shader systems)
- What platform are the Multiplayer servers hosted on? (AWS, Proprietary) 
- How many maps are currently played on?
- What scale are the maps in? (World to Meters)
- What Frames per Second do the games run in? (30fps, 60 fps, somewhere in between?)
- How many Monthly Active users on average?

**Thank you and we look forward to collaborating with you.**

## Our Team - https://www.spectatar.co/team

<img src="images/Brantley.png" width=100>

**Brantley Pace Co-founder / CEO**

<img src="images/Beau.png" width=100>

**Beau Bergman Co-founder / COO**

<img src="images/JJ.png" width=100>

**JJ McMillen Co-founder / Design**

<img src="images/Charlie.png" width=100>

**Charlie Arcodia Co-founder / CTO**

## Visit us: @spectatar

- Facebook: https://www.facebook.com/Spectatar-2249518738654092/
- Twitter: https://twitter.com/spectatar
- LinkedIn: https://www.linkedin.com/company/spectatar/about/




**For all questions and/or to setup a game integration interview, please visit https://www.spectatar.co and click on info@spectatar.co**



			       



 









			       





 



