# MikroTik Quest

![cover](img/cover.png)

Interactive quiz based on the **MikroTik Complete Course** by Ing. Alexis Uranga. Test your knowledge for the **MTCNA** certification with 5 game modes.

## Game Modes

| Mode | Pts | Description |
|------|-----|-------------|
| Quiz | 10 | Multiple choice questions |
| True/False | 5 | Evaluate statements as true or false |
| Word Scramble | 15 | Rearrange letters to form the correct word |
| Fill-in | 10 | Complete the sentence with the missing word |
| Case Scenarios | 20 | Real-world practical scenarios |

## Scoring System

- **Streak x2**: +5 pts bonus
- **Streak x3+**: +10 pts bonus
- Each mode awards different base points
- Maximum streak is recorded and displayed at the end

## Getting Started

### Windows
```bat
start index.html
```
Or double-click `run.bat`.

### Linux / macOS
```sh
xdg-open index.html
```
Or run `./run.sh`.

## Project Structure

```
mikrotik/
├── index.html           -- Main game file
├── run.bat              -- Windows launcher
├── run.sh               -- Linux/macOS launcher
├── favicon.svg          -- Game favicon
├── cover.png            -- README cover image
├── license.json         -- License and credits
├── package.json         -- Project metadata
├── img/
│   └── *.webp           -- OG metadata image
└── sounds/
    ├── mario-1-up.mp3   -- Correct answer sound
    ├── error-soundss.mp3-- Wrong answer sound
    ├── win-gameshow.mp3 -- Victory sound
    └── losssss.mp3      -- Defeat sound
```

## Topics Covered

Based on 91 pages of the complete course:

- [x] Networking fundamentals
- [x] Interface and bridge configuration
- [x] Firewall, NAT and filtering
- [x] Static and dynamic routing
- [x] Wireless and security
- [x] DHCP, DNS, QoS
- [x] VPNs and tunnels
- [x] Monitoring and diagnostics
- [x] RouterOS scripting
- [x] Administration case studies

## Built With

- HTML5 + CSS3 + vanilla JavaScript
- Font Awesome 6.5.1 (icons)
- No external dependencies

---

**Credits:** Content based on the course by Ing. Alexis Uranga. Developed by 0noxtackore.
