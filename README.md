![hiiiiiiii](assets/hi.png)

this is my CookiMC distribution setup. don't look...

if you wanna mess with it, get [packwiz](https://packwiz.infra.link/installation/), and:

```sh
export PATH="$PATH:$HOME/go/bin" # to make packwiz functional in ur terminal
```

## adding mods
to add mods, do `packwiz modrinth add <url>` or `packwiz curseforge add <url>`, wherever you're downloading the thing from.
if you're doing manual edits (like i had to do for miniwumbo), add the mod jar to the mods directory, and run `packwiz refresh`, so that packwiz creates the metadata for it, and includes it in the modpack.

## exporting modpack
```sh
packwiz modrinth export -o dist/CookiMC-1.3.0.mrpack
```
`-o <dir>` for output directory. if `-o <dir>` isn't specified, it outputs to the root directory
i recommend doing it in the dist directory for better organization

## current mods added to the pack
- [AppleSkin](https://modrinth.com/mod/EsAfCjCV) [2\.5\.2\+mc1\.20\.1] by squeek502
- [Architectury](https://modrinth.com/mod/lhGA9TYQ) [9\.2\.14] by shedaniel
- [Artifacts](https://modrinth.com/mod/P0Mu4wcQ) [9\.5\.17] by ochotonida, Florens
- [Automobility](https://modrinth.com/mod/rqIsPf9F) [0\.4\.2\+1\.20\.1\-fabric] by FoundationGames
- [Balm](https://modrinth.com/mod/MBAkmtvl) [7\.3\.43] by BlayTheNinth
- [Balm](https://modrinth.com/mod/MBAkmtvl) [7\.3\.44] by BlayTheNinth
- [Bendy api](https://modrinth.com/mod/aRnIEV0F) [4\.0\.0] by KosmX
- [Better Ping Display](https://modrinth.com/mod/MS1ZMyR7) [1\.1\.1] by Quintinity
- [BiomesOPlenty](https://modrinth.com/mod/HXF82T3G) [19\.0\.0\.96] by Adubbz, Forstride
- [Bobby](https://modrinth.com/mod/M08ruV16) [5\.0\.1\.1] by johni0702
- [Bookshelf](https://modrinth.com/mod/uy4Cnpcm) [20\.2\.15] by Darkhax
- [Bountiful](https://modrinth.com/mod/BpwWFOVM) [6\.0\.4\+1\.20\.1] by Ejektaflex
- [CICADA](https://modrinth.com/mod/IwCkru1D) [0\.14\.3\+1\.20\.1] by enjarai
- [Chat Heads](https://modrinth.com/mod/Wb5oqrBJ) [0\.15\.7] by dzwdz, Fourmisain
- [ClientSideNoteblocks](https://modrinth.com/mod/flmhXQgb) [2\.7] by DaCubeKing
- [Cloth Config v11](https://modrinth.com/mod/9s6osm5g) [11\.1\.136] by shedaniel
- [Clumps](https://modrinth.com/mod/Wnxd13zP) [12\.0\.0\.4] by Jaredlll08
- [CoolRain](https://modrinth.com/mod/iDyqnQLT) [1\.4\.0\-1\.20\.1] by Jaiz, 
, Config Coding Help:, trashoflevillage, 
 , NeoForge Port and Coding Help:, Leclowndu93150
- [CoroUtil](https://modrinth.com/mod/rLLJ1OZM) [1\.20\.1\-1\.3\.7] by Corosus
- [CreativeCore](https://modrinth.com/mod/OsZiaDHq) [2\.12\.39] by CreativeMD, AriaFreeze
- [Cristel Lib](https://modrinth.com/mod/cl223EMc) [1\.1\.5] by Cristelknight999
- [Critters and Companions](https://modrinth.com/mod/Yd4wb5wZ) [2\.7\.1] by Joosh, EterDelta
- [Drip Sounds](https://modrinth.com/mod/T8MMXTpr) [0\.5\.2] by PieKing1215
- [Dungeons and Taverns](https://modrinth.com/mod/tpehi7ww) [3\.0\.3\.f] by NovaWostra, Walls
- [Durability Tooltip](https://modrinth.com/mod/smUP7V3r) [1\.2\.0] by SuperMartijn642
- [EMI](https://modrinth.com/mod/fRiHVvU7) [1\.1\.24\+1\.20\.1\+fabric] by Emi
- [Easy NPC](https://modrinth.com/mod/Epm6R3P2) [7\.12\.1] by Markus Bordihn
- [Easy NPC \(Bundle\)](https://modrinth.com/mod/CgGEe1h3) [7\.12\.1] by Markus Bordihn
- [Easy NPC: Config UI](https://modrinth.com/mod/uTGjf7vA) [7\.12\.1] by Markus Bordihn
- [Elytra Slot](https://modrinth.com/mod/mSQF1NpT) [6\.4\.4\+1\.20\.1] by Illusive Soulworks
- [Emotecraft](https://modrinth.com/mod/pZ2wrerK) [2\.2\.7\-b\.build\.50] by KosmX
- [EnchantmentDescriptions](https://modrinth.com/mod/UVtY3ZAC) [17\.1\.21] by Darkhax
- [Even More Instruments\!](https://modrinth.com/mod/Mcs3cqJ1) [6\.1\.4] by StavWasPlayZ
- [Fabric API](https://modrinth.com/mod/P7dR8mSH) [0\.92\.12\+1\.20\.1] by FabricMC
- [Fabric Language Kotlin](https://modrinth.com/mod/Ha28R6CL) [1\.14\.1\+kotlin\.2\.4\.20] by FabricMC
- [Falling Leaves](https://modrinth.com/mod/WhbRG4iK) [1\.15\.6] by Fourmisain, BrekiTomasson, RandomMcSomethin
- [FallingTree](https://modrinth.com/mod/Fb4jn8m6) [4\.3\.4] by Rakambda
- [Farmer's Delight](https://modrinth.com/mod/7vxePowz) [1\.20\.1\-2\.5\.7\+refabricated] by MehVahdJukaar, ChrysanthCow, cassiancc
- [Fast IP Ping](https://modrinth.com/mod/9mtu0sUO) [1\.0\.8] by Fallen\_Breath
- [Fast Noise](https://modrinth.com/mod/OnlVIpq5) [1\.0\.13\+1\.20] by ZenXArch
- [FerriteCore](https://modrinth.com/mod/uXXizFIs) [6\.0\.1] by malte0811
- [Figura](https://modrinth.com/mod/s9gIPDom) [0\.1\.6\+1\.20\.1] by skyrina, lumelia, UnlikePaladin, omoflop
- [FiguraSVC](https://modrinth.com/mod/zDF68701) [2\.0\.1\+1\.20\.1] by KnownSH
- [Fish of Thieves](https://modrinth.com/mod/BzOTnuqM) [3\.3\.2] by SteveKunG, PloyiinGz, Gucc1Guy
- [Flan](https://modrinth.com/mod/Si383TIH) [1\.20\.1\-1\.11\.16] by Flemmli97
- [Force Crawl](https://modrinth.com/mod/8dt4QjOA) [1\.0\.4] by Famro Fexl
- [Forge Config API Port](https://modrinth.com/mod/ohNO6lps) [8\.0\.3] by Fuzs
- [Framework](https://www.curseforge.com/projects/549225) [0\.8\.0] by MrCrayfish
- [Freecam](https://modrinth.com/mod/XeEZ3fK2) [1\.2\.1\+1\.20] by hashalite
- [Furnish](https://modrinth.com/mod/5cWCtJmf) [26] by Wouink
- [GeckoLib 4](https://modrinth.com/mod/8BmcQJ2H) [4\.8\.4] by Gecko, Eliot, AzureDoom, DerToaster, Tslat, Witixin
- [Genshin Instruments](https://modrinth.com/mod/UUD6Qkij) [5\.0] by StavWasPlayZ
- [GlitchCore](https://modrinth.com/mod/s3dmwKy5) [0\.0\.1\.1] by Adubbz
- [Handcrafted](https://modrinth.com/mod/pJmCFF0p) [3\.0\.6] by Alex Nijjar, Kekie6
- [Hephaestus](https://modrinth.com/mod/sdSn3wvy) [1\.20\.1\-3\.6\.4\.305] by Slime Knights, AlphaMode
- [Iceberg](https://modrinth.com/mod/5faXoLqX) [1\.1\.25] by Grend
- [Immersive Aircraft](https://modrinth.com/mod/x3HZvrj6) [1\.5\.0\+1\.20\.1] by Luke100000
- [Immersive Furniture](https://modrinth.com/mod/SvN6UGeF) [0\.3\.3\+1\.20\.1] by Luke100000
- [Immersive Melodies](https://modrinth.com/mod/TaSmHw8V) [0\.8\.0\+1\.20\.1] by Luke100000
- [Immersive Paintings](https://modrinth.com/mod/6txNkua3) [0\.6\.13\+1\.20\.1] by Luke100000
- [Indium](https://modrinth.com/mod/Orvt0mRa) [1\.0\.30\+mc1\.20\.4] by comp500
- [Iris](https://modrinth.com/mod/YL57xq9U) [1\.6\.17] by coderbot, IMS212, Justsnoopy30, FoundationGames
- [Iron Chests: Restocked](https://modrinth.com/mod/n2de3t2z) [5\.0\.2] by Dev and Upgrade Textures \- ThatGravyBoat, All Other Textures \- Kekie
- [Item Borders](https://modrinth.com/mod/b1fMg6sH) [1\.2\.2] by Grend
- [ItemFavorites](https://modrinth.com/mod/BBi9csxn) [1\.0\.5\+1\.20\.1] by 2Retr0
- [Jade](https://modrinth.com/mod/nvQzSEkH) [11\.13\.3\+fabric] by Snownee
- [Joy of Painting](https://modrinth.com/mod/YOs4tZea) [fabric\-1\.20\.1\-2\.0\.0] by xerca
- [Kambrik](https://modrinth.com/mod/zfbCkvdZ) [6\.1\.1\+1\.20\.1] by Ejektaflex
- [LambDynamicLights](https://modrinth.com/mod/yBW8D80W) [4\.4\.0\+1\.20\.1] by LambdAurora
- [LazyDFU](https://modrinth.com/mod/hvFnDODi) [0\.1\.3] by tuxed
- [Lithium](https://modrinth.com/mod/gvQqBUqZ) [0\.11\.4] by JellySquid, 2No2Name
- [Lootr](https://modrinth.com/mod/EltpO5cN) [0\.7\.35\.86] by Noobanidus, ZestyBlaze, embeddedt
- [Macaw's Bridges](https://modrinth.com/mod/GURcjz8O) [3\.1\.2] by SketchMacaw
- [Macaw's Stairs and Balconies](https://modrinth.com/mod/iP3wH1ha) [1\.0\.2] by Sketch Macaw, Peachy Macaw
- [Magnum Torch](https://modrinth.com/mod/jorDmSKv) [8\.0\.2] by Fuzs
- [Make Bubbles Pop](https://modrinth.com/mod/gPCdW0Wr) [0\.3\.0\-fabric] by Tschipcraft
- [Mod Menu](https://modrinth.com/mod/mOgUt4GM) [7\.2\.2] by Prospector, haykam821, TerraformersMC
- [Model Gap Fix](https://modrinth.com/mod/QdG47OkI) [1\.15] by Mehvahdjukaar
- [Mouse Tweaks](https://modrinth.com/mod/aC3cM3Vq) [2\.26] by Ivan Molodetskikh \(YaLTeR\)
- [MrCrayfish's Furniture Mod: Refurbished](https://www.curseforge.com/projects/897116) [1\.0\.20] by MrCrayfish
- [No Chat Reports](https://modrinth.com/mod/qQyHxfxd) [1\.20\.1\-v2\.2\.3] by Aizistral
- [Nvidium](https://modrinth.com/mod/SfMw2IZN) [0\.2\.6\-beta] by Cortex
- [Overweight Farming](https://modrinth.com/mod/bCxmmxKN) [1\.20\.1\-2\.0\.3\-fabric] by Binome, MrSterner
- [PacketFixer](https://modrinth.com/mod/c7m1mi73) [3\.3\.2] by TonimatasDEV
- [Pehkui](https://modrinth.com/mod/t5W7Jfwy) [3\.8\.3\+1\.14\.4\-1\.21] by Virtuoel
- [Polymorph](https://modrinth.com/mod/tagwiZkJ) [0\.49\.11\+1\.20\.1] by Illusive Soulworks
- [Potion Container](https://modrinth.com/mod/V0m1Bqqf) [1] by meekeyn
- [Prism](https://modrinth.com/mod/1OE8wbN0) [1\.0\.5] by Grend
- [Puzzles Lib](https://modrinth.com/mod/QAGBst4M) [8\.1\.33] by Fuzs
- [Random Mob Sizes](https://modrinth.com/mod/ccz0Dj7d) [1\.20\.1\-2\.2\.3] by Buecher\_wurm
- [ReFramed](https://modrinth.com/mod/jCpoCBpn) [1\.6\.6] by Adrien1106
- [ResearchTable](https://modrinth.com/mod/OvsIV3cn) [1\.1\.3] by S Scott
- [Resourceful Lib](https://modrinth.com/mod/G1hIVOrD) [2\.1\.29] by ThatGravyBoat, Epic\_Oreo
- [ServerCore](https://modrinth.com/mod/4WWQxlQP) [1\.5\.2\+1\.20\.1] by Wesley1808
- [Show Me Your Skin\!](https://modrinth.com/mod/bD7YqcA3) [1\.9\.0\+1\.20] by enjarai
- [Simple Voice Chat](https://modrinth.com/mod/9eGKb6K1) [1\.20\.1\-2\.6\.24] by Max Henkel
- [Sit](https://modrinth.com/mod/VKXzIykF) [1\.20\.1\-27] by bl4ckscor3
- [Sodium](https://modrinth.com/mod/AANobbMI) [0\.5\.8\+mc1\.20\.1] by @jellysquid3
- [Sophisticated Backpacks](https://modrinth.com/mod/ouNrBQtq) [1\.20\.1\-3\.23\.4\.5\.110] by P3pp3rF1y, Ridanisaurus, Salandora
- [Sophisticated Core](https://modrinth.com/mod/9jxwkYQL) [1\.20\.1\-1\.2\.7\.15\.166] by P3pp3rF1y, Salandora
- [Styled Nicknames](https://modrinth.com/mod/DOk6Gcdi) [1\.2\.1\+1\.20] by Patbox
- [SuperMartijn642's Config Lib](https://modrinth.com/mod/LN9BxssP) [1\.1\.8\+a] by SuperMartijn642
- [TW's Decorative Food](https://modrinth.com/mod/656seq5J) [1\.20\.1\-2\.0\.1] by Tenacious Wonder
- [Tax Free Levels](https://modrinth.com/mod/jCBrrLTs) [1\.4\.23] by Fourmisain
- [TerraBlender](https://modrinth.com/mod/kkmrDlKT) [3\.0\.1\.10] by Adubbz
- [Towns and Towers](https://modrinth.com/mod/DjLobEOy) [1\.12] by Kubek and Biban\_Auriu, Cristelknight999
- [TrashSlot](https://modrinth.com/mod/vRYk0bv7) [15\.1\.5] by BlayTheNinth
- [Trinkets](https://modrinth.com/mod/5aaWibi9) [3\.7\.2] by Emi, C4
- [Very Many Players](https://modrinth.com/mod/wnEe9KBa) [0\.2\.0\+beta\.7\.102] by ishland
- [WaterFrames](https://modrinth.com/mod/eBzFuVTM) [2\.1\.22] by SrRapero720
- [WaterMedia](https://modrinth.com/mod/G922NeHS) [2\.1\.37] by SrRapero720, Goedix
- [WATERViSION](https://modrinth.com/mod/watervision) [FB\-mc1\.20\.1\-v0\.1\.0\-alpha] by SrRapero720
- [WaterMedia YT Plugin](https://modrinth.com/mod/P0w3IrnX) [2\.1\.2] by SrRapero720
- [Waystones](https://modrinth.com/mod/LOpKHB2A) [14\.1\.21] by BlayTheNinth
- [What Are They Up To](https://modrinth.com/mod/AtB5mHky) [1\.20\.1\-1\.2\.3] by Corosus
- [Wildfire's Female Gender Mod](https://modrinth.com/mod/bcOsQHnC) [1\.20\-3\.0\.1] by WildfireRomeo
- [WorldEdit](https://modrinth.com/mod/1u6JkXh5) [7\.2\.15\+6463\-5ca4dff] by EngineHub
- [WorldEditCUI](https://modrinth.com/mod/NSLJJooQ) [1\.20\+01] by lahwran, yetanotherx, Mumfrey, TomyLobo, mikroskeem
- [Xaero's Minimap](https://modrinth.com/mod/1bokaNcj) [26\.5\.0] by xaero96
- [Xaero's World Map](https://modrinth.com/mod/NcUtCpym) [1\.46\.0] by xaero96
- [YetAnotherConfigLib](https://modrinth.com/mod/1eAoo2KR) [3\.6\.6\+1\.20\.1\-fabric] by isXander
- [Zoomify](https://modrinth.com/mod/w7ThoJFB) [2\.15\.2\+1\.20\.1] by isXander
- [customnetherportals](https://modrinth.com/mod/2OCozLqc) [2\.0\.0] by Nighttie
- [figuraextrabone](https://modrinth.com/mod/PNBaqE8G) [0\.0\.3\-fabric] by asamikafune
- [miniwumbo](https://fabricmc.net/) [0.1.1]
###### (list generated by Prism Launcher, slightly edited by me)

#### if you're a mod developer, see your mod here, and don't want me to add it here, first of all i'm sorry. second, please contact me/create an issue and i will remove it
