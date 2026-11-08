# 🎧 Pitch Lab

Ear-training games made for Reece and Brian. Open it in any browser, on a phone, tablet or computer:

**▶ Play: https://mfenickfau.github.io/pitch-lab/**

## Games

| Game | What it trains |
|---|---|
| 🕵️ **Note Detective** | *Absolute pitch*: hear a note with no reference and name it. You start with 3 notes (C, G, E) and unlock a new one each time you score 85%+ over 20 answers. A quick "scramble" plays before each note so you can't just compare it to the last one. |
| 📏 **Interval Hunter** | *Relative pitch*: name the distance between two notes. Song hints help you remember each one (e.g. a Perfect 4th is "Here Comes the Bride"). Unlocks up to all 12 intervals, then mixes in descending and played-together intervals. |
| 🎯 **Sharp Ears** | A 30-round higher/lower test that gets harder as you go and measures the smallest pitch difference you can hear, in cents (100 cents = one piano key). |
| 🥁 **Tempo Sense** | Your inner clock. **Guess the BPM**: a beat plays and you set a slider to how fast it is (8 rounds). **Tap the BPM**: you see a tempo like "96 BPM", hear a 4-beat count-in, then tap 8 beats on your own. It scores your speed and your steadiness. |
| 🎙️ **Sing It** *(optional, uses the mic)* | Hear a note, sing it back, and keep the live needle in the green zone. Singing an octave up or down still counts. Choose Deep, Middle or High to fit your voice. |

Each player has their own profile with points, a daily streak and a leaderboard. Progress is saved in the browser on each device, so it doesn't carry over between devices.

## Tips
- Headphones help for the listening games. For **Sing It**, use speakers at a low volume so the mic hears you.
- A few minutes every day works better than one long session.

## Tech
One `index.html` file with no build step. Sound is generated with the Web Audio API, and Sing It detects your pitch in the browser (YIN-style). No audio ever leaves the device.

---

# 💩 Hospital Simulator

*The grossest game in the world*, made by Brian and Dad. Retro Atari-style graphics. It works on a PC (keyboard) and on a phone (on-screen joystick + MOP button).

**▶ Play: https://mfenickfau.github.io/pitch-lab/hospital-simulator/**

### Level 1: Code Brown
You're the new night-shift nurse at St. Grossington's Hospital. All 9 rooms are covered in poop, puke, pee, blood, and (in the Operating Room) guts. Clean them all before the 3:30 timer runs out to unlock Level 2.

- **Create your nurse:** name, city, skin, hair color and style, scrubs color, nurse cap, and a nurse type: *Speedy Sneakers* (faster), *Iron Stomach* (mops faster, never gags) or *Mega Bucket* (holds more).
- **Move:** arrow keys / WASD. **Mop:** hold SPACE on a mess.
- **Bucket:** each mess fills your bucket. When it's full, dump it at a red biohazard bin in the hallway.
- **Watch out:** patients turn green right before they barf or poop on the floor, and stepping in pee or puke makes you slip.
- **Pause:** P. **Mute:** M.

Level 2 is coming soon. Its code is all in `hospital-simulator/index.html`, with no build step.
