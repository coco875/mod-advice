# mod-advice
# My criters 
* opensource or code visible
* documented
* more then just few tweak

## Mod of optimisation

|    name   |  version | description | recommanded |
| --------- | -------- | ----------- |-------------|
| sodium | 1.16+ (fabric) | optimise the render of the game, the lastest version have some conflict | yes |
| embeddium | 1.18+ (forge) | is a fork of rubidium and is a port of sodium for forge, have more bugfixe then rubidium so I advice tu use it instead of rubidium | yes |
| rubidium | 1.16+ (forge) | is a port of sodium for forge his owner is busy so he have less bug fixes then embeddium | no |
| lithium | 1.16+ (fabric) | optimese tps (game physics, mob AI, block ticking, etc) in general | yes |
| canary | 1.18+ (forge) | a port of lithium for forge same functionnality | yes |
| radium | 1.16+ (forge) | also a port but I don't recomand this mod because less updated and less bug fixe then canary | no |
| ferritcore | 1.16+ (fabric, forge) | reduce memory usage | yes |
| modernfix | 1.16+ (fabric, forge) | reduce memory and reduce loading time he have a lot of documentation combined with ferritcore you can run the game with 512mb of ram in modded more but less then not here | yes |
| immediatlyfast | 1.18+ (fabric, forge) | this mod can be used with the lastest version of sodium/embeddium to gain fps | yes |
| phosphore | 1.16-1.19 (fabric) | optimise light engine, why it's not in 1.20 or have less efficiency, because mojand optimise light engine so it's not required anymore | yes (before 1.20) |
| radon | 1.16-1.19 (forge) | a port of phosphore | yes (before 1.20) |
| starlight | 1.16+ (fabric, forge) | a very similar situation then phosphor the only you will gain is on server side so on client is useless | yes (before 1.20, but not necesserly after) |
| lazy DFU | 1.16+ (fabric, forge) | a very similar situation then light engine, the DFU have been optimise in 1.20 | yes (before 1.20) |
| krypton | 1.18+ (fabric) | it's optimise network based on velocity and paper optimisation | yes |
| krypton reforged | 1.18+ (forge) | a port of krypton | yes |
| pluto | 1.18-1.19 (forge) | also a port of krypton not updated for now in 1.20 and have a bug then krypton reforged don't have in 1.19.2 | no (you can use instead of krypton reforged and have less fast/update then other port) |
| raknetify | 1.17+ (fabric) | is an alpha mod so you can encounter bug, should be more efficient then vanilla more then krypthon I don't know | maybe (krypton will be useless so don't need to put krython whit it) |
| fastload | 1.18+ (forge, fabric) | speedup loading time of a world/server | yes |
| Carpet-Fixes | 1.19+ (fabric) | fix server bug, by seing his issue It's look to not be incompatible with many mod | can be (I don't try) |
| Carpet forge | 1.19+ (forge) | a port of Carpet-Fixes | can be (I don't try) |
| Blanket | 1.19+ (fabric) | fix client bug, by seing his issue It's look to not be incompatible with many mod | can be (I don't try) |
| Entity Culling | 1.18+ (forge, fabric) | use a better culling then vanilla work with rubidium/embedium | yes |
| More Culling | 1.18+ (fabric) | same vibe but on more thing | can be |
| Cull Leaves | 1.18+ (forge, fabric) | same has before for leaves so every forest, jungle, etc will be better | yes |
| Cull Clouds | 1.18+ (fabric) | same vibe and clound are frequent but if you use mod who modify clound it's can be useless or if you disable cloud | can be |
| Distant Horizons | 1.18+ (forge, fabric) | hmm this mod can help see far but will decrease fps (he have update since but), it's depend if you want 16 chunks fully detailled or 8 and 128 chunk more | it's depend |
| oculus | 1.18+ (forge) | this mod will decrease fps but enable shader so you can have both but it's depend of your computer and what you want | it's depend |
| iris | 1.18+ (fabric) | this mod will decrease fps but enable shader so you can have both but it's depend of your computer and what you want | it's depend |
| Chunky | 1.18+ | this will pre-generate chunk so can be useful when you want pre-generate chunk so when player go in less drop of tps possible (I advice to use it on server before starting with everyone) | yes |
| ServerCore | 1.18+ | reduces lag spikes in different senario, have tool to reduce entity, lobotize villager, etc | yes |
| Let Me Despawn | 1.18+ | reduce condition for a mod to despawn so when a modded creatur have tool or other it's despawn, it's avoid keeping a lot of modded mob (you can still use a name tad to avoid despawn) | yes |
| Alternate Current | 1.18+ | reduce impact of redstone in tps | yes |
| It Shall Not Tick/No see no tick (lastest) | 1.18+ | avoid some tick so better tps | yes |
| Rubidium Extra/sodium extra | 1.18+ | show more option who can be use like a fps counter, Animations, Particles, Details, etc| yes |
| AI Improvements | 1.18+ | optimise IA, another mod is also out made by potato_boy (Similar to AI Improvement, but is implemented by Mixin and has a better performance - potato_boy) | no (use Goal optimizer do the same thing) |
| Goal Optimiser | 1.18+ | Allow you to configure the goals registry of Sheep, Pig, Cow, Fish, Chicken (Similar to AI Improvement, but is implemented by Mixin and has a better performance) and Do optimization to the Goal Selector (This is mainly more effective in 1.16.5, because in 1.18+ mojang optimize its ticking in the similar way) | yes |
| Does Potato Tick? | 1.18+ | no tick something who are far to simplify | yes |


