# Dexter - Philips 22VP932 Adapter
A simple adapter to enable Dexter to interface with games that used the Philips 22VP932 laserdisc player.  The only two games I know of are the Atari/European versions of Dragon's Lair and Space Ace.

# Background
When I was working on Dexter, a solid-state laserdisc player replacement for laserdisc arcade games, I wanted to add support for every laserdisc player on the main PCB.
However, it became apparent that I would probably never ship the product if I waited until every player was added to the main PCB.  So I designed the DB25 interface to be expandable and hopefully support future players down the road.
This VP932 adapter is the first adapter I made that extends from Dexter's DB25 interface.  Fortunately, it works correctly.

# PCBs
I created the PCB with Eagle v7.7.0.  I have briefly tested these files on Kicad v6 and they seem to work fine.

This was a smaller project so it was a little rushed.  You may notice that there is overlapping silkscreen on the PCB and the schematic page has no proper border.

# Bill of Materials
These are the actual spreadsheets I used when ordering parts for this PCB and assembling this PCB.

# Support
If you need help having PCBs made from the source files or with any other aspect of this repository, I offer commercial support: https://www.daphne-emu.com:9443/mediawiki/index.php/CommercialSupport

--Matt Ownby
