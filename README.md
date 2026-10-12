# Alien Dispensary — Day 1

A *Papers, Please*-style comedy game. You're the only human budtender at The Greenery Room's orbital station, in a galaxy where cannabis is an intergalactic pastime for every species — and every species reacts to it differently.

## Play it

Open `index.html` in a browser, or play the GitHub Pages version once Pages is enabled (Settings → Pages → Deploy from branch `main` / root):

https://thefixinhixon.github.io/alien-dispensary/

## How to play

1. Read the morning briefing, then **Clock In**.
2. For each of the 10 customers on Day 1:
   - Read what they're asking for (they will describe it terribly).
   - Check their **Galactic ID**, **permit**, and the **Species Tolerance Registry** in the in-game Species Handbook. Species age, dose, and react differently — an 87-year-old Ent is a minor, a 5 kg Moon Sprite cannot have a 100 mg bar, and limonene can be a serious allergen.
   - Pick the right product from the 10-product shelf — or pick nothing and deny.
   - Slam **APPROVED** or **DENIED**.
3. You're scored on credits and tips for perfect matches, compliance bonuses for correct denials, star reviews, and manager Deb's commentary. Bad sales earn **ICD citations — 3 citations and you're fired**. Finish the shift to get your end-of-shift report and rank.

Day 1 customers include Grob the Boulderian, Kyle the THC% Guy, Timble the underage Ent, a robot who needs CBD oil for his literal joints, a sentient flower looking for romance, and one completely normal customer who is definitely not an ICD inspector.

## Tech

Pure static single-file game (`index.html`) — no backend, no Firebase, no build step. All state lives in the browser and resets on reload. Sound effects are WebAudio (mutable in-game); light and dark modes included.

*Prototype — Day 1 only. Feedback from real budtenders especially welcome.*