### other mod of opti |
|    name   |  version | description | recommanded |
| --------- | -------- | ----------- |-------------|
| memoryLeakFix | 1.17+ | fix 8 things in mc can save a bit of memory | can be |
| Saturn | 1.17-1.19 | fix one thing who are already fix in memoryLeakFix | no |
| Video Tape/fix GPU memory leak | 1.18+ | I don't mesure performance, and I don't encounter this issue before | can be |
| Lightspeed | 1.17-1.19 | reduce time to launch but I think modernfix do similar thing so retry on your side with and without and see if help or not | can be |
| Dynamic FPS, fps reducer, Idle Tweaks | 1.18+ | is not optimisation is just reduce ressource when you are not on the game | yes |
| C2ME | 1.18+ (fabric) | it's an experimental mod who have goal to improve world generation (you maybe need to disable some mixin in config to run) | no |
| Leaves Be Gone/Fast Leaf Decay/Rapid Leaf Decay | 1.18+ | when you cut down a tree leaf will disapears more rapidelly (avoid flying leaf) and leaf it's a block who can be laggy visually so it can improve fps | yes (just for esthical side) |
| VulkanMod | 1.18+ (fabric) | it's experimental, what it does ? he replace the rendering engine opengl to vulkan, vulkan is more disigned for video game so in theory you get more fps, but sodium/embeddium work with opengl same for immedialtlyfast so at the end you will have less fps and incompatibility with mod who also use opengl | no (to early, not enought compatible/polished) |
| Methane | 1.18+ | a mod who change lightmap so it's when you have light actualisation | can be |
| Very Many Players/Too Many Players | 1.18+ (fabric) | I don't try but normally should gain in fps | can be |
| Nvidium | 1.18+ | when I try it I don't see a big perfomance difference, it's in alpha | no |
| Memory Clear | 1.18+ | I don't think this be useful with mod who optimise memory etc | no |
| Cyclotrimethylenetrinitramine | 1.18+ | experimental perfomance not mesured I don't know if it work but only client for now | no |
| Enhanced Block Entities | 1.18+ (fabric) | reduce lag of vanilla block entity so if you use block who are not heritate of chest etc this will be lag | can be |
| Bedrodium/Bocchium | 1.18+ | hmm can be useful, I trust potato_boy mod of optimisation event is just few tweak | yes |
| VanillaIcecreamFix | 1.19+ | fix 3 bugs, and cull particle useful | can be |
| Client Side Noteblocks | 1.16+ | it optimise noteblock but every player don't use blocknote so it can be or not useful | can be |
| Smooth Boot | 1.18+ | hmm in 1.20 it become more useless and can increase loading time in some case | no |
| Dimensional Threading | 1.18+ | I try on my side and I have lower tps, why not enought core I think | no |
| DashLoader | 1.18+ | embeddedt [say](https://github.com/embeddedt/ModernFix/issues/75) himself who will not support compatibility between moderfix and dasloader so you lost more then get | no |
| Debugify | 1.18+ | mod to fix minecraft bug but breaking change with a lot of mod | no |
| Better Biome Blend | 1.18+ | very small upgrade just biome blending | can be |
| Model Gap Fix | 1.18+ | fix just a bug but not performance improvement so it's just visual | can be |
| Exordium | 1.18+ | he just unlock fps in menu... you need to take a item in 1111fps | no |
| Better Beds | 1.18+ | to specific so I don't think it's great to put one mod to optimise one thing then you have one time | no |
| FastQuit | 1.18+ | I don't try personnelly but by what I see you quit more faster by running saving task on another thread so you really want qui your solo world faster ? | no |
| Hydrogen | 1.16-1.17 | not maintened and put as archived | no |
| FastAnim | 1.18+ | closed source but I saw in jar and see this will effect only vanilla mob so when you have alex mod or any mod who add a lot of mob is useless | no |
| Noxesium | 1.18+ | not a big change rather then other mod of optimisation and fix some bug so not bad not good | not sure |
| ForgetMeChunk | 1.17-1.19 | it's effective in one case so if you encounter this he can be useful but else not | no |
| Entity Collision FPS Fix | 1.19 | when you have a lot of collision it will no longer drop fps, fix in 1.19.3 so no longer useful | no |
| Ksyxis | 1.18+ | avoid load the first 144 chunk but after when you join the world it will load it, moderfix have a better implementation who already solve this | no |
| FeyTweaks (fabric) | 1.18+ | very small tweaks just for two vanilla item | no |
| Sodium Blending Registry | 1.18+ | fix a bug for sodium before 0.5 but if you use sodium after it no longer util | no |
| logcleaner  | 1.18+ | this will just auto remove logs so it's depend | can be |
| log begone, DeLogger, etc | 1.18+ | just reduce print of log so it will reduce log but when you need to give a log for a crash it will be less helpful so... | no |
| No Unused Chunks | 1.18+ | don't save chunk who don't change so reduce world size but when you load the chunk he need to generate it again | no |
| Clean F3 | 1.18+ | if you never use F3 it's no interesting (also remove characters display on scree don't optimise the game so much) and I think betterF3 better because you have all information but colored so more easier to find some | no |
| More Culling Extra | 1.18+ | I don't try and if the modder of more culling don't it his mod so it's not necesserly | no |
| Particle Blocker | 1.18+ | already made by Rubidium Extra/sodium extra | no |
| Faster Random | 1.18+ | the mod have goal to optimise random but the dev archived this because after retesting properly it was slower (decrese fps) | no |
| Async Locator | 1.18+ | optise just the locate command structure essentials already make this and have other tweak | no |
| Structure Essentials | 1.18+ | optise and help locate structures in world, not useful for everyone | no |
