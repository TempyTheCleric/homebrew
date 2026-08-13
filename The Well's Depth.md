---
title: The Well's Depth
aliases:
type: Item
type2:
  - Fey Boon
tags:
  - item
  - "#magicItem"
icon: liWand
campaign:
  - "[[Out of the Abyss]]"
procurement: Granted during Dominga's level-up dream, as she inherited stewardship of the Sand Gardens
rarity: Boon
weight: —
attunement: none
authority:
  - Dominga
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
> # The Well's Depth
>> *`=this.type2` bestowed by Marisol Everspring*
>> Current Owner: `=this.authority`
> ----------------------------
> Dominga's Intelligence score is increased by 2 and can now be increased above 20 through normal means (Ability Score Improvements, magic items, and so on), up to a maximum of 30.



# The Well's Depth

A personal boon, not a physical item — Dominga's mind deepening alongside the domain she now stewards.

### Effect

Dominga's Intelligence score can now be increased above 20 through normal means (Ability Score Improvements, magic items, and so on), up to a maximum of 30.

### Origin

Granted during Dominga's level-up dream, alongside [[Sandstep]] and the [[Pink Pinchglass]], as she learned the truth of the Sand Gardens' origin and her place in it.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
