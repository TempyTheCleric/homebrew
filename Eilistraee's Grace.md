---
title: Eilistraee's Grace
aliases:
  - Divine Intervention
type: Item
type2:
  - Divine Boon
tags:
  - item
  - "#magicItem"
icon: liWand
campaign:
  - "[[Out of the Abyss]]"
procurement: Granted by Eilistraee herself in a level-up dream, in recognition of Kay's own act of faith becoming her Champion
rarity: Boon
weight: —
attunement: none
authority:
  - Kay
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
> # Eilistraee's Grace
>> *`=this.type2` granted by Eilistraee* 
>> Current Owner: `=this.authority`
> ----------------------------
> Once per long rest, as a bonus action, Kay may call out to Eilistraee by name. Roll a d20 — on a **16 or higher**, the Dark Maiden answers, and together the player and DM narrate how her grace enters the fight: a flash of moonlight blinding a foe, an opening that wasn't there a second before, courage steadying an ally's blade, or whatever the moment calls for.
> 
> Even when the moon stays quiet, Kay's faith isn't wasted — she's just fighting this one herself, the way Eilistraee believes her capable of.


# Eilistraee's Grace

A personal boon, not a physical item — a standing bond between Kay and [[Eilistraee]], granted in a dream where the Dark Maiden spoke to her directly for the first time.

### Effect

Once per long rest, as a bonus action, Kay may call out to Eilistraee by name. Roll a d20 — on a **16 or higher**, the Dark Maiden answers, and together the player and DM narrate how her grace enters the fight: a flash of moonlight blinding a foe, an opening that wasn't there a second before, courage steadying an ally's blade, or whatever the moment calls for.

Even when the moon stays quiet, Kay's faith isn't wasted — she's just fighting this one herself, the way Eilistraee taught her she could.

### Origin

> [!quote] Eilistraee
> "I saw you Kay, your fight, your struggle — you chose the moon over the darkness all on your own. You becoming my champion was not just the act of a wish, it was your act of genuine, beautiful faith in me. And I want you to know, that I have faith in you."

Granted alongside [[Moon Wings]] in the same dream, where Eilistraee also named Jimjar, the current steward of [[Acorith]], and Jarlaxle Baenre's presence there awaiting the party before the summit.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
