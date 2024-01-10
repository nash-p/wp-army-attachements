All rights, ownership, and credits belong to the original mod author WhiskeyPotato

Changes:
    - Updated to 3.10.*
    - Attachments are now available for the General subclass only, not all commanders
        Sadly this requires Paragons DLC for the subclasses, will try to find a non-DLC implementation
    - Attachments are tiered to be in line with their effects

There are other changes not listed here, 
all in all I have tried to keep things in line with the original author's 'ethos'.

### [RESTYLED] ###
My intention here is to streamline a few traits in this mod. Rather than having each attachement stand alone equally they will now be upgrades of each other, like vanilla traits.
Summary of intended changes:
    - Attachements will now become like support companies
    - Each general should have something like max 5 support companies, one from each 'type'
    - Some support companies will be upgrades of others going up tiers, e.g, Combat Software 1.0 and 2.0
    - All of this should be possible with inline scripts
    - Some lore/description editing to be more... in tune

Changelog:
    - Infrastructure changed to Defenses, reworked all traits here


## NEW TRAIT CHAINS/UPGRADES ##

# Design Principles:
    -- Create a table of x number of rows (=> 3), corresponding to each 'tree/line'
    -- y number of rows (=> 3), composed of all the possible army_modifiers -1
    -- each cell on the same row must have a unique number ranging -2 - +2
    -- there must be 1 column where all cell values are either all positive or all negative

# DEFENSES [12 Total]
(Can pick either two static or two mobile, no mixing)
-- Coilgun Batteries > Autocannon CIWS > Heavy AA Batteries         [Normal disengage, increase health, reduce damage, alloy upkeep(+motes)]
-- Neocrete Bunkers > Durasteel Bastions > Living Metal Redoubts    [Reduced disengage, greatly increase health, slightly reduced damage, mineral upkeep(+living metal)]

-- Portable Defelctors > Ion Projectors > Mobile Zroshield Units    [Normal disengage, greatly increase health, moderately reduced damage, energy upkeep(+zro)]
-- Laser Grids > Low Orbit X-Rays > Particle Beam Arrays            [Reduced disengage, increase health, normal damage, energy upkeep(+crystals)]


# EQUIPMENT
- Power armor > Nerve Armor > Living Armor
- Comb. Software 1.1 > Cybernetic > Combat Software 2.0 [CYBER/SYNTH]
- Flamer > Chemical > Nuke

# BEASTS
- Canines > Mut Horde > Xenocav [GENE]
- Worms > Therapods

# REINFORCEMENTS
- MP > Commissars
- Hypno > Suicide
- Commando > Specops > Shadow Ass
- Gene shock > Void Walkers [GENE]
- !NEW! Psi shield > Psi warrior > TK > Class A [PSI]

# VEHICLES
- Dropships > Drop pods
- Strider > Mech > Armageddon
- Hover tank > ATV
-- TODO: ATV > Tank
- Plasma plane > Speeder
-- TODO: Speeder > Plane