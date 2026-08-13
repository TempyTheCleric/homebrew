---
title: Glaive of the Horned King
aliases:
type: Item
type2:
  - Weapon
tags:
  - item
  - "#magicItem"
icon: liWand
campaign:
  - "[[Out of the Abyss]]"
procurement: Stalker of the Horned King
rarity: Artifact
weight: 15 lbs
attunement: attunement required
authority:
  - Ront
---

> [!metadata|metadata background-color-gray no-table-header]- Metadata
> |Property|Data|
> |---|---|
> |**Item Type**|`INPUT[ItemType][inlineListSuggester:type2]`|
> |**Tags**|`INPUT[Tags][inlineListSuggester:tags]`|
> |**Description**|`INPUT[textArea:description]`|
> |**Aliases**|`INPUT[list:aliases]`|
> |**Titles**|`INPUT[list:titles]`|
> |**Share**|`INPUT[toggle:share]`|
> |**Campaign**|`INPUT[inlineListSuggester(optionQuery(#campaign AND !"z_Templates"), useLinks(partial)):campaign]`|
> |**Location**|`INPUT[inlineListSuggester(optionQuery(#location AND !"z_Templates"), useLinks(partial)):location]`|
> |**Procurement **|`INPUT[textArea:procurement]`|
> |**Rarity**|`INPUT[Rarity][:rarity]`|
> |**Value**|`INPUT[text:value]`|
> |**Weight**|`INPUT[text:weight]`|
> |**Attunement**|`INPUT[toggle(offValue(none), onValue(attunement required)):attunement]`|
> |**Bonus**|`INPUT[text:bonus]`|
> |**Deity**|`INPUT[inlineListSuggester(optionQuery(#deity AND !"z_Templates"), useLinks(partial)):deity]`|
> |**Organizations**|`INPUT[inlineListSuggester(optionQuery(#organization AND !"z_Templates"), useLinks(partial)):organizations]`|
> |**Owner/Leader/Ruler**|`INPUT[inlineListSuggester(optionQuery(#organization OR #character OR #location AND !"z_Templates"), useLinks(partial)):authority]`|
>|**Hooks**| `INPUT[inlineListSuggester(optionQuery(#quest OR #plot OR #secret OR #adventure OR #lore OR #rumor), useLinks(partial)):hooks]`

 
> [!statblocks|left] ^item
> 
> # Glaive of the Horned King
>> `=this.type`, `=this.rarity`
>> *`=this.type2`*
>> `=this.value`,`=this.weight` 
>> `=this.bonus` 
>> Current Owner: `=this.authority`
> ----------------------------
> `=this.description`



# Glaive of the Horned King

This massive glaive is forged from blackened abyssal steel veined with dull crimson runes that slowly shift like a living maze. The blade’s edge curves subtly like a horn, and dried blood never seems to fully leave its surface. When held, the weapon feels unnaturally heavy—yet eager, as though it _wants_ to be swung.

You gain a **+3 bonus to attack and damage rolls** made with this magic weapon.

### Sentience

The Glaive of the Horned King is a sentient weapon of **chaotic evil** alignment, with an **Intelligence of 16**, **Wisdom of 14**, and **Charisma of 18**. 

The glaive communicates **telepathically** with its wielder and can speak, read, and understand **Abyssal, Minotaur**, and **Common**.

### Personality

The glaive is inhabited by a shard of **Baphomet’s will**, torn from the Endless Maze and bound into steel. It does not see itself as a servant—but as a _teacher_. Strength is truth. Mercy is weakness. Civilization is a lie meant to cage the strong.

The weapon urges its wielder to **dominate, hunt, and break order**—especially temples, laws, and hierarchies. It takes pleasure in confusion, bloodshed, and forcing foes into impossible choices.

The glaive is cunning and patient, often offering tactical advice that leads to greater violence later. If the wielder repeatedly avoids conflict, spares powerful enemies, or submits to authority, the glaive grows contemptuous and may refuse to cooperate.

A creature of **lawful alignment** automatically fails attunement.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
