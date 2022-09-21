---
description: The tycoon of a winery empire in Mondstadt, unmatched in every possible way.
---

import char from '@site/src/data/characters/Diluc.json'
import { getSkillName } from '@site/src/utils/skill'

# Diluc

<blockquote>{frontMatter.description}</blockquote>

## Resources

* [Diluc: The Dark Side of the Dawn (In-Depth Written Guide)](https://keqingmains.com/diluc/)
* [3 Minute Guide to Diluc](https://www.youtube.com/watch?v=KdBdeGvtyUM)
* [Diluc Mains Discord](https://discord.gg/af9MWyd)

## ![](/assets/element_pyro.png) Diluc

![](/assets/characters/gacha/Diluc.png)

## Base Stats

import CharStatsTable from '@site/src/components/char/CharStatsTable'

<CharStatsTable char={char} />

## Attacks

import Skill from '@site/src/components/char/Skill'

<Tabs>
<TabItem value='na' label={getSkillName(char, 'na')}>
<Skill char={char} skill='na' sectionFilter='Normal Attack' />

| String | Talent 9% | Frames | MV/s | Poise Damage | Impulse Type |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1-Hit | 164.79% | 24 | 411.98%/s | 108.1 | 3 |
| 2-Hit | 161% | 77 | 253.86%/s | 105.57 | 3 |
| 3-Hit | 181.54% | 115 | 264.69%/s | 119.03 | 3 |
| 4-Hit | 246.16% | 181 | 249.78%/s | 161.46 | 6 |

<Skill char={char} skill='na' sectionFilter='Charged Attack' />

| String | Talent 9% | Frames | MV/s | Poise Damage | Impulse Type |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Slash | 126.4% | 30 | 252.8%/s | 60 | 3 |
| Final Slash | 229.1% | 29 | 474%/s | 120 | 6 |

<Skill char={char} skill='na' sectionFilter='Plunging Attack' />

| Damage Type | Talent 9% | Poise Damage | Impulse Type |
| :--- | :--- | :--- | :--- |
| Plunge DMG | 164.44% | 35 | 2 |
| Low Plunge DMG | 328.81% | 150 | 4 |
| High Plunge DMG | 410.7% | 200 | 7 |

</TabItem>

<TabItem value='e' label={getSkillName(char, 'e')}>
<Skill char={char} skill='e' />

| Attribute | Skill (1-Hit) | Skill (2-Hit) | Skill (3-Hit) |
| :--- | :--- | :--- | :--- |
| Skill DMG \(T9%\) | 160.48% | 165.92% | 218.96% |
| MV/s \(T9%\) | 213.97%/s | 191.45%/s | 162.19%/s | 
| Particles | 1~2 \(3:1\) | 1~2 \(3:1\) | 1~2 \(3:1\) | 
| Frames | 45 | 52 | 81 |
| GU | 1A | 1A | 1A |
| ICD | None | None | None | 
| Snapshot | Dynamic | Dynamic | Dynamic |
| Damage Element | Pyro | Pyro | Pyro |
| Damage Type | Skill | Skill | Skill | 
| Cooldown | 10s | - | - |
| Poise Damage | 120 | 120 | 120 |
| Impulse Type | 4 | 5 | 6 |

**Notes**
* The cooldown starts after the first cast.
* Each cast adds a stack to the 4pc Crimson Witch of Flames artifact set.
* When Searing Onslaught hits a frozen target, it will shatter before reacting with any underlying auras.
* Getting frozen in the middle of **Searing Onslaught**'s second attack's animation allows for the skill to be briefly recasted when unfrozen.

</TabItem>

<TabItem value='q' label={getSkillName(char, 'q')}>
<Skill char={char} skill='q' />

| Attribute | Slashing DMG | DoT DMG | Explosion DMG |
| :--- | :--- | :--- | :--- |
| Skill DMG \(T9%\) | 346.8% | 102% | 346.8% |
| MV/s | 413.63%/s | - | - |
| Cast Frames | 145 | - | - |
| Energy Frame | 24 | - | - |
| CD Frame | 16 | - | - |
| GU | 2B | 1A | ? |
| ICD | 5 hits/5s* | 5 hits/5s* | 5 hits/5s* |
| Snapshot | Dynamic | Snapshot | Snapshot |
| Damage Element | Pyro | Pyro | Pyro | 
| Damage Type | Burst | Burst | Burst |
| Energy Cost | 40 | - | - |
| Duration | 12s | - | - |
| CD | 12s | - | - | 
| Poise Damage | Cast: 400 <br/> 1st Part: 100 <br/> 2nd Part: 100 | 100 | 100 |
| Impulse Type | Cast: 3 <br/> 1st Part: 4 <br/> 2nd Part: 5 | Heavy, 900, 0 | 8 |

| Attribute | Field |
| :--- | :--- |
| Infuse GU | 1A |
| Duration | 8s | 

**Notes**
* The ICD for **Dawn** is shared between Slashing DMG, DoT DMG, and Explosions DMG.

</TabItem>
</Tabs>

## Ascension Passives

import Passive from '@site/src/components/char/Passive'

<Tabs>
<TabItem value='passive' label='Passive'>
<Passive char={char} passive={2} />
</TabItem>

<TabItem value='a1' label='Ascension 1'>
<Passive char={char} passive={0} />
</TabItem>

<TabItem value='a4' label='Ascension 4'>
<Passive char={char} passive={1} />

**Note**
* The Pyro DMG Bonus is also applied to **Dawn**'s Slashing, DoT, and Explosion DMG.

</TabItem>
</Tabs>

## Constellations

import ConstellationsFull from '@site/src/components/char/ConstellationsFull'

<ConstellationsFull char={char} />


## Full Talent Values

import TalentsFull from '@site/src/components/char/TalentsFull'

<TalentsFull char={char} />

## Evidence Vault

<Card item={require('../../evidence/characters/pyro/diluc.md')} />
