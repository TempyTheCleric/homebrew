---
title: Sandstep
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
> # Sandstep
>> *Fey Boon bestowed by Marisol Everspring*
>> Current Owner: Dominga
> ----------------------------
> Whenever Dominga casts a spell of 1st level or higher, she may also teleport — no action required — to an unoccupied space she can see within 60 feet of her current location. This teleport happens after the spell resolves, at her choice, whether or not the spell takes effect, and doesn't require the spell to target the destination in any way. She doesn't simply vanish and reappear — she sinks half a step into loose pink sand that spills from nowhere and closes over her, then rises the same way at her destination.


# Sandstep

A personal boon, not a physical item — a mark of Dominga's growing fey nature as she steps into her role as the [[The Sand Gardens|Sand Gardens]]' new archfey.

### Effect

Whenever Dominga casts a spell of 1st level or higher, she may also teleport — no action required — to an unoccupied space she can see within 60 feet of her current location. This teleport happens after the spell resolves, at her choice, whether or not the spell takes effect, and doesn't require the spell to target the destination in any way.

She doesn't simply vanish and reappear — she sinks half a step into loose pink sand that spills from nowhere and closes over her, then rises the same way at her destination.

### Origin

Granted alongside the [[Pink Pinchglass]] in the same dream, as [[Dominga]] learned the truth of the Sand Gardens' origin and her place in it.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
