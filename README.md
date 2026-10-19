# HeyPCB LED Art

Shaped LED boards inspired by films: stars, ghosts, cats, rockets, gears, moons, saucers and shields, each in its own colour. KiCad 10, JLCPCB-ready, CERN-OHL-S-2.0.

<p align="center"><a href="boards/big-moon/"><img src="boards/big-moon/media/top.png" width="180" alt="Full Moon"></a> <a href="boards/blast-gear/"><img src="boards/blast-gear/media/top.png" width="180" alt="Clockwork"></a> <a href="boards/broken-heart/"><img src="boards/broken-heart/media/top.png" width="180" alt="Heartbeat"></a> <a href="boards/crescent-moon/"><img src="boards/crescent-moon/media/top.png" width="180" alt="Crescent"></a> <a href="boards/flying-saucer/"><img src="boards/flying-saucer/media/top.png" width="180" alt="Saucer"></a> <a href="boards/ghost-trap/"><img src="boards/ghost-trap/media/top.png" width="180" alt="Ghost Trap"></a> <a href="boards/hero-shield/"><img src="boards/hero-shield/media/top.png" width="180" alt="Hero Shield"></a> <a href="boards/hyperdrive/"><img src="boards/hyperdrive/media/top.png" width="180" alt="Hyperdrive"></a> <a href="boards/kitty-pink/"><img src="boards/kitty-pink/media/top.png" width="180" alt="Neon Kitty"></a> <a href="boards/knight-shield/"><img src="boards/knight-shield/media/top.png" width="180" alt="Knight"></a> <a href="boards/lucky-heart/"><img src="boards/lucky-heart/media/top.png" width="180" alt="Love Letter"></a> <a href="boards/midnight-cat/"><img src="boards/midnight-cat/media/top.png" width="180" alt="Midnight Cat"></a> <a href="boards/moon-rocket/"><img src="boards/moon-rocket/media/top.png" width="180" alt="Moon Rocket"></a> <a href="boards/nebula-cloud/"><img src="boards/nebula-cloud/media/top.png" width="180" alt="Nebula"></a> <a href="boards/night-ghost/"><img src="boards/night-ghost/media/top.png" width="180" alt="Boo"></a> <a href="boards/pirate-skull/"><img src="boards/pirate-skull/media/top.png" width="180" alt="Skull"></a> <a href="boards/rock-pick/"><img src="boards/rock-pick/media/top.png" width="180" alt="Rock Pick"></a> <a href="boards/stop-sign/"><img src="boards/stop-sign/media/top.png" width="180" alt="Halt"></a> <a href="boards/storm-cloud/"><img src="boards/storm-cloud/media/top.png" width="180" alt="Storm Cloud"></a> <a href="boards/ufo-green/"><img src="boards/ufo-green/media/top.png" width="180" alt="Little Green"></a> <a href="boards/war-gear/"><img src="boards/war-gear/media/top.png" width="180" alt="Engine Room"></a></p>

Every board is its own silhouette and solder-mask colour, with addressable RGB LEDs (XL-2020RGBC-2812B, WS2812B-2020 class) following its outline, a CH32V003 RISC-V controller running at 5 V (so it drives the LEDs directly), a MODE button, a 1-wire SWIO programming header, a 3-pin OUT header that chains the light onto the next board, and USB-C power on a tab at the bottom. 4 layers.

| Board | Idea | Mask | Size | DRC errors / unconnected / parity |
|---|---|---|---|---|
| [Full Moon](boards/big-moon/) | a full moon for a lab window | White | 87.99 x 95 mm | 0 / 0 / 0 |
| [Clockwork](boards/blast-gear/) | a clockwork gear with a ticking light | Black | 76.01 x 82.08 mm | 0 / 0 / 0 |
| [Heartbeat](boards/broken-heart/) | a heart that beats at your pulse | Red | 82.84 x 81.86 mm | 0 / 0 / 0 |
| [Crescent](boards/crescent-moon/) | a crescent moon for a werewolf night | Purple | 80.44 x 91.01 mm | 0 / 0 / 0 |
| [Saucer](boards/flying-saucer/) | a flying saucer from a drive-in movie | Green | 96.01 x 56.67 mm | 0 / 0 / 0 |
| [Ghost Trap](boards/ghost-trap/) | a friendly ghost with a pulse | White | 62.01 x 82.76 mm | 0 / 0 / 0 |
| [Hero Shield](boards/hero-shield/) | a hero's shield with a lit rim | Blue | 64.01 x 83.01 mm | 0 / 0 / 0 |
| [Hyperdrive](boards/hyperdrive/) | an octagon that counts down to the jump | Black | 77.62 x 84.62 mm | 0 / 0 / 0 |
| [Neon Kitty](boards/kitty-pink/) | a neon cat sign from a rainy street | Red | 58.01 x 83.01 mm | 0 / 0 / 0 |
| [Knight](boards/knight-shield/) | a knight's black shield | Black | 56.01 x 75.01 mm | 0 / 0 / 0 |
| [Love Letter](boards/lucky-heart/) | a small heart for a long-distance letter | Purple | 67.78 x 68.25 mm | 0 / 0 / 0 |
| [Midnight Cat](boards/midnight-cat/) | a black cat with glowing outline eyes | Black | 66 x 91.01 mm | 0 / 0 / 0 |
| [Moon Rocket](boards/moon-rocket/) | the rocket from a 1950s moon movie | White | 68.01 x 103.01 mm | 0 / 0 / 0 |
| [Nebula](boards/nebula-cloud/) | a purple nebula cloud | Purple | 71.06 x 51.79 mm | 0 / 0 / 0 |
| [Boo](boards/night-ghost/) | a purple ghost that says boo | Purple | 56.01 x 74 mm | 0 / 0 / 0 |
| [Skull](boards/pirate-skull/) | a pirate flag skull with a lit jaw | Black | 64.01 x 71.89 mm | 0 / 0 / 0 |
| [Rock Pick](boards/rock-pick/) | a guitar pick that flashes on the beat | Black | 55.45 x 62.45 mm | 0 / 0 / 0 |
| [Halt](boards/stop-sign/) | an octagon that says stop | Red | 73.93 x 80.93 mm | 0 / 0 / 0 |
| [Storm Cloud](boards/storm-cloud/) | a cloud that rains light | White | 80.66 x 56.49 mm | 0 / 0 / 0 |
| [Little Green](boards/ufo-green/) | a black saucer with green running lights | Black | 84 x 50.47 mm | 0 / 0 / 0 |
| [Engine Room](boards/war-gear/) | a gear from the engine room of a steam airship | Blue | 80.01 x 86.51 mm | 0 / 0 / 0 |

**Not fabricated, assembled or powered.** Every number in a board's README is measured by KiCad 10 on the files in its folder (`report.json`); parts carry LCSC numbers and were in JLCPCB's stock on the date each README gives. Order each board in its stated mask colour. Firmware is not included: these are the boards.

Designed with the HeyPCB method on KiCad 10 by heypcb-kicad's headless pipeline with Freerouting 2.4.1.

## Licence

CERN-OHL-S-2.0, © 2026 heypcb.ai. See [LICENSE](LICENSE).
