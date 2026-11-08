# Backline Percussion

A full set of percussion instruments for the iPad, played with your fingers. It runs in Safari and can be added to the Home Screen like an app. Every sound is generated live in the browser, so there are no sample files, and it keeps working offline once it has been opened.

## Kits

- **Drum Kit:** kick, snare (tap the hoop for a cross-stick), three toms, hi-hat with pedal, crash, splash, china and ride with bell. Optional left-handed layout.
- **Latin:** quinto, conga, tumba, bongos, timbales, cowbell, agogô, claves, güiro and shaker.
- **World:** djembe, cajón, darbuka, frame drum, udu, tabla (dayan and bayan), tambourine and caxixi.
- **Orchestra:** four tuned timpani, concert bass drum, snare, clash and suspended cymbals, tam-tam, triangle, mark tree and sleigh bells.
- **Electronic:** 16 analog drum-machine voices on a pad grid.
- **Mallets:** marimba, vibraphone (pedal and motor), xylophone and glockenspiel.
- **Handpan:** a ding and eight tone fields, in four scales.

## Playing

- Play with several fingers at once.
- Where you strike matters. Drums are fullest in the center. Congas and djembe give bass, tone or slap depending on the spot. Cymbals get louder toward the edge.
- Apple Pencil pressure sets the volume.
- Press and hold a cymbal, the tam-tam or the triangle to damp it.
- Drag across the güiro or the mark tree. Hold a timpano, the bayan or the udu and drag up to bend the pitch.
- **Metronome:** 40 to 240 BPM, 2/4 through 7/4.
- **Looper:** tap record, play a groove, then tap record again to close the loop. Tap record once more to layer on top. With the metronome on, loops snap to whole bars. A loop keeps playing when you switch kits.

## Put it on the iPad

1. In this repository on GitHub, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, then **Save**.
3. After a minute the page is live at `https://<your-username>.github.io/<repository-name>/`.
4. Open that address in **Safari** on the iPad, tap **Share**, then **Add to Home Screen**.

It opens full screen from its icon. If you hear nothing, turn up the iPad's volume.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app: layout, sound engine and instruments |
| `sw.js` | Offline support |
| `manifest.webmanifest`, `icon-*.png` | Home Screen name and icons |
