# Alien Dispensary — Day 1 & Day 2

A *Papers, Please*-style comedy game. You're the only human budtender at The Greenery Room's orbital station, in a galaxy where cannabis is an intergalactic pastime for every species — and every species reacts to it differently.

## Play it

Open `index.html` in a browser, or play the GitHub Pages version once Pages is enabled (Settings → Pages → Deploy from branch `main` / root):

https://thefixinhixon.github.io/alien-dispensary/

## How to play

1. Read the morning briefing, then **Clock In**. Pick your day on the briefing screen — Day 2 unlocks its own rules, handbook edition, and shift report.
2. For each customer:
   - Read what they're asking for (they will describe it terribly).
   - Check their **Galactic ID**, **permit**, and the **Species Tolerance Registry** in the in-game Species Handbook. Species age, dose, and react differently.
   - Pick the right product from the shelf — or pick nothing and deny.
   - Slam **APPROVED** or **DENIED**.
3. You're scored on credits and tips for perfect matches, compliance bonuses for correct denials, star reviews, and manager Deb's commentary. Bad sales earn **ICD citations — 3 citations and you're fired**.

**Day 1** introduces the basics: Grob the Boulderian, Kyle the THC% Guy, Timble the underage Ent, a robot who needs CBD oil for his literal joints, a sentient flower looking for romance, and one completely normal customer who is definitely not an ICD inspector.

**Day 2** is worse. New Federation rules: Venus just legalized (Venusians photosynthesize — edibles hit double, and they're severely allergic to myrcene), Schrödinger's Haze is recalled (140% THC COA — always deny), and daily limits are enforced *per body*. Kyle returns demanding a refund, a 47-drone Hive Mind argues it gets 47x the daily limit, a vendor rep tries to drop unmanifested samples with no S2S paperwork, and the final customer is a *real* ICD inspector.

## Tech

Pure static single-file game (`index.html`) — no backend, no Firebase, no build step. All state lives in the browser and resets on reload. Sound effects are WebAudio (mutable in-game); light and dark modes included.

*Prototype — Days 1–2. Feedback from real budtenders especially welcome.*
