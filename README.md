<img width="1950" height="1080" alt="KerbalWilds_Poster_KerbalCaption" src="https://github.com/user-attachments/assets/7bfc24de-1aa2-421f-9142-4bbb7ffc56b9" />

# Kerbal Wilds
A system replacer planet mod for Kerbal Space Program heavily inspired by the solar system from the 2019 masterpiece of a video game Outer Wilds. Outer Wilds is best enjoyed without spoilers (as the only progression mechanic is what you the player know about the story), so please play that game before playing this mod. Kerbal Wilds is a realistic reinterpretation of the Outer Wilds solar system at 6000:1 scale. (That's 1/4th of RSS, or 2.5x stock KSP scale; there are settings for RSS, Stock, and Toy scale as well in SETTINGS.cfg). The scope is (presently) limited to exploration of the natural world, rather than the space-archaeology that makes up so much of the original game.

**Mod Prerequisites**
* Kopernicus and all of its prerequisites. https://github.com/Kopernicus/Kopernicus/releases (Required to load planet mods.)
    * HarmonyKSP. https://github.com/KSPModdingLibs/HarmonyKSP/releases
    * KSPTextureLoader. https://github.com/Phantomical/KSPTextureLoader/releases
    * ModularFlightIntegrator. https://ksp.sarbian.com/jenkins/job/ModularFlightIntegrator/
    * ModuleManager https://ksp.sarbian.com/jenkins/job/ModuleManager/ (which you probably already have anyway)
* Kopernicus Expansion. https://github.com/VabienArt/KopernicusExpansion-Continueder/releases/ (Required for RegionalPQS)

**Bundled Mods**
* VertexColorMapEmissive by Lt. Duckweed. https://github.com/jamespglaze/VertexColorMapEmissive (Required for Hollow's Lantern)
* Scientific Revolution by StollD. https://github.com/StollD/SciRev (Required for science definitions.)
* VertexMitchellNetravaliHeightmap. https://github.com/pkmniako/Kopernicus_VertexMitchellNetravaliHeightMap (Required for some planet heightmaps)

**Supported Mods**
* Principia (highly recommended for realistic orbits around the Hourglass Twins and Hollow's Lantern, as well as axial tilt.) https://github.com/mockingbirdnest/Principia
* EVE Volumetrics Release-5 (Volumetric clouds for almost every planet! Note: Release-3 is _not_ (yet?) supported!) https://www.patreon.com/blackrack/posts/true-volumetric-139879553
    * For this, you MUST_ install EnvironmentalVisualEnhancements, StockVolumetricClouds, and Scatterer. 
	* You must _NOT_ install StockScattererConfigs.
* Scatterer (highly recommended for much nicer atmosphere rendering) https://github.com/LGhassen/Scatterer/releases (a more up to date scatterer is also included in Blackrack's Patreon version of EVE Volumetrics)
* Distant Object Enhancement. (Although if you also have scatterer, turn off the planet flares and just use the skybox dimming.) https://forum.kerbalspaceprogram.com/topic/205063-ksp-131-distant-object-enhancement-doe-l-2217-2026-0626/
* Kerbal Renamer (for authentic Hearthian names!) https://github.com/KSP-RO/KerbalRenamer/releases/
* Texture Replacer (highly recommended for custom-built skybox) https://github.com/ducakar/TextureReplacer/releases/
    * If you want only the Hearthian skin, you will have to manually remove the default TR Kerbal hairstyle skins in GameData/TextureReplacer/Skins/TR.

**System Layout**
* Sun: A K8IV Subgiant, just on the cusp of evolving into a red giant.
* The Hourglass Twins: Binary system of half-Earth-mass terrestrial planets.
    * Ember Twin: A planet covered in canyons and mesas.
    * Ash Twin: A ball of sand with some equatorial landmasses.
* Timber Hearth: Barren desert world with oasis-filled multi-ring impact basins.
    * The Attlerock: A brown-gray moon-like world.
* Brittle Hollow: A low-density rocky planet with jointed columnar terrain.
    * Hollow's Lantern: A volcanic moon with a molten surface.
* Giant's Deep: A massive world with swirling green clouds.
* Dark Bramble: An ice world with what appears to be creeping space vines.
* The Interloper: An interstellar comet on an eccentric retrograde orbit.

**Scale Notes**
* In GameData/KerbalWilds/SETTINGS.cfg, you can change the scale of the solar system.
* Supported options are RSS (1:1), Quarter (1:4), KSP (1:10), and Toy (1:120).
* The mod was built at Quarter scale and so works best there, but KSP scale should work fine. The other two can be a little finicky.
* SigmaDimensions is NOT compatible with this mod.

**Science Notes**
* The Infrared Telescope can only be used in high orbit. It also has a new Infrared Astronomy science experiment which requires crew on the vessel in order to use.
* The Mystery Goo has been turned into an astrobiology experiment, and can ONLY be used inside atmospheres.
* There is less science available overall in this system, so you will likely have to visit multiple biomes on each planet.
* There are science definitions for each planet which explore some of the interesting properties of each planet. Read them!
* Mod science definition support TBD.

**F.A.Q.**
* Are there Outer Wilds spoilers?
    * The mod does have some spoilers for Outer Wilds. It probably won't ruin your experience of the original game... but it might, so if I were you I would play through the entirety of Outer Wilds first. If you do choose to play the KSP mod and only after that play Outer Wilds, I'd be curious to know your experience.
    * There are virtually no references to its DLC (at least not yet) so if you haven't played Echoes of the Eye yet but you want to, you will be safe to play this KSP mod.
* Is the QM or the 6th Location implemented?
    * they are both post-1.0 stretch goals, and will _not_ have the game mechanic that makes it so weird and interesting in the original game.
* What about the Stranger?
    * I have an idea for how to do it, but it will not be a celestial body. It is also a post-1.0 stretch goal.
* How do you do Brittle Hollow and Dark Bramble?
    * They are implemented as more realistic planets. B.H. is not hollow and Dark Bramble doesn't do what it does in the original game. In particular, Dark Bramble is represented as the unnamed ice planet that pre-dates the Bramble, based on an illustration of the past of the solar system visible in the EOTE DLC which showed the early stages. There are no black holes or wormholes, as they would not be compatible with Principia (which does not allow crafts to teleport).
* Will there be the sand flow on the Hourglass Twins, or caves on the Ember Twin?
    * both of those are out of the scope of a KSP planet mod. Actually, if I was making the Realistic Hourglass Twins as a standalone worldbuilding project rather than a KSP mod, I'd represent them as a near-contact binary made of two egg shaped lobes, similar to Rocheworld. I think you could even justify the sand transferring back and forth over the course of the day with some kind of tidal effect from the Sun or the eccentricity of the orbits. Sadly, KSP does not support non-spherical atmospheres, a problem I have been dealing with in KSP modding ever since Whirligig World.
* Why is Timber Hearth so arid?
    * The craters are interpreted as multi-ring impact basins, like we see on the Moon and Mercury. These are rimmed by tall mountains, which means that, since all the water has pooled in the lowlands of the craters, almost the entire planet is in a huge rain shadow. The Hearthians don't see their planet as arid, since they exclusively live in the lush Village Basin. Just as how we don't really see our planet as mostly water when we imagine it in our heads, and we named it "earth" instead of "ocean," the Hearthians don't see their planet as mostly desert, and named their world after the forest biome in which they exclusively live. 
	* Timber Hearth also had arid highlands in the 2015 Alpha version!
* Will there be alien structures, stations, or spacecrafts?
    * As a post-1.0 stretch goal, _maybe_. But my feeling is that a KSP mod will never approach the depth of narrative storytelling possible in Outer Wilds, so I won't be attempting to weave an intricate narrative. Maybe a few structures that gesture towards the story. Honestly one problem is I'm just not that good at modelling buildings, and I'm not sure how I'd pull off the specific architectural styling shown in the game.
* Where's the Interloper's tail?
    * This is one of the biggest flaws in the mod at present. I don't have the Unity experience required to use ScaledDecorator. I asked R-T-B about adding stock comet FX to celestial bodies, and they said they would look into it.
    * If you want to contribute a ScaledDecorator comet tail, please do get in touch, I would massively appreciate it.

<img width="726" height="737" alt="image" src="https://github.com/user-attachments/assets/b0a15fe5-ce2e-4384-ad4d-c2914aa93cb1" />

<img width="868" height="786" alt="image" src="https://github.com/user-attachments/assets/bcee15fa-0730-47fa-aa16-38b4fed54a8d" />

<img width="842" height="769" alt="image" src="https://github.com/user-attachments/assets/fc4238b8-fa97-47f0-94b1-2448fa2db356" />
