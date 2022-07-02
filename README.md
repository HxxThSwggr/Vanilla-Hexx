# #'s Lovely Vanilla Modpack
A minecraft modpack of mods, resource- and shader-packs I play with.

Nothing game changing in the sense of the game's content. Mainly make-up and optimizations.

## Content
### | Lists
#### mod_list.txt
All mods and links to their download (preferably [Modrinth](https://modrinth.com/), then [CurseForge](https://www.curseforge.com/minecraft/mc-mods), then whatever).

#### resourcepack_list.txt
All resourcepacks, their download pages and order.

#### shaderpack_list.txt
All (two) shaderpacks and their (one) download page.

### | .minecraft
A .minecraft folder with the mods' configs and shaderpacks' settings.

Includes *return_mods.bat* in the *mods* folder. More below.

### | Ferium
#### ferium_config.json
A [Ferium](https://github.com/gorilla-devs/ferium) config with one profile including all the mods, even the ones not yet available for 1.19.
You can copy the profile to your own Ferium config for easy updating, but dont forget to put in the actual directory behind *"output_dir":* .

Ferium will move any mods (it thinks) it didn't replace to .old folder. You need to move them back every time you *ferium upgrade* with **return_mods.bat**. Check if it moved some mods' old versions back and delete them.

## Issues
A few of the components are incompatible or have issues. I recommend using [MultiMC](https://multimc.org/) where you can disable and enable mods, as well as create multiple instances of Minecraft for tidyness.

If you find some more or notice that any were fixed, make an issue and I'll update this.

**Note:** Even tho *Distant Horizons* has many incompatibilities, it's one of the best mods ever. I recommend using it even if it means disabling the other wonderful mods.

### | Severe
It's recommended to use one or the other. Huge bugs or even crashes.

#### Sodium Extra
Doesn't work for some reason? I just updated everything like normal and it stopped working.

Disable for now.

#### Distant Horizons × Immersive Portals
Huge lags and even crashes when looking into immersive portals with Distant Horizons enabled.

Play with one or the other until (if ever) the two are compatible.

#### Distant Horizons × ExtendedClouds
The clouds are rendered above the distant chunks (closer to the camera), thus covering them.

Play with one or the other until (if ever) the two are compatible.

### | Minor
Not that bad bugs. Definitelly no crashes.

#### Distant Horizons × Iris
The distant chunks are not visible while shaders are on.

No other bugs tho, so you can play with both of them.

#### 3D Skin Layers × Immersive Portals
Incomplete 3D layer when looking into mirrors.

Not that common so it's in minor.

#### 3D Skin Layers × Wildfire's Gender
3D Layer is not applied on the chest that Wildfire's adds.

Actually not even that noticeable.

#### Effective × Sodium
Water splashes are black.

Not that bad. Keep both mods.
