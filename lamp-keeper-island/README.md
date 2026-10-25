# Lamp Keeper Island

A cozy first-person game about keeping a lighthouse on a small island, for one or two players.
The whole game is one file, `index.html`. It runs in any modern browser on desktop or mobile.

## Put it online with GitHub Pages

1. Create a new repository on GitHub, e.g. `lamp-keeper-island`.
2. Upload `index.html` and this `README.md` to it (**Add file → Upload files**, then **Commit changes**).
3. Open the repository's **Settings → Pages**. Under **Build and deployment**, set **Source** to
   *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, and click **Save**.
4. After a minute or two the game is live at `https://<your-username>.github.io/<repository-name>/`.

## Play together

Both players open the same GitHub Pages link, each on their own device.

1. **Host:** Settings → *Play together* → **Host**. A 6-character code appears.
2. **Friend:** Settings → *Play together* → **Join**, type the code, then **Connect**.
3. Either player can press **Leave** to stop. The friend goes back to their own saved island.

What is shared: the host's island, time and weather, coins, firewood, garden, eggs, stew pot, barrels,
lamp oil and lens, paint, hung photos, doors, the rowboat (one steers from the front, one rides in back)
and the dog (it follows whoever last stood it up). Each player keeps their own hotbar and keeper.
The night only ends when both keepers are in bed.

Connections go directly between the two browsers. PeerJS's free public service is used only to help them
find each other, so both players need to be online at the same time. Some very strict networks
(certain school or office Wi-Fi) block direct connections; a home connection or phone hotspot usually works.

## Controls

- **Desktop:** WASD to walk (Shift to sprint), mouse to look, click to use, right-click for extras.
- **Mobile:** joystick to walk (push it all the way to sprint), drag to look, tap to use.
  Joystick side and opacity are in Settings.
