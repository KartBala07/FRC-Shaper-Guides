# FRC Shaper Guides

A complete guide to using FRC Shaper, a free Chrome extension that makes Onshape faster for FRC teams.

## Table of Contents

- [Guide](#guide)
- [Keys to Know](#keys-to-know)
- [Getting Started](#getting-started)
- [Select it, check the preview, press Enter](#select-it-check-the-preview-press-enter)
- [Press the A key, type, press Enter](#press-the-a-key-type-press-enter)
- [Parts in an Assembly](#parts-in-an-assembly)
- [Motors and Drive](#motors-and-drive)
- [Auto-assembler](#auto-assembler)
- [Tools](#tools)
- [Part Studio](#part-studio)
- [You and Your Friends](#you-and-your-friends)

---

## Guide

Start here. This is the master guide to FRC Shaper.

### Select it, check the preview, press Enter

Select a hole, an edge or a part and a card by your pointer offers what fits, previewed in place.

Press the **Enter** key to insert that part into the document. `Ctrl+Z` undoes the whole run.

---

### Keys to Know

| Key | Action |
|-----|--------|
| `A` | Insert any part by name |
| `Shift+A` | Auto-assemble (fills whole gearbox) |
| `Enter` | Run the line |
| `Tab` | 1–9 Pick another line |
| `←→` | Change a pill |
| `Esc` | Close the card |
| `Ctrl+Z` | Undo the last run |
| `Ctrl+Y` | Redo it |
| `Shift+F` | Tidy the tree |
| `Shift+L` | Check the Assembly |
| `Shift+K` | Quick settings |
| `Shift+J` | FRCShaper off / on |
| `Shift+B` | Calculator |

---

## Getting Started

How the cards work, part search (the A key), your account and the look.

Select something and a card by your pointer offers what fits, with the part previewed in place.

Switch FRCShaper to FTC standards: metric bolts, goBILDA's 8mm REX parts and the FTC parts library.

---

## Part Search

### Press the A key, type, press Enter

In an Assembly, press the **A** key and type a name (e.g., `"20t pulley"`, `"1.5 in 10-32"`, `"kraken x60"`).

Press **Enter**.

FRCShaper inserts the right part and mates it to your selection point.

### The Process

1. Click where a part goes (in an Assembly or Part Studio)
2. Type the part name in the search box
3. Enter (or press the ⬅️/➡️ arrow on the card)
4. FRCShaper:
   - Inserts the part to the correct location
   - Mates the part to your selection
   - If inserting in an Assembly, creates a new line with a flow part that holds it

### Tips

- FRCShaper looks through FRCDesignLib, plus Onshape's standard content for metric bolts
- Type the name in the way you'd say it in conversation
- Watch out for names that aren't unique - you'll need to refine your search
- Press ⬅️ or ➡️ on the card to navigate results

---

## Parts in an Assembly

Click where a part goes. FRCShaper inserts the right part and mates it.

### Bearings

Click a bearing hole for a hex bearing (and its retainer), then two bearings for the shaft between them.

FRCShaper:
- Inserts the bearing to your selection
- Creates a flow mate between the bearing and the hole
- Calculates and creates a shaft that spans between two bearings if requested

### Motors

Click a motor's mount: the Kraken, Falcon, NEO or Minion goes on, lined up.

- Select the motor mounting point
- Choose your preferred motor from the drop-down
- FRCShaper creates the motor and mates it to the mount

### Gears, Pulleys and Sprockets

From your layout sketch, or any size you pick.

- Click a gear hole in your layout
- Type the size and number of teeth
- FRCShaper fills in the part and mates it

### Belts and Chain

The size that fits between two pulleys or sprockets.

- Click two pulleys/sprockets
- FRCShaper calculates the belt/chain pitch length

### Wheels and Swerve

A wheel on a shaft, a module on a frame corner.

- Click the wheel mounting point
- FRCShaper inserts the wheel and mates it to the shaft/frame

---

## Auto-assembler

Shift+A plans the whole gearbox from its plates and your layout sketch, previews it on a plan card, and builds it when you press Enter.

### How It Works

1. Put the design plates into an Assembly
2. Open an Assembly
3. Press **Shift+A**
4. A plan card shows with pills arranged
5. Press **Enter** on the cards to build the gearbox

### The Process

1. Open your Assembly document
2. Shift+A opens the plan card
3. Review the gear arrangement (left/right side, shifts, and layout index)
4. Press **Enter** to insert gears, press Enter again to mate them
5. Repeat for each line in the card
6. `Ctrl+Z` undoes all changes at once
7. `Ctrl+Y` puts everything back

### Tips

- The auto-assembler builds gearboxes the way the FRCDesign.org course teaches
- It uses gearboxes from the Exercise 2 and 3 clips in FRCDesignLib
- Check the plan before building - it's fast to undo with Ctrl+Z
- Shift+F tidies the tree after assembly

---

## Tools

### Shift+F - Files the Assembly

Files the Assembly's hardware into folders by kind and hides the mates.

### Shift+K - Quick Settings

Opens FRCShaper's settings inside Onshape.

### Shift+J - Toggle

Turns FRCShaper off / on.

### Shift+B - Calculator

Opens the calculator window for gear ratios and other calculations.

---

## Part Studio

Robot shaft, Robot spacer, Robot frame and Origin Cube, each its own guide.

### Robot Frame

Creates the robot frame from two clicks and the selected plates.

### Robot Spacer

Creates a spacer from two holes and their parent bodies.

### Robot Shaft

Creates a shaft from two points.

### Origin Cube

Sets up the origin cube for new documents.

---

## You and Your Friends

A free Chrome extension that makes Onshape faster for FRC teams.

© 2026 FRCShaper.

---

## Credits

### Ethan

Made FRC Shaper · FRC Team 7415

Designed and built FRCShaper: the auto-assembler, the click rules, the themes, the Guide and everything else in it.

### FRCDesign.org and FRCDesignLib

The FRC design course and parts library for Onshape

Nearly every part FRCShaper inserts comes from FRCDesignLib, and part search looks through the whole library. The auto-assembler builds gearboxes the way the course teaches, and the clips use its Exercise 2 and 3 gearboxes. FRCDesignLib grew out of MKCad, started by Team 1836, the Milkenknights.

[Contributors](https://www.frcdesign.org/contribution/contributors/)

### howlongismyname

Made the original software FRC Shaper is based off of.

### Alex Kempen

Wrote the Robot shaft, Robot spacer and Robot frame FeatureScripts. FRCShaper's Part Studio tools fill them in from your clicks.

### Justin Tervay

Made ReCalc, the FRC design calculator. FRCShaper's calculator window (Shift+B) is reca.lc.

### Testers

- Ethan FRC Team 7415
- Zach FRC Team 7415
- Lulucu FRC Team 7415
- Arnan FRC Team 5667
- Taven FRC Team 4322

FRCShaper isn't affiliated with Onshape, FIRST, FRCDesign.org or ReCalc.

---

## Version History

### v0.7.3

Current version.

---

## Install

Add FRCShaper from the Chrome Web Store (Chrome or Edge):

[Add to Chrome](https://chromewebstore.google.com/detail/frcshaper/pnaofgdknhccbnmhiljjbhfanjbcnpmd)

## Privacy

See the [privacy policy](https://www.frcshaper.org/privacy).
