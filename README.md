
## My project Deliverables

- **Title: Temporary Euphoria**
- **Live page: [your url](https://benfitz1110-dev.github.io/myproject-oak-tree/)**
- **Coordinates: lat: 40.000222, lon: -83.013446**
- **Intent: Our object brings out the contrast between natural and artificial happiness, challenging the viewer to see which one they will pick**
- **Screenshot: <img width="3024" height="4032" alt="ARTraining2Location" src="https://github.com/user-attachments/assets/24614163-5741-4adc-9601-5e0ae5549bbd" />**
- **SUBMIT ON CARMEN -- Video: .mp4, stable shot, < 2 min.**

## Run and test

- Open the deployed site on a phone over HTTPS, tap **Start**, and allow location access. Walk to the temporary coordinates in `index.html` to unlock the models. The project coordinates above are separate from the current test locations.
- Add `?fake` to the URL for the full desktop walkthrough without GPS.
- Use `?preview=1` for the cigarette and ashtray or `?preview=2` for the laptop. These let you test the 3D viewer and **View in AR** without visiting either spot. The iOS Quick Look fallback displays a static model because the automatically generated USDZ does not carry animations.
- In the browser 3D viewer, the laptop waits four seconds once the model has loaded and then loops continuously. The cigarette plays each animation track three times and holds the final pose.
- Add `?scout` to record test coordinates on the device.
- For local testing, run `python -m http.server 8000` here and open `http://localhost:8000/?fake`. The viewer loads from a CDN.
- For GitHub Pages, put `index.html` and `models/` together at the root of the Pages publishing source. The older `newIndex.html` can be removed once the root page is working.
