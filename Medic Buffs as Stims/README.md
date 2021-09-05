This modification creates schematics for medics to be able to craft their medic buffs as stims.

This A. Gives something for medics to craft and sell. B. Reduces the need for AFK Buff bots.

You will need to do the following on your own:

You will need to add these schematics to a schematic group in schematic_group.tab
object/draft_schematic/chemistry/item_medic_constitution.iff

object/draft_schematic/chemistry/item_medic_action.iff

object/draft_schematic/chemistry/item_medic_strength.iff

object/draft_schematic/chemistry/item_medic_agility.iff

object/draft_schematic/chemistry/item_medic_precision.iff

object/draft_schematic/chemistry/item_medic_block.iff

object/draft_schematic/chemistry/item_medic_dodge.iff

You will then need to add the name of the schematic group that you put these in skills.tab.

You can choose to add these somewhere in the medic profession wheel or you can add it as a new expertise box.


Optionally: You can adjust the length of the buffs in buff.tab since this uses the existing medic buffs from there, just be aware that you made need to tweak other skills that also change the duration of the buffs.
