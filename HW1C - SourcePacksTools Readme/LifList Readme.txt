CnlPepper Weapons Mod V2 PSD files:
-----------------------------------

For all you modders out there here are the PSD files for my weapon textures.

I have included the directory structure for use with liflist in the file. Don't forget to delete the file called null in the data\etg\textures\bullet dir, it is just to force winzip to keep the directory structure.

Assuming you have the following directory structure follow these install instructions:

<dir>ROOT
   -liflist.exe
   -<dir> data
      -Textures.ll  <------------------ From the homeworld dir.
      -<dir> etg
         -<dir> textures  
            -<dir> bullets
   -<dir> datasrc
      -weapons.mif
      -<dir> etg
         -<dir> textures
         -[TEXTURE FILES]  
            -<dir> bullets
               -[TEXTURE FILES]

From the root dir the command to add the weapon textures is

   liflist Q data\textures.ll datasrc\weapons.mif

This will convert the PSDs to lifs and add the textures to the texture.ll database in <dir> data. Copy the directories and the textures.ll file from the data dir into the homeworld directory.

CnlPepper

Contact details are on my website http://www.geocities.com/cnlpepper

The weapon modifications are as follows:

Beam Weapons-

GS_VeryLargeIonCannon = EA/Narn Laser 
GS_LargeIonCannon = Minbari Neutron Beam 
GS_MediumIonCannon = Shadow Fusion Beam 
GS_SmallIonCannon = Vorlon Lightning Beam 
GS_Laser = Minbari Fighter Neutron Beam (Smaller Version of GS_LargeIonCannon) 
GS_MediumProjectile = Drakh Fighter Beam (Use this like any ordinary GS_### Beam type) 
Energy/Projectile Cannons-

GS_VeryLargePlasmaBomb = Omega/Midwinter Heavy Pulse Cannon (Large Yellow-White) 
GS_LargePlasmaBomb = B5/Hyperion Projectile Cannons (Large Blue) 
GS_MediumPlasmaBomb = Narn/Centauri Ion Cannon (Medium Red) 
GS_SmallPlasmaBomb = B5/Alpha Heavy Plasma Cannon (Large Green) 
GS_VeryLargeEnergyCannon = Starfury Pulse Cannon (Small Blue) 
GS_LargeEnergyCannon = Thunderbolt Pulse Cannon (Small Yellow-White) 
GS_MediumEnergyCannon = B5/Omega Particle Array (Small Orange-Yellow) 
GS_SmallEnergyCannon = Shadow/Whitestar Discharge Cannons (Small-Medium Purple)
