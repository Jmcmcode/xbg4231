# Rosalie's Frog Hop

A maths game for the iPad, made for Rosalie: adding and taking away, with a frog that hops along a number line to help.

Play it at https://jmcmcode.github.io/xbg4231/

Her name is set once, as `NAME` near the top of the script in `index.html`. It appears in the greeting, the praise, the animals' lines, the results, the level-ups, the sticker book and some story sums, and the spoken praise uses it too.

## Games

**Beat the clock:** 20 adding and taking-away sums up to 20, against a timer: Warm-up (3 minutes), Test speed (2 minutes) or Lightning (1½ minutes). It starts with a 3-2-1-Go countdown and keeps a personal best for each.

**Up to 20 (practice with help):** adding, taking away, missing numbers, or a mix of all three.

**Bigger sums (like the homework):** word sums ("The total of 43 and 18 is ☐"), missing numbers up to 2000 ("68 + ☐ = 100"), adding three numbers, and story sums. The frog shows the "friendly jumps" method: count up to the next ten, then the next hundred, then the rest.

## Rewards

- After each right answer an animal pops up with a silly noise and a pun ("Moo-velous!"), with confetti.
- Getting 3, 5 or 10 in a row brings a banner, then an animal parade and confetti rain.
- At the end of a round the stars count up, a new sticker is revealed, and there's a joke to read.
- Stars build up her level, and the frog unlocks a new outfit at each level: bow tie, sunglasses, party hat, superhero cape, crown and gold medal.
- A daily streak counter shows how many days in a row she has played.

## Surprises, dress-up and records

- **Random surprises:** about one right answer in six or seven (never two close together) triggers something rare instead of the usual animal: Fly Snack (the frog's tongue catches a fly, then it burps), Giant Boing, Sneezy Cow, Duck Stampede, Golden Fly (tap it for 3 bonus stars), Disco Frog, Dino Stomp, and a Fireworks Finale at the end of good rounds. Three are there from the start; the rest unlock with levels. Ones she hasn't found yet come up more often, and the records page shows which she's found.
- **Slapstick on wrong answers:** sometimes the frog falls in the pond with a splash, the monkey blows a raspberry, or the frog goes "Whoooops!" with a slide whistle. It's always followed by "have another go".
- **Dress-up room:** she names her frog and chooses its colour (green, pink, purple, blue and orange from the start; gold and rainbow unlock late) and which unlocked outfits it wears.
- **Records:** sums right, rounds played, perfect rounds, best streak, most days in a row, stars, best Beat the clock times, and surprises found.
- **Milestones:** banners and cheers at 25, 50, 100, 150, 200 sums right and beyond, for a new best streak, and for golden fly bonus stars.
- **Jokes:** 65, never repeating until she has seen them all.
- **Tap the frog** on the home screen and it jumps and makes a silly noise.

Beat the clock stays quick: no surprises or slapstick during the timed sums, only at the end.

## Learning from mistakes

- First wrong answer: "have another go". Second wrong answer: the frog shows the jumps and says the answer.
- At the end of a round, "Let's fix the tricky ones" goes through each sum she got wrong. It shows what she typed and the right answer, a tip for that exact sum (make 10 first, near doubles, take away 10 then add 1 back, count up when the numbers are close, friendly jumps to 100), and the frog can act it out. Then she can try those sums again.
- Sums she gets wrong are saved on the iPad and come back in later rounds until she gets them right.

## Putting it on the iPad

It's a single page, `index.html`, plus its home-screen icons (`apple-touch-icon.png`, `icon-192.png`, `icon-512.png`) and `manifest.webmanifest`. There's no build step. It's hosted on GitHub Pages from this branch. Open it in Safari, tap **Share → Add to Home Screen**, and it opens full-screen like an app, with the frog icon and the name "Rosalie's Sums". Sounds play through the iPad speaker, so check the volume and that silent mode is off.
