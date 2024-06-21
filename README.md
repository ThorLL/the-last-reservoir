# The Last Reservoir
The Last Reservoir is a first-person, narrative-driven game set in a dystopian world, drawing players into a captivating experience of ethical dilemmas and societal divides. Inspired by old sci-fi aesthetics, it challenges players to navigate a society on the brink, making choices that explore themes of resource scarcity and inequality. Our vision is to offer a gameplay experience that not only entertains but also provokes thought and reflection on contemporary issues, delivering a unique perspective on the impact of technology and power dynamics in a speculative future.

The game is set in a time of technological advancement and environmental degradation, where steam power is the pinnacle of innovation but comes at the cost of the world's most precious resource: water. The player embodies Sam; an undercover rebel disguised as a technician, who’s determined to challenge the status quo of Vapour City's impact on divided society. Guided initially by instructions through an earpiece from a fellow rebel, the player must navigate and sabotage a facility crucial to delivering power to Vapour City and uncover its ruthless ways of doing so.

We offer an immersive narrative experience that intertwines gameplay with
thought-provoking themes, presenting a unique speculative universe as a backdrop to
explore real-world issues. Bringing this game to life, we wish to contribute to a meaningful conversation on the future we envision and the paths we choose, encouraging players to consider their impact on the world and the ethical dimensions of their choices.
# The team - The Tunnel Rats
Game Design Lead, Sound Designer & Narrative Designer Fríði Paulason Hentze

Co-Producer, Level Designer & Narrative Designer Mathias Kladov

Co-Producer & Narrative Designer: Magnus Holm Koch [<img src="https://skillicons.dev/icons?i=github" alt="GitHub Icon" style="vertical-align: middle; height: 1em;">](https://github.com/maghoko)

Level Designer & Narrative Designer: Peter Blomsgård Hansen

Tech lead & Programmer: Gustav Sølvsteen Olesen [<img src="https://skillicons.dev/icons?i=github" alt="GitHub Icon" style="vertical-align: middle; height: 1em;">](https://github.com/GustavSO)

Programmer: Kleanthis Michael Diakogiannis

Programmer & Tooling: Thor Lyster Lind [<img src="https://skillicons.dev/icons?i=github" alt="GitHub Icon" style="vertical-align: middle; height: 1em;">](https://github.com/ThorLL)

# Setup Guide
This guide has only been tested on Windows!
## Prerequisites
- [Git LFS](https://git-lfs.com/)
- [Visual Studio installer](https://visualstudio.microsoft.com/downloads/)
- [Unreal 5.3.2](https://www.unrealengine.com/en-US/download)
    - [Substance-plugin](https://www.unrealengine.com/marketplace/en-US/product/substance-plugin)

## Guide
1. Set Up Visual Studio: In the installer:
	1. Under **Workloads** select
		1. .NET desktop development
		2. Desktop development in C++
		3. Game development with C++
		4. Windows applications development 
	2. In the **Installation details** panel put a check in:
		1. Universal Windows Platform tools
		2. C++ (v143) Universal Windows Platform tools
	3. Under Individual components select
		1. .NET Framework 4.6.2 targeting pack
		2. MSVC v143 - VS 2022 C++ x64/x86 build tools (V14.36-17.6)
   4. Click Install
2. Pull the Repo
3. Install FMOD for Unreal 5.3
   1. Download the version specific to your system [here](https://www.fmod.com/download#fmodengine)
   2. Extract the contents
   3. Copy the contents into the [./Plugins](https://github.com/ThorLL/The-Last-Reservoir/tree/main/Plugins) folder
4. Open the project in UE 5.3.2
5. You should get the following prompt  
	```text
	The following modules are missing or built with a different engine version:
	  TheLastReservoir
	Would you like to rebuild them now?
	```
	The prompt should ONLY mention TheLastReservoir nothing else!

	Click **yes**
6. If everything went well the project should be open in just a bit

# Assets
1. 80s Brutalist Office by Enrab Arts. [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/80s-brutalist-office)
2. Apartment Tech Props by Dekogon Studios. [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/31797bf6fa0545d590e3bb17d0968dea)
3. City Subway Train Modular by Dekogon Studios. [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/city-subway-train-modular)
4. Soul: City by Epic Games. [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/soul-city)
5. Factory Environment Collection by Denys Rutkovskyi. [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/factory-environment-collection)
6. Buildings VOL.8 - Commercial Doors (Nanite & Low Poly) by Dekogon Studios. [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/buildings-vol-8-commercial-doors-nanite-low-poly?sessionInvalidated=true)
7. Ultra Dynamic Sky by Everett Gunther. [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/ultra-dynamic-sky)
8. Warhammer 40k Imperial Hive City by taumich. [Sketchfab](https://sketchfab.com/3d-models/warhammer-40k-imperial-hive-city-77b6e7a31509497a9753f6a93d30f63f)
9. ChatGPT (2022) OpenAI
10. Scientist skibidi multiverse [Sketchfab](https://skfb.ly/oSwK7)
11. ZOMBIE CORPSE [Sketchfab](https://skfb.ly/opsHn)
12. Ceiling Speaker [Sketchfab](https://skfb.ly/ouYFN)
13. SFX sounds [getsoundly](https://getsoundly.com/assets/Soundly-EULA.pdf)
14. SFX sounds [getsoundly](https://getsoundly.com/faq/how-can-i-use-the-sounds/)
15. Font, jmh-typewriter [dafont](https://www.dafont.com/jmh-typewriter.font)
16. Font, Amstrad PC, [int10h](https://int10h.org/oldschool-pc-fonts/fontlist/font?amstrad_pc)
17. Relaxing Soft Warm Jazz Piano Bossa Nova Podcast Music [pixabay](https://pixabay.com/music/smooth-jazz-relaxing-soft-warm-jazz-piano-bossa-novapodcast-music-203913/)
18. Terminal Simple [Sketchfab](https://sketchfab.com/3d-models/terminal-simple-7fba9c94723e4127a442dd054da221d9)
19. Modular factory button [Sketchfab](https://sketchfab.com/3d-models/modular-factory-button-50f3011929a247418b6c3c46614c53b8)
20. Modular Pipes [Sketchfab](https://sketchfab.com/3d-models/modular-pipes-f43677d2d1014669b7c7a9f220d46eb3) by DJMaesen
21. Manometer [Sketchfab](https://sketchfab.com/3d-models/old-dirty-manometer-28f6b13d71cd4e90ad890f17eb69b40f)
22. Characters and Animations provided by Mixamo. [mixamo](https://www.mixamo.com/)
