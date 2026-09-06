# Mario Kart World Interactive Map
[![Interactive Leaflet Map Screenshot](https://github.com/normal-platinum/MKW-Map/blob/main/preview.png)](https://normal-platinum.github.io/MKW-Map/)
*Click the map above to explore the live interactive version.*

This repo started as a fork of [MrL314's MKW-Map](https://github.com/MrL314/MKW-RoadMap), but has been converted into a workspace for Obsidian Leaflet!<br> 
The original readme can be found [here](https://github.com/normal-platinum/MKW-Map/blob/main/Maps/Maps.md).

Work by Lumi Platinum aka normal-platinum<br>
Credit for certain images to [MrL314](https://github.com/MrL314/MKW-RoadMap) and [Lady Sophie](https://www.mariowiki.com/User:LadySophie17)<br>
Credit for certain discoveries to [AkBKukU](https://github.com/AkBKukU/mkw-map) and [Maelmc](https://github.com/MrL314/MKW-RoadMap/issues/2)<br>
Leaflet by [Leaflet Maintainers](https://github.com/Leaflet/Leaflet)<br>
Obsidian Leaflet by [javalent](https://github.com/javalent/obsidian-leaflet)<br>
leaflet-groupedlayercontrol by [ismyrnow](https://github.com/ismyrnow/leaflet-groupedlayercontrol)<br>
leaflet-smooth-wheel-zoom by [mutsuyuki](https://github.com/mutsuyuki/Leaflet.SmoothWheelZoom)<br>

Special Thanks to: 
- Maelmc, for their feedback on the original repo
- Lady Sophie, for engaging in all my ramblings about the game
- All of the lovely helpful contributors of the Super Mario Wiki

If you contributed, feel free to add your name below!<br>
Contributors:
- example

## How to contribute
1) Installation Setup
	1) Install Obsidian and some form of git cloning (I prefer using GUI, so I have Desktop Plus)
	2) In Github, fork this repo
	3) Clone that fork to your drive (using git clone or Desktop Plus)
		- You might be able to clone without forking? I'm not sure.
2) Obsidian Setup
	1) In Obsidian, open the folder where you cloned to as a new vault
	2) Enable plugins (required for Leaflet)
	3) Double click on "Leaflet" in the left outline to open up the file
3) Edit! (Obsidian Leaflet Tips)
	- You will most likely want to enable the roads layer, using the 3 stacked rhombus icon in the top right.
	- While in editing view, you can change parameters of the map. In order to view the map, either toggle reader view or click outside the code block.
	- Be careful when dragging the map, as markers can also be dragged. This can be avoided by using the lock icon in the top right.
	- Please do NOT "Convert to Code Block"! This converts the marker's JSON to YAML, which will cause that marker to not appear on the website. 
	- When you add a screenshot to your marker in Obsidian, make sure that the 'Note to Open' field includes the file ending. Otherwise, it will open a new .md file instead of your image.
4) Publish Your Changes
	1) Commit changes to your fork. It's a good idea to do this regularly, especially if you are working collaboratively
	2) When your fork reaches a finished state, submit a Pull Request to merge your changes into the main branch. Please describe exactly what you changed!

## Contributions wanted
- **BEFORE COMMIT**
- Free Roam sections of GBR, rDDJ, rSHS, DBB, rAF, SSS, rWSh, rKTB
- P Switch Missions (have 0%), Peach Medallions (have 3.5%), and ? Panels (have 3.33%)
- Yoshi's Drive-Throughs, Snack Bars, Food Trucks, and other Dash Food spots (have 178)
- Vending Machines
- Track/Route/Rally Checkpoints (have 0)
- Giant Coin Piles (have 20)
- Nabbit (have 39), Chargin' Chuck (have 8)
- Binoculars (have 68), RVs (have 1), campfires (have 7), other random objects
- Anything else you want to map out!
- Large Undertakings
	- More convenient way to contribute markers
	- More marker metadata (tracks/routes active, spawn probabilities, mission/checkpoint paths)
	- Option for non-homogenous markers (eg. Fast Travel --> each Course/Character, Yoshi's --> each Dash Food)
	- Signal Bugs/enemy spawn locations and probability (requires indexing and studying nearly every road segment in the game)
### Naming Conventions
Please refer to [Names.md](https://github.com/normal-platinum/MKW-Map/blob/main/Names.md)
