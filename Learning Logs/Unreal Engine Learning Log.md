[[2022-05-12]]
---
- [HTF do I? Event Dispatchers in Unreal Engine 4](https://www.youtube.com/watch?v=sEcoWGrF1Hg)

[[2022-05-03]]
---
- [Unreal Engine - Sound and Music In 6 Minutes](https://www.youtube.com/watch?v=1GJRoUJvijw)

[[2022-04-28]]
---
- [Unreal how to apply damage to things](https://www.unrealengine.com/en-US/blog/damage-in-ue4) [[Matthew Booth]]

[[2022-04-11]]
---
- [Unreal vs. Unity: Actors & Components, Inheritance & Composition](https://www.youtube.com/watch?v=iQ3c-lrHO7o)
- [Alex Forsythe](https://www.youtube.com/channel/UCJf_2Ea75Wub1FHe6YjQ7Qw)
- [The Unreal Engine Game Framework: From int main() to BeginPlay](https://www.youtube.com/watch?v=IaU2Hue-ApI)
- [Blueprints vs. C++: How They Fit Together and Why You Should Use Both](https://www.youtube.com/watch?v=VMZftEVDuCE)

- [welcome to unreal course](https://learn.unrealengine.com/course/2436634/)
- [unreal for game dev course](https://learn.unrealengine.com/course/3751481)
- [make a game playlist](https://www.youtube.com/playlist?list=PL9z3tc0RL6Z4Yd0yqoELGiJLVIoDkpFD8)
- [Unreal Engine Learning Resources](https://learn.unrealengine.com/home/dashboard)
- [creating blueprints course](https://learn.unrealengine.com/course/2436619)

[[2022-03-16]]
---
- [Unreal Engine AI with Behavior Trees | Unreal Engine](https://www.youtube.com/watch?v=iY1jnFvHgbE)

[[2022-03-03]]
---
[unreal epic coding standards](https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/DevelopmentSetup/CodingStandard/)

[[2022-02-18]]
---
- [animating in unreal](https://youtu.be/IDNi0plxIXE)
	- vertex animation exists and is kind of neat
	- you can use it to animate folliage, birds flapping,
	- you can animate with particle effects

[[2022-02-17]]
---
[functions vs events in unreal](https://pixelsapiens.com/functions-vs-events-in-unreal-engine-4/)


[[2022-02-15]]
---
unreal edu
- texture streaming!
- you can stream textures at different sizes and different levels of detail
- you have a fixed streaming pool size to work within
	- you might get angry messages if its too full too fast
	- you can increase it through editing the config files
	- you can make them never stream ever if you really want to
	- interesting
		- ideal for text
- levels of detail can be split into groups, kinda a useful way to optimize
- merge actor tool exists
	- how the fuck do you get this to be 1 material i just what
	- you can make a huge mesh/material behemoth into a small material and small mesh behemoth
	- still a lot of traingles tho but still wild
	- fbx is the preferred 3d export ~thing~
	- ah the textures get bundled into an atlas
		- makes sense
		- very interesting practice, i wonder if it's automatable?
		- lmao this man made a potato
- hierarchical level of detail tool
- cascaded shadow maps
	- basically you can have close up shadows be dynamic and have far off ones be static
	- kind of wild actually
	- lights are so expensive lmao
	- distance fields - a thing for light falloff
- contact shadows exist
	- expensive tho because of course they are
	- mostly for cinematics ideally
- post processing exists
	- also expensive lmao lighting is just like this
- lightmass volumes
- lightmass importance volumes
	- like light probes in unity but different i think?
- basically itll pull samples from the volume and the different volume types have different densities and therefore more detailed lighting
- cull distance
	- the stop drawing button probably
	- delete tiny things
	- you've seen this in games all of the time
	- cull... by hand.... oh no
- reflections
- oh man reflections
	- spheres are cheap (interesting)
	- rectangles are expensive
	- just use... one large sphere reflector... in your whole level...
	-  oh my god
	-  of use a bunch of nested ones until you achieve the desired effect
	-  basically you can use localized reflectors to help with more detailed reflections
-  you have a reflector capture that does the capturing
-  boxes also exist
-  they are ok but use a sphere lmao
-  planar reflectors
	-  literally copy the materials lol
	-  works ok sometimes but can also be a nightmare depends on your project
	-  expensiiiivvvvveeee
	-  stunning HD reflections
-  reflection capture resolution can be changed/enhansed

[[2022-02-01]]
---
- [Mathew Wadstein Youtube Channel](https://www.youtube.com/c/MathewWadsteinTutorials)
- [Interactive Materials in Blueprint: Unreal Engine Tutorial](https://www.youtube.com/watch?v=I8lr9pdoSCY)
- [Tech Art Aid](https://www.youtube.com/channel/UCs2RyUGngZIZYdZaQ5p2mGg)
- [Unreal Engine 5: Changing an Object Color Dynamically](https://www.youtube.com/watch?v=wobCmfWT6w8)
- [Welcome To Unreal Engine](https://www.unrealengine.com/en-US/onlinelearning-courses/welcome-to-unreal-engine)
- [Making a VR Experience in Unreal Engine 4](https://www.pluralsight.com/courses/unreal-engine-4-making-vr-experience-2494)
- [welcome to unreal course](https://www.unrealengine.com/en-US/onlinelearning-courses/welcome-to-unreal-engine)
- [building better pipelines tutorial unreal](https://learn.unrealengine.com/course/2436634)
- [Unreal Engine Learning Resources](https://learn.unrealengine.com/home/dashboard)
- [blueprint examples](https://docs.unrealengine.com/4.27/en-US/Resources/ContentExamples/Blueprints/)
- [visual studio setup for unreal dev](https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/DevelopmentSetup/VisualStudioSetup/) 
- [triggering geometry sequences](https://docs.unrealengine.com/4.27/en-US/AnimatingObjects/Sequencer/HowTo/TriggeringSequences/) 
- [actor triggers](https://docs.unrealengine.com/4.27/en-US/Basics/Actors/Triggers/) 
- [Unreal Engine 4 - Blueprint Scripting a projectile/bullet](https://www.youtube.com/watch?v=OB6ns9E3dUU) 
- [implementing projectiles in an FPS](https://docs.unrealengine.com/4.27/en-US/ProgrammingAndScripting/ProgrammingWithCPP/CPPTutorials/FirstPersonShooter/3)
- [ingame viewport plugin](https://www.unrealengine.com/marketplace/en-US/product/second-in-game-viewport-window)
- [ingame viewport plugin but its open source](https://gitlab.com/UE4MarketplaceSubmission_Public/multiwindows4ue4_public#user-guide-of-multiwindows4ue4-plugin)