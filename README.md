# KDMtron - A Kingdom Death Prototype AI Card Generator

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
 1. Download [nanDECK] (http://www.nand.it/nandeck/). 
 2. Copy the Git repository to your computer. If you are new to Git, it's fairly easy to use GitHub's visual client.
If you do not want updates, you can download the repository as a zip file instead. 
 3. Run nanDECK, click the Open Deck button, and select "KDM_Template.txt". 
 4. Test whether you have set things up correctly by clicking Validate Deck. If 

TODO: Link to example template, which is simpler than my template. 

## Options
Up to 6 elements per card. 

Most elements are designed for AI cards, but you can improvise Hit Location cards by using text boxes. 

Supported headers: Mood, Duration, Trap, Trait, Survivor Status. Headers are blue by default, for your hit location
headers such as First Strike, Super-Dense, Impervious, Light Speed, and so on. 

Element options: 
Text
Flow
Alert
Header
Zone
Attack Profile
Attack Trigger
Persistent Injury

## How to Import into Tabletop Simulator

## How to Modify This Template
Get Sublime Text or some equivalent, or die. 

Read the nanDeck manual. 

We don't yet have a good way to do loops, so the number of elements is determined by copy-pasting. To alter all templates
at once, you really really want to have multi-select. 

You need to reload the template in nanDeck every time you make a change to the file in your text editor. 
