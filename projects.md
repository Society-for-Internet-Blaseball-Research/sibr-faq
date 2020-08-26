
# Current SIBR Projects

* check the faq: https://github.com/Society-for-Internet-Blaseball-Research/sibr-faq

* More details on projects may be available at https://trello.com/b/KqiT4fms/society-for-internet-blaseball-research-projects

* A diagram of how the SIBR projects relate can be found at https://docs.google.com/presentation/d/1iSM7uVkyUx-XY2ff0E8osNF_7DgFPUQvsGzsnS_5Kho/edit?usp=sharing

## The Datablase (#datablase)

* Description: Database to store archived blaseball data
* Docs: https://api.blaseball-reference.com/docs
* Code: https://github.com/Society-for-Internet-Blaseball-Research/datablase
* Contributers: Corvimae, lilserf, Sakimori, iliana, shibboh, tehstone

### Datablase Python Client

* Site: https://github.com/jmaliksi/blaseball-reference-py
* Contributer: ch00beh#0836

### Scryer

* Description: A Browser-based datablase client
* Site: https://metermaid.github.io/scryer/
* Code: https://github.com/metermaid/scryer
* Contributors: risky#9552

### blaseball-reference.com

* Description: not launched yet, but a reference for stats
* Contributors: @shibboh
* Preview: https://dev.blaseball-reference.com/

## Harvesting and Analyzing Data (#archivism)

### blaseball-archive-scripts

* Description: Tools and structures for the archival of Blaseball game logs and player statistics. Archiving scripts that store raw game updates for use by other systems. Several SIBR members are running these to capture as much data as we can. Archiving began during Season 2 so some Season 2 updates are missing.
* Code: https://github.com/iliana/blaseball-archive-scripts
* Contributors: @ iliana#8784, @ shibboh#4306

### Cauldron

* Site: https://nuget.org/packages/SIBR.Cauldron/
* Code: https://github.com/lilserf/Cauldron
* Description: .NET Core library to process raw JSON from `baseball-archive-scripts` into a SIBR-defined schema for use in a DB. Now includes a visualizer that can line up the original JSON with the exported events!
* Contributors: @ lilserf#8712

### Prophesizer

* Description: Tool for importing raw logs from S3 into Postgres using `Cauldron`
* Site:  https://github.com/Society-for-Internet-Blaseball-Research/prophesizer
* Contributors: Corvimae

### sibr-ops

* Description: Standard configuration files and database schemas for SIBR infrastructure
* Site:  https://github.com/Society-for-Internet-Blaseball-Research/sibr-ops
* Contributors: @ Corvimae#8392


## Viewing Games

### Blaseball-Livestream-Watcher

* Description: A way to view stats and box scores for any given blaseball game (live or archived) and a fully featured client for any game. Can also process stored JSON from `baseball-archive-scripts` and calculate advanced stats like SLG and WHIP!
* Site: https://github.com/Sakimori/Blaseball-Livestream-Watcher/releases
* Code: https://github.com/Sakimori/Blaseball-Livestream-Watcher
* Contributors: @ Sakimori#1228

### Blaseball Game Log

* Description: Watch a game in your browser, and scroll back through the history
* Site: http://jlareau.club.cc.cmu.edu/blaseball.html
* Contributors: @Dlareau

### Node.js game viewer

* Description: Follow a Blaseball game for the given team and print updates to the console. (deprecated??)
* Site: https://gist.github.com/JavadocMD/49309d286ba24dc3eb2d25236263afd8

### blaseball-recorder

* Description: recorder (deprecated?)
* Site: https://github.com/GoggleChild/blaseball-recorder

## User scripts / styles

### Blaseball-Userstyles

* Description: Tweaks to make your viewing experience on blaseball.com better
* Site: https://holmesmr.github.io/Blaseball-Userstyles
* Contributors: @ceph3us.#0451

### Blaseball Userstyles 2

* Description: CSS improvements for blaseball.com
* Site: https://gist.github.com/Fugiman/1cbe3b776bb9603298fc4258495af09a

## Betting (#betting-and-voting)

### Blaseball-Bet-Optimizer

* Description: Optimises the value of users' bets and streamlines the decision process for choosing bet values.
* Site: https://github.com/Cor-8558/Blaseball-Bet-Optimizer
* Contributors: @ Cor#8558

### Blaseball Bet Gist

* Description: For optimizing bet amounts on Blaseball. Play ball!
* Site: https://gist.github.com/SubstandardZeal/a866d5ccee88d475937d5d3d2b7b0d1c

