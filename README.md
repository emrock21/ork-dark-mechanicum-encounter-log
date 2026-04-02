# Ork Dark Mechanicum Encounter Log

An on-chain ledger of Ork descriptions of encounters with Dark Mechanicum  
forges, heretek covens, daemon engines, corrupted manufactorums, and other  
spiky machine-worshippin' gitz.

Each entry uses a short 3‑line format describing how da metal monsters acted  
and how da scrap ended. The community votes whether the encounter was  
**WAAAGH-approved** or **not proppa'.**

---

## Contract

Deployed on Base:  
`0xe24acb3893510A60A39D3F8D47Ea5E0E2D655461`  
https://basescan.org/address/0xe24acb3893510a60a39d3f8d47ea5e0e2d655461#code

Main file: `contracts/DarkMechanicumEncounterLog.sol`

---

## Example encounter

```solidity
recordEncounter(
  "Daemon Forge of Skarvex-9",
  "Da big metal beasties clanked around chantin' binharic like angry squigs speakin' backwards.",
  "Da scrap ended wiv sparks, smoke, an' da boyz swearin' one of da engines tried to bite a trukk."
);

Voting
voteEncounter(1, true);   // WAAAGH-approved
voteEncounter(1, false);  // Not proppa'

Closing Note
A chronicle of mad hereteks, daemon engines,
an' machines dat definitely weren't built by humies wiv all dere screws tight.
