---
title: Moon Wings
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
procurement: Granted by Eilistraee
rarity: Boon
weight: —
attunement: none
authority:
  - Kay
deity:
  - "[[Eilistraee]]"
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
> # Moon Wings
>> *`=this.type2` granted by Eilistraee*
>> Current Owner: `=this.authority`
> ----------------------------
> As a bonus action, Kay may speak the command word **"Wax"** to manifest the wings. While active:
>  - Kay gains a flying speed equal to her walking speed.
>  - The wings shed dim light in a 10-foot radius, but it's a divine gift rather than a mundane glow — it doesn't reveal her to hostile creatures or impose any penalty on her Stealth checks
>  - If Kay is knocked unconscious, the wings vanish immediately
>  - To dismiss the wings you must speak the command word **Wane**.
>  - If the wings end while Kay is airborne due to her being knocked unconsciousness — they spend themselves in one last pulse of moonlight, easing her gently to the ground. She takes no fall damage.
> 
>  Once the wings end, they can't be summoned again until Kay finishes a long rest.



# Moon Wings

A personal boon, not a physical item — twin wings of silver moonlight that Kay can call from her own shoulders (sometimes drawn visibly out of her shadow) at [[Eilistraee]]'s gift.

### Effect

As a bonus action, Kay may speak the command word **"Wax"** to manifest the wings. While active:

- Kay gains a flying speed equal to her walking speed.
- The wings shed dim light in a 10-foot radius, but it's a divine gift rather than a mundane glow — it doesn't reveal her to hostile creatures or impose any penalty on her Stealth checks.
- If Kay is knocked unconscious, the wings vanish immediately.
- If the wings end while Kay is airborne — dismissed (command word **"Wane"**), expired, or cut short by unconsciousness — they spend themselves in one last pulse of moonlight, easing her gently to the ground. She takes no fall damage, even if she's out cold on the way down.

Once the wings end, they can't be summoned again until Kay finishes a long rest.

### Origin

Granted alongside [[Eilistraee's Grace]] in the same dream — Eilistraee named Kay's want to reclaim her moon scythes from the Demonweb Pits before Kay ever said it aloud, and gave her the wings specifically as the means to go get them.

## Notes
 |
---|---|
**Owner** | `=this.authority` |
**Location** | `=this.location` |
**Procurement** | `=this.procurement` | 
