
# Explodium Breathing Engines
Modified jet engines, explodium vapour intakes, and oxidizer tanks for Kerbal Space Program 1.2.2's planet Eve. Also includes a Resources definition for "ExpVapour" (Explodium Vapour), which should be found in Eve's atmosphere only. Intended as a jet engine counterpart to OhioBob's Eve Optimized Engines.

These are configuration files only, no software. This is also a work in progress. MIT License similar to OhioBob's part pack.

With the conversion of the intakes to atmospheric harvesters, the ExpVapour harvesters now only work on Eve, or any planet that has ExpVapour added as an atmospheric resource. Harvesters require manual activation, but otherwise work like the original intakes. I'd suggest using the Brakes action group to deploy the harvesters, then use the Stage action group to start them.

The engines are tuned based on ethane chemistry, where the KSP Wiki entry for Eve suggests an atmosphere of 90% carbon dioxide and 10% ethane.  Values are based on hydrogen and ethane chemistry suggested here:

http://forum.kerbalspaceprogram.com/index.php?/topic/158643-jet-engines-on-eve-for-alien-space-programs/&do=findComment&comment=3031034

...and also based on RP-1 chemistry here:

http://forum.kerbalspaceprogram.com/index.php?/topic/158643-jet-engines-on-eve-for-alien-space-programs/&do=findComment&comment=3033408

This engine tuning is subject to change, but I think it's where it needs to be. The harvesters will gather MinAbundance to MaxAbundance amounts of Explodium Vapour compared to the original intakes' gathering of IntakeAir, and the engines will use an average of 0.375 U ExV to 1 U OX, similar to an ethane-oxygen reaction.

Engine specific impulse is 45% of the originals, to reflect needing 2.21 times as much OX and ExV to get the same amount of energy as the original engines based on an oxygen-RP1 reaction, while maintaining the original thrust.

Visible engine plumes replaced with blue plumes where appropriate, to match methane / ethane reactions with oxygen.

To install, download a release and copy the contents of GameData to your own GameData folder. Also install a current edition of Module Manager to your GameData folder.
