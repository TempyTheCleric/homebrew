---
title: Appraiser's Eye
aliases:
type: Item
type2:
  - Wondrous Item
tags:
  - item
  - "#magicItem"
icon: liWand
campaign:
  - "[[Out of the Abyss]]"
procurement: Granted by Tymora during Thavian's level-up dream, in place of the eye lost to Zuggtmoy's dying curse
rarity: Rare
weight: negligible
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
> # Appraiser's Eye
>> `=this.type`, `=this.rarity`
>> *`=this.type2`*
>> Current Owner: `=this.authority`
> ----------------------------
> A golden sphere the size of an eyeball, its iris bejeweled and faintly warm. The eye has 3 charges and regains 1d3 expended charges daily at dawn.
> 
> Thavian can use an action to expend 1 charge to cast *identify* from it. He can also use the eye as the material component required for *legend lore* — each time, there is a flat 10 percent chance the sphere's ability to cast legend lore is consumed is consumed. If this happens the eye can still be used to function as a normal eye, and as a means of casting *identify*
> 
> Thavian always has advantage on Intelligence checks made to determine an item's value, and on Wisdom (Perception) checks that rely on sight.



# Appraiser's Eye

A golden sphere the size of an eyeball, its iris bejeweled and faintly warm. No attunement is required to use it — it functions freely in Thavian's hand or socket alike.

### Properties

The eye has 3 charges and regains 1d3 expended charges daily at dawn.

While holding the eye, Thavian can use an action to expend 1 charge to cast *identify* from it. He can also use the eye as the material component required for *legend lore* — each time, there is a flat 10 percent chance the sphere is consumed by the spell (this chance does not increase with repeated use).

Thavian always has advantage on Intelligence checks made to determine an item's value, and on Wisdom (Perception) checks that rely on sight.

### Origin

Granted by [[Tymora]] during Thavian's level-up dream, alongside [[Regal Garments of the Antiquarian]] — a replacement for the eye Zuggtmoy's dying curse took from him, turned from a demon lord's last cruelty into one of Lady Luck's gifts.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
