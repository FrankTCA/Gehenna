# Gehenna
Gehenna is the world's first OTG nether preset. It attempts to completely redo the way that noise is handled in the nether, so it looks much more scary, in addition to adding structures and features.

Right now, we're still in alpha phase. Go to the OTG discord to download the latest releases of this preset.

Right now, we are still working on compatibility with other mods. There is some very basic compatibility code in place, but there has been no testing done yet. Stay tuned for that.

Discord: https://discord.gg/YmRXXkkRBu

## Building
If you wish to build a presetpacker jar from source, I have another repository that's a fork of PG85/WorldPacker for you to use.

```
git clone --recursive https://github.com/FrankTCA/Gehenna-WorldPacker.git
cd Gehenna-WorldPacker
# If you want the latest commit (unstable), run the following commands. You will not recieve support for any issues this may cause.
cd Presets/Nether365
git pull origin cpt-4
cd ../..
# Make sure your java version is set to Java 8
export JAVA_HOME=/path/to/jdk-8
# Build the preset
./build_preset.sh
```
(Instructions are for UNIX-based systems (e.g. macOS or Linux). Procedure shouldn't be much of a change on Windows.)

It is also, of course, possible to simply put the preset in the Presets directory inside of the OpenTerrainGenerator config dir (config/OpenTerrainGenerator/Presets on Forge, plugins/OpenTerrainGenerator/Presets on Spigot).

## Contributions

Please reach out on the Gehenna Discord and ask permission before contributing, as this is a work of art and not all changes necessarily fit.

However, we would love for you to contibute and we will work with you to do so.

Proper credit will be given on the author line of any files that are contributed.
