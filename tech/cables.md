# Cables

This document describes the cabling standards used at The Voxel.

# Color Code

| Color     | Length |
| --------- | ------ |
| 🟥 Red    | 5'     |
| 🟩 Green  | 10'    |
| 🟦 Blue   | 15'    |
| 🟪 Purple | 25'    |
| 🟧 Orange | 50'    |
| ⬜️ White | 75'    |
| 🟨 Yellow | 100'   |

Length is indicated via colored electrical tape wraps on both ends of all cables. In addition, most cables are also labeled with a printed heat shrink wrap.

# Terminology

The Voxel follows the recommendation of the Professional Audio Manufacturers Alliance (PAMA) for the term "Plug" to refer to the version of a connector with pins and "Socket" to refer to the other. Other recommendations can be found at www.tinyurl.com/PAMA-NN-Guide.

# Cable Types

- DMX (for controlling light fixtures)
- powerCON (for powering light fixtures)
- NL4 (for connecting speakers)
- Edison (for powering things)

---

# Cable Construction

This information can be used as a reference when ordering new components or performing maintenance on existing systems.

### Labeling

All cable is labeled with custom heat shrink on one end.
![dmx5](https://user-images.githubusercontent.com/919746/136625031-0d90e06b-fc23-4f8e-857d-02db98374cc0.png)

The first heat shrink sleeve has The Voxel logo, with the "The" end facing the connector. The next sleeve denotes the cable length as text.
A half-width wrap of colored electrical tape follows the length. All of this is covered in clear heat shrink. The clear heat shrink should not be so lengthy as to reduce the flexibility of the cable.

It is important that all lengths are indicated in text so the color code can be easily learned.

On XLR cables, the connector ring should be the same color as the electrical tape wraps.

### Components

- Heat shrink labels are [Elite Core CUSTOM-SHRINK](https://elitecoreaudio.com/elite-core-custom-shrink-100pk/) black labels with white print. TODO: add the image files to use when ordering.
- Clear heat shrink is 2:1 TODO add size of shrink
- Electrical tape is TODO add tape source
- A hook-and-loop cable wrap should be affixed to the cable on the same end as the heat shrink. 8" is an appropriate length for most cable types. Use 10" for thicker 4-conductor speaker wire, and 12" for most extension cords.

### NL4 (speakON)

![nl4](https://user-images.githubusercontent.com/919746/136625539-7c2d4f07-155b-47ae-8639-7f5d4f550d71.png)

| Color | Length    |
| ----- | --------- |
| 1+    | 🟥 Red    |
| 1-    | 🟩 Green or 🟦 Blue  |
| 2+    | ⬛️ Black |
| 2-    | ⬜️ White |

The Voxel frequently uses pin-swap adapter cables to separately power two speakers with one NL4 cable. All NL4 cable must be 4-wire to avoid confusion.

---

### DMX

![dmx5](https://user-images.githubusercontent.com/919746/136625054-b094ad97-aee1-446b-9760-47c753a82b12.png)

| Pin | Color | Purpose |
| --- | ----- | ------- |
| 1   | ⚡️   | Ground  |
| 2   | 🟥    | Data 1+ |
| 3   | ⬛️   | Data 1- |
| 4   |       | Data 2+ |
| 5   |       | Data 2- |

All DMX cable available to rental users is 5-Pin.

#### DMX over Twisted Pair

The Vox3l follows ESTA Color Code for DMX over twisted pair cable for architectual applications.

| XLR Pin | Twisted Pair Color | Purpose |
| ------- | ------------------ | ------- |
| 1       | ⬜️🟫 White/Brown  | Ground  |
| 2       | 🟧🟧 Orange        | Data 1+ |
| 3       | ⬜️🟧 White/Orange | Data 1- |
| 4       | 🟩🟩 Green         | Data 2+ |
| 5       | ⬜️🟩 White/Green  | Data 2- |

---

### Audio XLR

![xlr3](https://user-images.githubusercontent.com/919746/136625839-38b9d1de-e026-47c1-b4f2-2470a7464883.png)

| Pin | Color | Purpose        |
| --- | ----- | -------------- |
| 1   | ⚡️   | Shield, Ground |
| 2   | 🟥    | Positive       |
| 3   | ⬛️   | Negative       |

---

### Twisted Pair

![ethercon](https://user-images.githubusercontent.com/919746/136625514-8479e0d8-d9fd-47b7-ac05-59a40ec73fbf.png)
![rj45](https://user-images.githubusercontent.com/919746/136625828-8556614f-b322-406c-9c8b-74c22be45e1d.png)

All data cable at The Voxel is Cat6A. Receptacles in the grid are NE8FDX-Y6 etherCON Cat6A which is compatible with standard RJ-45 plugs. For permanent installation, use shielded Cat6A cable.

The Voxel uses T-568B color code.

| Pin | Color              |
| --- | ------------------ |
| 1   | ⬜️🟧 White/Orange |
| 2   | 🟧🟧 Orange        |
| 3   | ⬜🟩 White/Green   |
| 4   | 🟦🟦 Blue          |
| 5   | ⬜🟦 White/Blue    |
| 6   | 🟩🟩 Green         |
| 7   | ⬜️🟫 White/Brown  |
| 8   | 🟫🟫 Brown         |

When looking at an RJ-45 connector, Pin 1 is on the left when the clip is pointing away from you.

---

### Power (Edison)

![edison](https://user-images.githubusercontent.com/919746/136626390-94404f2b-6e0d-4225-95f2-4c963f816a96.png)

---

### Power (powerCON)

Most equipment in The Voxel inventory use Neutrik NAC3FCA powerCON connectors. TRUE1 cables are not kept in inventory.
