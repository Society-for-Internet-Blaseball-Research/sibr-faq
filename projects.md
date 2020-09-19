
# Current SIBR Projects

* check the faq: https://github.com/Society-for-Internet-Blaseball-Research/sibr-faq

* A diagram of how the SIBR projects relate can be found at https://docs.google.com/presentation/d/1iSM7uVkyUx-XY2ff0E8osNF_7DgFPUQvsGzsnS_5Kho/edit?usp=sharing

## The Datablase (#datablase)

* Description: Database to store archived blaseball data
* Docs: https://api.blaseball-reference.com/docs
* Code: https://github.com/Society-for-Internet-Blaseball-Research/datablase
* Contributers: Corvimae, lilserf, Sakimori, iliana, shibboh, tehstone

### Datablase Python Client

* Site: https://github.com/jmaliksi/blaseball-reference-py
* Contributer: ch00beh#0836

### Reblase

* Description: Comprehensive archived games viewer built partially using the datablase!
* Site: https://reblase.sibr.dev/
* Code: https://github.com/xSke/BlaseballData
* Contributors: Ske#6201

### Scryer

* Description: A Browser-based datablase client
* Site: https://metermaid.github.io/scryer/
* Code: https://github.com/metermaid/scryer
* Contributors: risky#9552

### blaseball-reference.com (#blaseball-reference)

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
* Contributors: Corvimae, lilserf, ifhbiff

### sibr-ops

* Description: Standard configuration files and database schemas for SIBR infrastructure
* Site:  https://github.com/Society-for-Internet-Blaseball-Research/sibr-ops
* Contributors: @ Corvimae#8392


## Viewing Live Games

### Blaseball Game Log

* Description: Watch a game in your browser, and scroll back through the history
* Site: http://blaseball.dlareau.com
* Contributors: @Dlareau

### Blaseball Playback

* Description: Tool to record current blaseball games and play them back on a local streaming server. Also works with SIBR archives
* Site: https://github.com/Cidolfas/BlaseballPlayback

### Blases Loaded (#blases-loaded)

* Description: Blases Loaded is a mobile app for live-viewing Blaseball games.
* Site: https://rangerrick.github.io/blobile/
* Code: https://github.com/RangerRick/blobile
* Contributors: RangerRick#6987

### bbTV

* Description: Blaseball TV Viewer, written in C# for Unity 2019.3 Download the latest release in the panel to the right to try it out today!
* Site: https://github.com/KaynSD/bbTV
* Contributors: KaynSD#5477

## Blaseball.com Scripts and Parsers (#site-js)

### Blaseball-Userstyles

* Description: Tweaks to make your viewing experience on blaseball.com better
* Site: https://holmesmr.github.io/Blaseball-Userstyles
* Contributors: @ceph3us.#0451

### The Book Scrapers

* Description: scrapers for the book
* Python: https://gist.github.com/oshoham/0ee3c81013183ce57d6c48897cd25be5
* JS: https://gist.github.com/oshoham/b05e81e4759e5105d0a4c947172e025c

### blaseball-net-winnings

* Description: A userscript to add fields to the Watch Live section of Blaseball to calculate net winnings
* Code: https://github.com/rgallo/blaseball-net-winnings
* Contributor: TransatlanticFoe#3525

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
* Site: http://stlats.sibr.dev/
* Source: https://git.sr.ht/~dittoslash/blaseballstlats
* Contributors: @ rainefall#0001, @ Gir327#9432
* Project Board: https://todo.sr.ht/~dittoslash/blaseballstlats

### Vibe Check

* Description: checks some vibes
* Site: http://blaseball.dlareau.com/vibe-check.html

### Blaseball-stats

* Description: stlat comparison
* Site: https://donblaseball.github.io/blaseball-stats/

### StatsVStLats
* Description: stlats vs stats
* Site: https://notruestatistics.shinyapps.io/batStatsVStLats/

## Blaseball.com API Clients (#blaseball-api)

### API Documentation

* Description: Detailed documentation of all known blaseball.com API endpoints for community reference.
* Site1: https://github.com/Society-for-Internet-Blaseball-Research/blaseball-api-spec
* Site2: https://postman.com/collections/8c0e97c7444de0a125ac
* Contributors: @ Corvimae#8392, @ tehstone#8448, @ dwfig (discord unknown)

### node-blaseball
* Description: Blaseball API for Node.js, written in TypeScript
* Site: https://npmjs.com/package/node-blaseball
* Code: https://github.com/TheHanna/node-blaseball
* Contributors: @TheHanna#5269
* Project Board / Todo List: https://github.com/TheHanna/node-blaseball/projects/1

### blaseball-mike

* Description: blaseball API for python, with lazy loading references and event stream support
* Code: https://github.com/jmaliksi/blaseball-mike

## Games Analysis

### Blaseball Playoff Status

* Description: a tool to check whether your team will make the playoffs
* Site: https://mixolyde.github.io/blaseballstatus/index.html
* Code: https://github.com/mixolyde/blaseballstatus
* Contributors: mixolyde#9663

### blaseball-streak-finder

* Description: This repo contains a command line tool called streak-finder that helps find blaseball winning and losing streaks.
* Code: https://github.com/ch4zm/blaseball-streak-finder
* Contributors: 🌞 Ch4zm of Hellmouth 🌞

### interesting-blaseball-games

* Description: interesting-blaseball-games is a command-line tool for finding interesting blaseball games.
* Code: https://github.com/ch4zm/interesting-blaseball-games
* Contributors: 🌞 Ch4zm of Hellmouth 🌞

### Sclorigami

* Description: Scorigami tool in rust
* Code: https://gitlab.com/red9/sclorigami
* Contributors: red#4096

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

## Blasebot

* Description: A discord bot for watching games and looking up facts
* Code: https://github.com/BeeFox-sys/blasebot
* Bot Invite: https://discord.com/oauth2/authorize?client_id=749154634370646067&scope=bot&permissions=18432
* Contributors: BeeFox#7767

## Blaseball-Scripts

* Description: A collection of scripts to help use blaseball
* Code: https://github.com/BeeFox-sys/blaseball-scripts
* Contributors: BeeFox#7767