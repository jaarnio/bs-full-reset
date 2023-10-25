## autorun.brs

This is a Brightscript script that can be put on the root of a player's SD Card. If a player boots up with this script, it will perform a deep factory reset.
Recommended steps to deploy to a running player: "Disable Autorun -> Format SD -> Upload autorun.brs -> Reboot"

## autozip.brs

This is a helper script that can be added to a zip package, which enables the player to auto extract the zip contents. Typically this is used to deploy a setup package as a zip file named "autorun.zip"

## Presentations

BrightAuthor (classic) and BrightAuthor:connected Presentation that wraps the reset script into a Presentation format. These Presentations can be published via local file network, or via cloud based Groups in the respective platforms. Once published, the Presentation forces the player to erase its storage and reset itself. This can be used to "eject" a player out of the old BrightSignNetwork and migrate to the new BSN.cloud (assuming new Provision records have been created).
