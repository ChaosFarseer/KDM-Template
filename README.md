# KDMtron - A Kingdom Death Prototype AI Card Generator

Created by Greg Oppenheimer and Alex Freeman

This project allows you to generate AI cards and HL cards for Kingdom Death: Monster. 
These cards are not intended to be at the full quality level of official KDM cards; instead, this is for rapidly 
creating and playtesting custom Kingdom Death content. When it's time to make your cards look official, you will
need to look elsewhere. 

The card template is currently fully functional, but it could be more flexible and it could look better. 
It's hypothetically possible to make this generate full-quality KDM cards, but that's not intended to happen anytime
soon. 

## Features
 * Generate cards from a spreadsheet or Google Sheets
 * Insert flows, alerts, attack profiles, and images
 * Headers for your various types of cards
 
![Image](https://media.discordapp.net/attachments/608857593120555008/628100734784765953/KDM_Template_11.png 
"Example card output")

## Setup Instructions
 1. Download [nanDECK](http://www.nand.it/nandeck/). 
 2. Copy the Git repository to your computer. If you are new to Git, it's fairly easy to use GitHub's visual client.
If you do not want updates, you can download the repository as a zip file instead. 
 3. Run nanDECK, click the Open Deck button, and select "KDM_Template.txt". 
 4. Test whether you have set things up correctly by clicking Validate Deck. Ignore the missing image warnings; if the deck is valid, the text output at the bottom should end with "Deck valid". 
 5. Click 'Build Deck' to preview how the example cards will look. You can browse through them using the arrows in the middle-right. 
 6. Make a copy of our [spreadsheet template](https://docs.google.com/spreadsheets/d/1KFg9fd_qZ4na4wP_3k7uMGBlgKIDKpmFX4UL-xydCqU/edit?usp=sharing). 
 7. If you continue using Google Sheets, get a sharable link with at least view permissions. Take the sheet ID out of the URL, and replace the first line inside KDM_Template.txt with that ID. For example, the template's ID is: 1KFg9fd_qZ4na4wP_3k7uMGBlgKIDKpmFX4UL-xydCqU
 8. You should now be able to make your own changes and see them inside nanDECK. Go nuts!

## Options
Up to 6 elements per card. 

Most elements are designed for AI cards, but you can improvise Hit Location cards by using text boxes. 

Supported headers: Mood, Duration, Trap, Trait, Survivor Status, Terrain. Headers are blue by default, for your hit location
headers such as First Strike, Super-Dense, Impervious, Light Speed, and so on. 

Element options: 
* TX(1-4) - Text block. TX4 is longer than TX1. 
* TRG(1-4) - Attack Trigger
* FLOW - Flow
* ALRT - Alert
* INJ(1-3) - Persistent Injury
* ATK - Attack
* ZONE - For inserting images. Image must be in template's directory; recommend using included template for zones of death. 

## Tips and Tricks
* You can validate and build the deck in one click by right-clicking Validate Deck, instead of left-clicking. 
* nanDECK will always use the leftmost sheet in the linked Google Sheet. You can get the template to print different sheets by changing their order. 
* If you want to do one card yourself, replace the card's title with the path to a card image. The entire card will be replaced with that image. 
* For a currently in-use example of how to use the template, you can look at what I use for my [Harvester Worm](https://docs.google.com/spreadsheets/d/1MhVIXiGWFDXuERPZeP26gSarWC62nU7wimgjc5GG4vE/edit?usp=sharing). Feel free to copy stuff from this sheet.  

## How to Import into Tabletop Simulator
<https://kb.tabletopsimulator.com/custom-content/custom-deck/#deck-builder>

## How to Modify This Template
Get Sublime Text or some equivalent text editor, or die. 

Read the nanDECK manual. 

We don't yet have a good way to do loops, so the number of elements is determined by copy-pasting. To alter all templates
at once, you really really want to have multi-select. 

You need to reload the template in nanDECK every time you make a change to the file in your text editor. 
