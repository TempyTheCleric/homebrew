---
title: Silvertongue's Finery
aliases:
  - Regal Garments of the Antiquarian
type: Item
type2:
  - Wondrous Item
tags:
  - item
  - "#magicItem"
icon: liWand
campaign:
  - "[[Out of the Abyss]]"
procurement: Granted by Tymora during Thavian's level-up dream
rarity: Legendary
weight: 3 lbs
attunement: attunement required
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
> # Silvertongue's Finery
>> `=this.type`, `=this.rarity`
>> *`=this.type2`*
>> Current Owner: `=this.authority`
> ----------------------------
> A fine gentleman's suit that matches any occasion — spotless without effort, tailored to a perfect fit no matter how Thavian's build changes, and cut in a style that shifts to suit wherever he's standing. He can also will the change himself at any time. The richness of the fabric and craftsmanship visibly tracks his reputation in the world.
> 
> While worn, Thavian's base AC is 19 (this does not stack with worn armor).
> 
> Once per long rest, Thavian can force one Charisma check, his own or a creature he can see, to succeed or fail outright, no roll required.
> 
> He has advantage on Constitution saving throws made to maintain concentration on a spell while wearing the garments.
> 
> Thavian can sense whenever a creature within 60 feet casts a spell from the illusion school, or a spell that forces a target to make a Charisma saving throw, and can pinpoint the direction and location of the caster, even if the caster is invisible or otherwise hidden, without needing an action to do so. This doesn't reveal the caster's identity, only where the magic is coming from.


# Silvertongue's Finery

A fine gentleman's suit that matches any occasion — spotless without effort, tailored to a perfect fit no matter how Thavian's build changes, and cut in a style that shifts to suit wherever he's standing. He can also will the change himself at any time. The richness of the fabric and craftsmanship visibly tracks his reputation in the world — modest and sharp when he was still an unknown schemer, steadily more resplendent as his name as a talker, a broker, and a face has spread.

### Properties

While worn, Thavian's base AC is 19 (this does not stack with worn armor).

Once per long rest, Thavian can force one Charisma check — his own or a creature he can see — to succeed or fail outright, no roll required.

He has advantage on Constitution saving throws made to maintain concentration on a spell while wearing the garments.

Thavian can sense whenever a creature within 60 feet casts a spell from the illusion school, or a spell that forces a target to make a Charisma saving throw, and can pinpoint the direction and location of the caster — even if the caster is invisible or otherwise hidden — without needing an action to do so. This doesn't reveal the caster's identity, only where the magic is coming from.

### Origin

Granted by [[Tymora]] during a level-up dream, alongside [[Appraiser's Eye]] — a gift befitting a man who has built himself a reputation as a face, a talker, and a broker of secrets.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
