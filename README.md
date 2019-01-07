# AcornMiner HiveOS integration

From https://thefpgaforum.com/threads/alpha-zen-protocol-215-acorn-miner-solo.57/

This miner is intended for windows and linux, it was built as a quick release (a day or so of build). Give it a shot and let me know if it works for you. On first launch it will ask you to flash your acorns, it'll skip non-215+ and say an error, but ignore that if you have mixed acorn. Will take a reboot or power cycle to absorb the stand-alone flash image. This is PURELY a tinkerers alpha and while this will get your acorn mining (profitably per my power calcs), it isn’t the official SQRL Miner / GPU assist magic

## Keyboard shortcuts
(+) or (-) will increment or decrement core clock for all acorns

1-9 will select a specific acorn for commands to apply to

a reselects all acorns

d disabled

e enables

q quits

## Legend
F/A/I/R/L - Found, Accepted by the pool, Invalid (too high clocks?) Rejected by the pool, Low Difficulty (Acorn internal difficulty is lower than the pool, these are expected). A+I+R+L should = F

Acorns can run at a max of 125C before thermal shut down, and 110C for an extended period of time (I'd personally keep it <100C just to be safe)

Make sure you have the proper drivers installed before running any miner: http://www.squirrelsresearch.com/get-started-acorn/
