# Leapster-Tools
A replacement for LeapFrog-Tools with an end goal of having the highest accuracy possible with each tool. This repository is only for the Leapster, Leapster TV, Leapster L-Max and Leapster 2!


# LeapSplit
Currently, LeapSplit only extracts the following:
- Product info (stuff like the name, version number, compiler name and build date)
- Instruments (don't ask how to use these! I don't know yet due to the pitch format being unknown) (not all games have unique instruments in them)
- RAW audio (the A-Law stuff you can find by opening the ROMs in audacity)
- LPC audio (the codec is unknown and the extraction code is incomplete. There's more to the format than just ending on C00F.)
- SYN sequences (the music format used on the Leapster)
- SWF files (the Flash files used for stuff like cutscenes and gameplay in a ton of games)

How to use LeapSplit:
- Double click the script
- Navigate to and double click your ROM
- Dig through the assets that have been extracted from your ROM (should be in {script folder}/Split_ROMs/{game name}/)
