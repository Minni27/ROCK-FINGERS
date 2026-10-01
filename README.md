# Rock Fingers

Play real songs with your hands. Your webcam tracks your hands (MediaPipe, in the browser; nothing leaves your machine) and a Web Audio guitar/synth plays the chords.

- **Play hand:** pinch to play the next chord, hold to let it ring
- **Other hand:** height = tone, tilt = vibrato, finger spread = space (echo + reverb), pinch = back, fist = stop
- **Song / Pads modes**, clean guitar / synth pad / rock sounds, per-song strum and picking patterns, drum machine
- **Backing track:** bass + drums play the song in time; hold a pinch and your pattern follows the chord changes
- **Guitar chord diagrams** (with capo shapes) and **stats**: accuracy trend and trickiest chord changes
- **Works without a camera:** tap / click to play, drag the tone bar; phone layout with a compact menu
- **🎓 Training:** gestures warm-up, meet the chords, timed play-along with scoring, pads from memory. Lessons are generated for any song you add.

## Run locally

```bash
node serve.js
```

Then open http://localhost:5179. The camera needs `localhost` or HTTPS.

## Deploy

A static site with no build step: import the repo into Vercel with framework preset "Other".
