# Current SIBR Projects

More details on projects may be available at https://trello.com/b/KqiT4fms/society-for-internet-blaseball-research-projects

A diagram of how the SIBR projects relate can be found at https://docs.google.com/presentation/d/1iSM7uVkyUx-XY2ff0E8osNF_7DgFPUQvsGzsnS_5Kho/edit?usp=sharing


## Datablase

The official SIBR statistical reference API. https://api.blaseball-reference.com/docs

### Datablase Clients

Python: https://github.com/jmaliksi/blaseball-reference-py (by ch00beh#0836)

## Real Performance Statistics

### https://docs.google.com/spreadsheets/d/1tGDP50yFYbYYrptcUB-735D75ZOTDxHHV-XC32wUFdc/edit#gid=0
Season 3 basic stats. Includes simple countable stats for batters and pitchers (not more complex calculated stats like SLG or WHIP), as well as each team's schedule.

## Harvesting and Analyzing Data

### https://github.com/iliana/blaseball-archive-scripts
Archiving scripts that store raw game updates for use by other systems. Several SIBR members are running these to capture as much data as we can.
Archiving began during Season 2 so some Season 2 updates are missing.

### https://github.com/lilserf/Cauldron
.NET Core library to process raw JSON from `baseball-archive-scripts` into a SIBR-defined schema for use in a DB

### https://github.com/Society-for-Internet-Blaseball-Research/prophesizer
Imports data into a SQL DB using `Cauldron`

### https://github.com/Society-for-Internet-Blaseball-Research/sibr-ops
Operational configs for SIBR infrastructure

### https://github.com/Society-for-Internet-Blaseball-Research/mining-ops
A place to store your datamining operations, keep lab notebooks, and store code that doesn't belong to a particular research paper.

## Viewing Games

### https://github.com/Sakimori/Blaseball-Livestream-Watcher/releases
Local app that watches games and records box scores and statistics. Can also process stored JSON from `baseball-archive-scripts` and calculate advanced stats like SLG and WHIP!

### http://jlareau.club.cc.cmu.edu/blaseball.html
Watch a game in your browser, and scroll back through the history

### https://holmesmr.github.io/Blaseball-Userstyles
Tweaks to make your viewing experience on blaseball.com better

## Betting

### https://github.com/Cor-8558/Blaseball-Bet-Optimizer
For optimizing bet amounts on Blaseball. Play ball!

### https://docs.google.com/spreadsheets/d/1Zvqq_ypg2I26WMmepbpgO7w5mZB1amNq3No8lhPBaGU/edit#gid=0
Information on shop costs and payouts

## Forbidden Knowledge

### https://git.sr.ht/~dittoslash/blaseballstlats
Viewer for the secret attributes assigned to each player

## Utilities and APIs for other projects

### https://github.com/TheHanna/node-blaseball
Blaseball API for Node.js, written in TypeScript