## Forbidden Knowledge

### stlatsviewer

* Description: Viewer for player statistics by team. (live)
* Site: https://dittoslash.uk/stlatsviewer/
* Source: https://git.sr.ht/~dittoslash/blaseballstlats
* Contributors: @ rainefall#0001, @ Gir327#9432
* Project Board: https://todo.sr.ht/~dittoslash/blaseballstlats

### blaseball.space

* Description: Viewer for the secret attributes assigned to each player (old data, out of date)
* Site: https://blaseball.space

### Vibe Check

* Description: checks some vibes
* Site: https://jlareau.club.cc.cmu.edu/vibe-check.html

### Blaseball-stats

* Description: stlat comparison
* Site: https://donblaseball.github.io/blaseball-stats/

### StatsVStLats
* Description: stlats vs stats
* Site: https://notruestatistics.shinyapps.io/batStatsVStLats/

### forbidden knowledge

* Description: blessings vs decrees? deprecated
* Site: https://forbidden-knowledge.vercel.app/

## Blaseball.com API

### API Documentation

* Description: Detailed documentation of all known blaseball.com API endpoints for community reference.
* Site1: https://github.com/Society-for-Internet-Blaseball-Research/blaseball-api-spec
* Site2: https://postman.com/collections/8c0e97c7444de0a125ac
api docs, sorta anyways
* Contributors: @ Corvimae#8392, @ tehstone#8448, @ dwfig (discord unknown)

### node-blaseball
* Description: Blaseball API for Node.js, written in TypeScript
* Site: https://npmjs.com/package/node-blaseball
* Code: https://github.com/TheHanna/node-blaseball
* Contributors: @TheHanna#5269
* Project Board / Todo List: https://github.com/TheHanna/node-blaseball/projects/1

### modern-blaseball

* Description: blaseball api/scraper for python #1 (deprecated??)
* Code: https://github.com/helloimowen/modern-blaseball
* Code: https://github.com/helloimowen/blextract

### blaseball api for python 2 (deprecated??)

* Code: https://github.com/swgillespie/blaseball

### blaseball api for python 3 (deprecated???)

* Code: https://gist.github.com/Edgarware/78ee78fcd7781379b9c604cac7393423

### The Book Scrapers

* Description: scrapers for the book
* Python: https://gist.github.com/oshoham/0ee3c81013183ce57d6c48897cd25be5
* JS: https://gist.github.com/oshoham/b05e81e4759e5105d0a4c947172e025c

### splortshub

* Description: reverse look up / caching (not working????)
* Docs: http://api.splortshub.com/docs
* Example: http://api.splortshub.com/api/v1beta/players/search/?name=Ziwa%20Mueller

## Papers + Paper Accessories

### Blaseball Research

* Description: official papers directory
* Site: https://research.blaseball-reference.com/
* Github: https://github.com/Society-for-Internet-Blaseball-Research/papers

### style-guide

* Description: style guide
* Site: https://github.com/Society-for-Internet-Blaseball-Research/style-guide

### blaseball ticker analysis

* Description: arguably, the first blaseball publication
* Site: https://coeneedell.com/post/blaseball_ticker_analysis/

### Formal math write ups

* Description: some overleaf collections...
* Site: https://www.overleaf.com/6349797897qjhwszrgmfzb
* Site: https://overleaf.com/3185459682vsfgkkkqnpyp
* Site: https://overleaf.com/6845487649rwznxykvzygd
* Site: https://overleaf.com/9582456254bnrntpmcbttr
* Contributors: baronbliss@

### mining-ops

* Description: A place to store your datamining operations, keep lab notebooks, and store code that doesn't belong to a particular research paper.
* Site: https://github.com/Society-for-Internet-Blaseball-Research/sibr-ops
* Contributors: @ soybison#9152
* Project Board: https://github.com/Society-for-Internet-Blaseball-Research/mining-ops/issues

### blaseball-notebooks

* Description: python notebooks
* Site: https://github.com/dlareau/blaseball-notebooks

## Misc Fun Stuff

### Jlohn Mladden

* Description: blaseball announcing robot
* Code: https://github.com/jmaliksi/jlohn-mladden
* Contributors: jmaliksi

### Rescorer

* Description: rescorin' stuffs
* Site: https://github.com/lilserf/Rescorer
* Site: https://gist.github.com/dlareau/ecd34d38df5836ba17c633f96c7e519e
