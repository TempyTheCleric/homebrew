---
title: Unbreaking
aliases:
type: Item
type2:
  - Divine Boon
tags:
  - item
  - "#magicItem"
icon: liWand
campaign:
  - "[[Out of the Abyss]]"
procurement: Won from Tymora in a wager during Thavian's level-up dream, forged from what he survived of Zuggtmoy's madness
rarity: Boon
weight: —
attunement: none
authority:
  - Thavian
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
> # Unbreaking
>> *`=this.type2` granted by Tymora* 
>> Current Owner: `=this.authority`
> ----------------------------
> Thavian is immune to indefinite madness caused by a demon lord.
> 
> He has advantage on all saving throws against any effect that would inflict madness, regardless of its source.
> 
> Once per long rest, Thavian can call on what he survived to shield his entire party — for 1 minute, every creature of his choice that he can see within 60 feet becomes immune to madness effects, regardless of source. This can be triggered as a reaction, the instant before an effect would take hold, or proactively at the start of a fight he knows is coming.




# Unbreaking

A personal boon, not a physical item — what survived of Zuggtmoy's madness inside Thavian, hardened by Tymora into a shield rather than left to fester as a wound.

### Effect

Thavian is immune to indefinite madness caused by a demon lord.

He has advantage on all saving throws against any effect that would inflict madness, regardless of its source.

Once per long rest, Thavian can call on what he survived to shield his entire party — for 1 minute, every creature of his choice that he can see within 60 feet becomes immune to madness effects, regardless of source. This can be triggered as a reaction, the instant before an effect would take hold, or proactively at the start of a fight he knows is coming.

### Origin

Won from [[Tymora]] in a wager during Thavian's level-up dream — the same dream that began with him reliving what Zuggtmoy's death-curse did to him, before Tymora broke through the memory to reach him.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
