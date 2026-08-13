---
title: Prayer Beads of Grace
aliases:
type: Item
type2:
  - Wondrous Item
tags:
  - item
  - "#magicItem"
icon: liWand
description: |-
  A simple necklace with stone beads faintly humming with divine resonance. This necklace only has 3 beads left.
  As a bonus action or reaction, expend a bead to gain advantage on one attack, save, or ability check. If you use this to aid another creature, you both gain the advantage.
campaign:
  - "[[Out of the Abyss]]"
rarity: Very Rare
weight: 0.2 lbs
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
> |**Weight**|`INPUT[text:weight]`|
> |**Attunement**|`INPUT[toggle(offValue(none), onValue(attunement required)):attunement]`|
> |**Bonus**|`INPUT[text:bonus]`|
> |**Deity**|`INPUT[inlineListSuggester(optionQuery(#deity AND !"z_Templates"), useLinks(partial)):deity]`|
> |**Organizations**|`INPUT[inlineListSuggester(optionQuery(#organization AND !"z_Templates"), useLinks(partial)):organizations]`|
> |**Owner/Leader/Ruler**|`INPUT[inlineListSuggester(optionQuery(#organization OR #character OR #location AND !"z_Templates"), useLinks(partial)):authority]`|
>|**Hooks**| `INPUT[inlineListSuggester(optionQuery(#quest OR #plot OR #secret OR #adventure OR #lore OR #rumor), useLinks(partial)):hooks]`


> [!statblocks|left] ^itemprayerbeadsofgrace
> 
> # Prayer Beads of Grace
>> `=this.type`, `=this.rarity`
>> *`=this.type2`*
>>`=this.weight` 
>> Current Owner: `=this.authority`
> ----------------------------
> `=this.description`


# Prayer Beads of Grace

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 

