---
title: Pinchglass
aliases:
type: Item
type2:
  - Wondrous Item
tags:
  - "#item"
  - "#magicItem"
icon: liWand
campaign:
  - "[[Out of the Abyss]]"
procurement: Gifted by Marisol Everspring
rarity: Artifact
weight: 0.01 lbs
attunement:
authority:
  - Dominga
description: |-
  A slim crystal vial, no longer than a finger, shaped like an hourglass but with no way to turn it — the sand only ever falls one direction, and never runs out on its own. Inside is a shifting store of pink sand from The Sand Gardens.

  The vial holds a maximum of 3 pinches of sand and begins full.

  Using a Pinch. As part of casting a spell, you can expend one pinch of sand to cover the gold cost of all of that spell's material components, regardless of their value.

  Regaining Sand. At each dawn, if the vial holds at least 1 pinch, it regains 1d4 − 1 pinches (minimum 0), up to its maximum of 3.

  Dormancy. If the vial is ever emptied of all pinches, it goes dormant and its regeneration pauses entirely. At each dawn while dormant, roll a d6: on a 5 or 6, the vial wakes and regains its full 3 pinches. Otherwise, it remains dormant and empty.
share: true
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
> # Pinchglass
>> Wondrous Item, Artifact
>> *Vial*
>> 0.01 lbs
>> Current Owner: `=this.authority`
> ----------------------------
> A slim crystal vial, no longer than a finger, shaped like an hourglass but with no way to turn it — the sand only ever falls one direction, and never runs out on its own. Inside is a shifting store of pink sand from [[The Sand Gardens]]. The vial holds a maximum of **3 pinches** of sand and begins full.
> 
> **Using a Pinch.** As part of casting a spell, you can expend one pinch of sand to cover the gold cost of all of that spell's material components, regardless of their value.
> 
> **Regaining Sand.** At each dawn, if the vial holds at least 1 pinch, it regains 1d4 − 1 pinches (minimum 0), up to its maximum of 3.
> 
> **Dormancy.** If the vial is ever emptied of all pinches, it goes dormant and its regeneration pauses entirely. At each dawn while dormant, roll a d6: on a 5 or 6, the vial wakes and regains its full 3 pinches. Otherwise, it remains dormant and empty.




# Pink Pinchglass

A slim crystal vial, no longer than a finger, shaped like an hourglass but with no way to turn it — the sand only ever falls one direction, and never runs out on its own. Inside is a shifting store of pink sand from [[The Sand Gardens]].

### Properties

The vial holds a maximum of **3 pinches** of sand and begins full.

**Using a Pinch.** As part of casting a spell, you can expend one pinch of sand to cover the gold cost of all of that spell's material components, regardless of their value.

**Regaining Sand.** At each dawn, if the vial holds at least 1 pinch, it regains 1d4 − 1 pinches (minimum 0), up to its maximum of 3.

**Dormancy.** If the vial is ever emptied of all pinches, it goes dormant and its regeneration pauses entirely. At each dawn while dormant, roll a d6: on a 5 or 6, the vial wakes and regains its full 3 pinches. Otherwise, it remains dormant and empty.

### Origin

Passed down alongside the mantle of the Sand Gardens' archfey — a token of stewardship as much as a tool. The sand inside is drawn from the Well of Creation itself, and its slow, uncertain replenishment mirrors the Gardens' own nature: generous, but never to be taken for granted.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
