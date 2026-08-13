---
title: Vile of Deva's Ichor
aliases:
  - Deva's Blood
type: Item
type2:
  - Potion
tags:
  - item
  - "#magicItem"
icon: liWand
description: |-
  Painfully bright liquid light swirls inside a hollowed out crystal. The crystal is thin and fragile and dissolves easily as if made of sugar.

  When eaten regain 40hp and remove one curse.

  If fed to a fiend or undead, they instead take 80 radiant damage. Attempting to feed a creature who is hostile towards you uses grappling mechanics.
campaign:
  - "[[Out of the Abyss]]"
rarity: Very Rare
weight: 0.01 lbs
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


> [!statblocks|left] ^itemvileofdevasichor
> 
> # Vile of Deva's Ichor
>> `=this.type`, `=this.rarity`
>> *`=this.type2`*
>> `=this.weight` 
>> Current Owner: `=this.authority`
> ----------------------------
> `=this.description`


# Vile of Deva's Ichor

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
