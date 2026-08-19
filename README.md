# RekMOD
Mod based on recreating Lekmod, a multiplayer mod for civ 5
You can find many of the changes or attempted changes in this mod here:
https://docs.google.com/document/d/18tsjg2C1wKA7I41GktDRr6R83eUrhn4FHi9EUEtpKvI/edit?usp=sharing

# RekMOD-iron
Fork Rekmod with changes for the multiplayer games

#### General Changes
- NEW Multiplayer speed (scienceCostModifier and cultureCostModifier 0.50/0.50)
- NEW Solo speed (scienceCostModifier and cultureCostModifier 0.50/0.50), use it for solo games.

- Project Utopia 30 -> 36
- removed barbarian bonus on King+
- rebalance strategic resources
- `minimumWorldLuxuries*` ModConstants (requires Unciv https://github.com/yairm210/Unciv/pull/15267 — do not merge until that Unciv PR lands): world luxury floors 35/60/60/88/112 by map size
- City-states settle first city in place: Unciv default since https://github.com/yairm210/Unciv/pull/15268 (no Iron ModOptions unique; do NOT add `City-states search for first city location` — that is the opt-out)
- fixed startBias for Vietnam, Armenia, Aztecs, Israel, Iroqez, Canada, Ukraine, Finland, Hitties, Sweden
- Disabled belief "Just war"
- Maritime city-states: `Start bias [Coast]` on CityStateType (requires Unciv ≥4.21.4 / #15271)

#### Building Changes
- Hanse 25% -> 10%
- BMPC Plant requires improved resource, provides 4 Oil
- Constabulary / Convict Penitentiary: `Spies in [in this city] cities act as though they have [+1] levels for [Counter-intelligence]`
