# AcornMiner HiveOS integration

From https://thefpgaforum.com/threads/alpha-zen-protocol-215-acorn-miner-solo.57/

This miner is intended for linux, it was built as a quick release (a day or so of build). Give it a shot and report to the link above if it works for you. On first launch it will ask you to flash your acorns. Will take a reboot or power cycle to absorb the stand-alone flash image. This is PURELY a tinkerers alpha and while this will get your acorn mining, it isn’t the official SQRL Miner / GPU assist magic.

## Keyboard shortcuts
(+) or (-) will increment or decrement core clock for all acorns

1-9 will select a specific acorn for commands to apply to

a reselects all acorns

t tunes teh Acron - should be supervised for temps!

d disabled

e enables

q quits

## Legend
F/A/I/R/L - Found, Accepted by the pool, Invalid (too high clocks?) Rejected by the pool, Low Difficulty (Acorn internal difficulty is lower than the pool, these are expected). A+I+R+L should = F

Acorns can run at a max of 125C before thermal shut down, and 110C for an extended period of time (I'd personally keep it <100C just to be safe)

Make sure you have the proper drivers installed before running any miner: http://www.squirrelsresearch.com/get-started-acorn/

## Exmaple Flight Sheet
<img src="flight-sheet-example.png">
