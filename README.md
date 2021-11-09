# Nether365
Nether365 is the world's first OTG nether preset. It attempts to completely redo the way that noise is handled in the nether, so it looks much more scary, in addition to adding structures and features.

Right now, we're still in alpha phase. OTG has not yet been released fully for 1.16-0.1.0, but is on the verge of an initial beta release on CurseForge. Go to the OTG discord to download OTG jars for 1.16.5 as well as releases of this preset.

Right now, we are still working on compatibility with other mods. There is some very basic compatibility code in place, but there has been no testing done yet. Stay tuned for that.

## Building
If you wish to build a presetpacker jar from source, I have another repository that's a fork of PG85/WorldPacker for you to use.

```
git clone --recursive https://github.com/FrankTCA/Nether365-WorldPacker.git
cd Nether365-WorldPacker
# If you want the latest commit (unstable), run the following command. You will not recieve support for any issues this may cause.
cd Presets/Nether365
git pull origin 1.16.5
cd ../..
# Make sure your java version is set to Java 8
export JAVA_HOME=/path/to/jdk-8
# Build the preset
./build_preset.sh
```
(Instructions are for UNIX-based systems (e.g. macOS or Linux). Procedure shouldn't be much of a change on Windows.)

It is also, of course, possible to simply put the preset in the Presets directory inside of the OpenTerrainGenerator config dir (config/OpenTerrainGenerator/Presets on Forge, plugins/OpenTerrainGenerator/Presets on Spigot).

## Licensing
If you want to use my work, you are freely able to. The license we use can pretty much be summed up to:
1) Keep my license header on any files that have it.
2) If you meet me in real life, you have to buy me a doughnut.

## Contributing
We would love your contributions!

If you wish to contribute, simply fork the repository and pull request the changes upstream when you're done.

This is, of course, a work of art, so we may not accept everything necessarily if it doesn't fit, so you may want to reach out to me before you put effort in.

Any code that makes it into the repository will be given proper credit via the author line of any files that were contributed.
