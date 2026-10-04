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

## Learning from mistakes

- First wrong answer: "have another go". Second wrong answer: the frog shows the jumps and says the answer.
- At the end of a round, "Let's fix the tricky ones" goes through each sum she got wrong. It shows what she typed and the right answer, a tip for that exact sum (make 10 first, near doubles, take away 10 then add 1 back, count up when the numbers are close, friendly jumps to 100), and the frog can act it out. Then she can try those sums again.
- Sums she gets wrong are saved on the iPad and come back in later rounds until she gets them right.

## Putting it on the iPad

It's a single page, `index.html`, plus its home-screen icons (`apple-touch-icon.png`, `icon-192.png`, `icon-512.png`) and `manifest.webmanifest`. There's no build step. It's hosted on GitHub Pages from this branch. Open it in Safari, tap **Share → Add to Home Screen**, and it opens full-screen like an app, with the frog icon and the name "Rosalie's Sums". Sounds play through the iPad speaker, so check the volume and that silent mode is off.
