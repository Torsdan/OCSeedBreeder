# OCSeedBreeder
Automatic seed breeder for Mystical Agriculture using OpenComputers.

Uses 1 Computer (SeedC) and 1 Robot (SeedR) with wireless cards.

![Screenshot](images/Layout.png)

Dump Storage/Trash Can infront of the Robot. <br />
Finished seeds to the Left. <br />
To be processed seeds to the Right. <br />
Mechanical Users (Extra Utilites 2) behind the seeds with a Inventory Checker (RFTools) checking for a item and outputting a redstone signal to the conduits (Ender IO) that loops back around to the Mechinical User. <br />

![Screenshot](images/MechanicalUser.png)

Computer using Tier 1 components.<br />
Robot using Tier 2 componets.<br />

For the OpenComputers Adaptor to talk to the Agricraft Computer Controlled Seed Analyzer, I had to download a patched version of AgriCraft and InfinityLib.<br />
These can be obtained from here: ![AgriCraft](https://github.com/josephcsible/AgriCraft/releases)  ![InfinityLib](https://github.com/josephcsible/InfinityLib/releases)<br />
