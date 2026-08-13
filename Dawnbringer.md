---
title: Dawnbringer
aliases:
type: Item
type2:
  - Weapon
tags:
  - item
  - "#magicItem"
  - needs-review
icon: liWand
campaign:
  - "[[Out of the Abyss]]"
procurement: Gifted by The Duchess
rarity: Legendary
weight:
attunement: attunement required
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
> # Dawnbringer
>> `=this.type`, `=this.rarity`
>> *`=this.type2`*
>> `=this.value`,`=this.weight` 
>> `=this.bonus` 
>> Current Owner: `=this.authority`
> ----------------------------
> `=this.description`



# Dawnbringer

A radiant, sonic-edged blade that seems to hum with a low, resonant chord whenever drawn — as though it is always mid-note. Its hilt is wrapped in something that never tarnishes, warm to the touch even in the cold of the Underdark.

### Sentience

Dawnbringer is a **sentient weapon**. Exact ability scores, alignment, and communication method are unconfirmed (`#needs-review`) — she was gifted to [[Dominga]] by **[[The Duchess]]** at the [[Araumycos]] battlefield in [[Session 51 Notes|Session 51]]/[[Session 52 Notes|Session 52]], and is bonded closely enough to Dominga to react emotionally through their connection (she "panicked" sensing danger to [[Thavian]] while he wielded her — see Session 52).

### Personality

Protective and emotionally reactive to the people she's bonded with rather than coldly dutiful. In Session 52, Dominga consciously released her own claim so Dawnbringer could be passed to Thavian for the killing blow against [[Juiblex]] — Dawnbringer allowed it, suggesting she recognizes chosen loyalty/trust over strict possession (thematically mirroring the session's "not yours" throughline). Full personality, purpose, and any special properties beyond radiant/sonic damage still TBD.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` |

> [!dmsecret]- Secret
> Who is The Duchess, and why did she have a sentient sword to give away? TBD.
