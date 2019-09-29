# Combat Rules
These are mostly house rules that override the ones in the manual. 

## Autofire
Autofire has the original principle, but different modifiers. For every (starting) five rounds, a range based negative modifier is added. 

| Range  | Burst modifier per five rounds | Difficulty | 5 rounds | 15 rounds | 30 rounds |
| ---    | --- | --- | --- | --- | --- |
| Point blank | -1 | 10 | 11 | 13 | 16 |
| Close | -3 | 15 | 18 | 21 | 33 |
| Medium | -5 | 20 | 25 | 30 | 50 |
| Long | -10 | 25 | 35 | 55 | 85 |
| Extreme | -20 | 30 | 50 | 90 | 150 |

The benefit of burst fire disappears quickly as the amount of rounds and the distance grows. However, it's lethal at point blank, and short bursts remain effective at longer range. Additionally, it causes suppression.

### Autofire hits
```Amount of hits = REF + weapon skill + d10 + weapon accuracy - burst modifier - difficulty```

#### Example
Character with REF 8, Rifle 8, and +1 accuracy weapon fires a burst into an enemy:

| # of Rounds | Point blank | Close | Medium |
| ---         | ---         | --- | --- |
| 5   |  d10+6 hits (max 5) | d10-1 hits (max 5) | d10-8 hits |
| 10  |  d10+5 hits (max 10)| d10-5 hits | d10-13 hits |
| 15  | d10+4 hits   | d10-8 hits | - |
| 30  | d10+1 hits | d10-17 hits | - |

Due to the range modifiers, it is practically pointless to use burst fire beyond close range except to suppress the enemy.

### Suppression Using Autofire
Suppression is an additional effect of autofire. A character can also choose to use autofire to cause suppression, even if they see no targets to engage or have no chance to hit them.

If a character in the area target by suppressive fire, they must pass a COOL check to take any action other than act in cover, find cover, or flee. If they pass the check, and take an action that exposes them, they suffer any hits score by the character laying down suppressive fire before taking their action.

| Weapon | Modifier |
| --- | --- |
| SMG | +1 |
| Rifle | +2 |
| Heavy weapons | +4 |

| Range | Modifier |
| --- | --- |
| Point blank | +1 |
| Close | 0 |
| Medium | -1 |
| Long | -2 |
| Extreme | -3 |

### Suppression check:
```ROF/5*2 + Weapon type + range modifier Vs. COOL + roll```

#### Example
Same character as before, with their rifle, fires suppressing fire to an alleyway. The table shows the number opposing characters must beat to be able to do anything but act in cover, find cover, or flee.

| # of Rounds | Point blank | Close | Medium | Long | Extreme |
| ---         | ---         | ---   | --- | --- | --- |
| 5 | 5 | 4 | 3 | 2 | - |
| 15 | 9 | 8 | 7 | 6 | 5 |
| 30 | 15 | 14 | 13 | 12 | 11 |

| Range | 5 rounds | 15 | 30 |
| --- | --- | --- | --- |
| Point blank | 

## Three Round Burst
With automatic weapons, instead of single fire, player can use the three round burst. Roll to hit as normal, but on a hit, roll to see how many bullets hit the target. All the bullets hit the same body part if at all.

| Range | 3 hits | 2 hits |
| --- | --- | --- |
| Point blank | 2+ | 1+
| Close | 3+ | 2+ |
| Medium | 4+ | 3+ |
| Long | 5+ | 4+ |
| Extreme | 6+ | 5+ |

