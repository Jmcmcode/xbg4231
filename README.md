# Rosalie's Frog Hop

A maths game for the iPad, made for Rosalie: adding and taking away, with a frog that hops along a number line to help.

Play it at https://jmcmcode.github.io/xbg4231/

Her name is set once, as `NAME` near the top of the script in `index.html`. It appears in the greeting, the praise, the animals' lines, the results, the level-ups, the sticker book and some story sums, and the spoken praise uses it too.

## Games

**Beat the clock:** 20 adding and taking-away sums up to 20, against a timer: Warm-up (3 minutes), Test speed (2 minutes) or Lightning (1½ minutes). It starts with a 3-2-1-Go countdown and keeps a personal best for each.

**Up to 20 (practice with help):** adding, taking away, missing numbers, or a mix of all three.

**Bigger sums (like the homework):** word sums ("The total of 43 and 18 is ☐"), missing numbers up to 2000 ("68 + ☐ = 100"), adding three numbers, and story sums. The frog shows the "friendly jumps" method: count up to the next ten, then the next hundred, then the rest.

## Calm sums, fun at the end

The sums are kept calm so she can concentrate: a right answer gets a soft chime, a few words ("Brilliant, Rosalie!") and a star; a wrong answer gets a gentle tone and "have another go". Nothing pops up, flies across or covers the sum while she's working, in any mode.

All the fun comes when a round is finished, in this order:
1. The stars light up one at a time with rising pings, and the voice reads out her result.
2. A fanfare, with confetti and an animal parade for a great round.
3. **A surprise, every round:** Fly Snack (the frog's tongue catches a fly, then it burps), Giant Boing, Sneezy Cow, Duck Stampede, Golden Fly (tap it for 3 bonus stars), Disco Frog, Dino Stomp, plus a Fireworks Finale after good rounds once she reaches Frog Royalty. Three are there from the start and the rest unlock with levels. Ones she hasn't found yet come up more often.
4. Banners for anything special: a new record, best streak ever, a new surprise found, milestones (25, 50, 100, 150, 200 sums right and beyond), golden fly stars.
5. A drumroll and a new sticker (gold for a perfect round), and a joke (64 of them, none repeated until she's seen them all).
6. A level-up when she reaches one: her frog gets a new outfit and a new surprise unlocks.

## Coming back

- **Dress-up room:** she names her frog and chooses its colour (green, pink, purple, blue and orange from the start; gold and rainbow unlock late) and which unlocked outfits it wears: bow tie, sunglasses, party hat, cape, crown, gold medal.
- **Records page:** sums right, rounds played, perfect rounds, best streak, most days in a row, stars, best Beat the clock times, and surprises found (unfound ones show as "???" or locked).
- **Sticker book**, a daily streak counter, and a frog on the home screen that jumps and makes a silly noise when tapped.
- **Sound switch:** "🔊 Sound on" at the bottom of the home screen, and a speaker button next to Home while playing. It turns off all sound, including the voice, and the iPad remembers the setting.

## Learning from mistakes

- First wrong answer: "have another go". Second wrong answer: the frog shows the jumps and says the answer.
- At the end of a round, "Let's fix the tricky ones" goes through each sum she got wrong. It shows what she typed and the right answer, a tip for that exact sum (make 10 first, near doubles, take away 10 then add 1 back, count up when the numbers are close, friendly jumps to 100), and the frog can act it out. Then she can try those sums again.
- Sums she gets wrong are saved on the iPad and come back in later rounds until she gets them right.

## Putting it on the iPad

It's a single page, `index.html`, plus its home-screen icons (`apple-touch-icon.png`, `icon-192.png`, `icon-512.png`) and `manifest.webmanifest`. There's no build step. It's hosted on GitHub Pages from this branch. Open it in Safari, tap **Share → Add to Home Screen**, and it opens full-screen like an app, with the frog icon and the name "Rosalie's Sums". Sounds play through the iPad speaker, so check the volume and that silent mode is off.
