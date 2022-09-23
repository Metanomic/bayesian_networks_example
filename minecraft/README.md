# Minecraft | Thunderstruck Tables & Bayesian Chains

## Classifications:
- Farmers
- Killers
- Scientists

<br />
Sum of users per Classification
<br />
<div align="center">
  <a href="https://github.com/Metanomic/bayesian_networks_example">
    <img src="images/sum_of_players_type.png" alt="Logo" width="937" height="401">
  </a>
</div>

<br />
Classification of users per XP Level
<br />
<div align="center">
  <a href="https://github.com/Metanomic/bayesian_networks_example">
    <img src="images/minecraft_table.png" alt="Logo" width="1003" height="497">
  </a>
</div>

## Farmer Event Chain
Paths:
1. "canBeSteered" --> "isInLove" --> "procreate"
2. "addRecipesTool" --> "procreate"
3. "fall" -- > "procreate"
<br />
<div align="center">
  <a href="https://github.com/Metanomic/bayesian_networks_example">
    <img src="images/farmer_chain.png" alt="Logo" width="789" height="630">
  </a>
</div>

## Killer Event Chain
Paths:
1. "getEntityToAttack" --> "findPlayerToAttack" --> "onKillEntity"
2. "fall" --> "onKillEntity"
3. "doesContainerItemLeaveCraftingGrid" --> "onKillEntity"
<br />
<div align="center">
  <a href="https://github.com/Metanomic/bayesian_networks_example">
    <img src="images/killer_chain.png" alt="Logo" width="789" height="630">
  </a>
</div>

## Scientist Event Chain
Paths:
1. "initCraftableStats" --> "getCraftingResult"
2. "doesContainerItemLeaveCraftingGrid" --> "getCraftingResult"
3. "fall" --> "getCraftingResult"
<br />
<div align="center">
  <a href="https://github.com/Metanomic/bayesian_networks_example">
    <img src="images/scientist_chain.png" alt="Logo" width="789" height="630">
  </a>
</div>

## Farmers Table

<br />
<div align="center">
  <a href="https://github.com/Metanomic/bayesian_networks_example">
    <img src="images/farmers_table.png" alt="Logo" width="594" height="852">
  </a>
</div>

## Killers Table

<br />
<div align="center">
  <a href="https://github.com/Metanomic/bayesian_networks_example">
    <img src="images/killers_table.png" alt="Logo" width="712" height="976">
  </a>
</div>

## Scientists Table

<br />
<div align="center">
  <a href="https://github.com/Metanomic/bayesian_networks_example">
    <img src="images/scientists_table.png" alt="Logo" width="706" height="984">
  </a>
</div>