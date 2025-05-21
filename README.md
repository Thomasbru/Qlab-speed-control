# Qlab-speed-control
Interfacing between Qlab and a midi controller, to control the run speed of an audio cue.

The cue needs to be no. 3, assumes a base speed of 120BPM.

Assumes the following midi channels:
1 = Go cue 3
2 = Stop cue 3
3 = Tap tempo: first trigger initiates count, second counts time and commits bpm
4 = Reset rate to 1
5 = Decrease rate by 0.01
6 = Increase rate by 0.01

All midi channels respond only to messages w/velocity 127.

---

To do:
- generalize cue no.
- make base bpm adjustable.
- ???
