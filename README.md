From baseline filter:

#BIS Bases
> Highlight all the bases you need for endgame, change depending on character and build.

#Shields
Swap Class "Shield" to "Buckler" or "Foci" or "Sceptres" , if need a different offhand

Adjust these values for Armour, Evasion, ES Bases, (0 means the gear should have 0 of that value)

#Sample for ES/EVA Bases
	BaseEnergyShield > 0
	BaseEvasion > 0
	BaseArmour 0

#Sample for Armour Bases
	BaseEnergyShield 0
	BaseEvasion 0
	BaseArmour > 0

#Change weapon type depending on what you need, swap to any of the following:
#1H
Class == "One Hand Maces" "Sceptres" "Spears" "Wands" "Quivers"
#2H
Class == "Bows" "Crossbows" "Quarterstaves" "Staves" "Talismans" "Two Hand Maces"	

Default:
Show #Change to weapon type you need
	Class == "Spears"
