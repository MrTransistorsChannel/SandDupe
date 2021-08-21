# SandDupe
### This plugin brings back fixed gravity-affected block duping on PaperMC servers.
Since Paper fixes this issue by simply adding a check if a block should stop moving into the portal, we can`t check if an entity touches it.
This plugin just spawns a new FallingBlock entity when a FallingBlock entity hits the portal and is converted into block. This allows for the original block being thrown into the portal again thus simulating the way it works in vanilla Minecraft.
