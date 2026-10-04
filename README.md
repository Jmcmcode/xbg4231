# Rosalie's Frog Hop

A maths game for the iPad, made for Rosalie: adding and taking away, with a frog that hops along a number line to help.

Play it at https://jmcmcode.github.io/xbg4231/

Her name is set once, as `NAME` near the top of the script in `index.html`. It appears in the greeting, the praise, the animals' lines, the results, the level-ups, the sticker book and some story sums, and the spoken praise uses it too.

## Games

**Beat the clock:** sums up to 20 against a timer, with a 3-2-1-Go countdown and a personal best for each:
- **Sprint:** as many as she can in 1 minute. The score only counts up, so there's never an unfinished test, just a best to beat.
- **Warm-up** (20 sums in 3 minutes), **Test speed** (20 in 2 minutes) and **Lightning** (20 in 1½ minutes).

**Speed builders:** short rounds (12 sums) on one family of key facts at a time, in the order to learn them: Bonds to 10, Doubles, Near doubles, Add and take 10, Bonds to 20, Cross 10. Each round opens with the trick for that family, and mixes adding, taking away and missing numbers from the same facts.

**Fast facts:** every up-to-20 sum is timed. Adding, taking away and missing-number versions all count as the same fact (8 + 5, 13 − 5 and 5 + ☐ = 13). A fact goes gold when she gets it right first time in 4 seconds or less, three times. The Fast facts page shows the 52 key facts by family, with each row's progress and a Practise button, and gold facts are celebrated at the end of a round. Facts she has tried but is still slow at come back more often in every up-to-20 mode, including Beat the clock.

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
- **Rosalie's picture:** in the dress-up room you can choose a picture of Rosalie from the iPad's photos. A plain white background is made see-through, and at the end of each round she jumps up from the bottom of the screen and cheers (bigger for great rounds), and appears next to her frog when she levels up. The picture is saved only on that iPad. It is not part of this repository or the website.
- **Voice:** the spoken praise uses the iPad's own voices. The game picks the most natural English one it can find (preferring British voices marked Enhanced or Premium), and the dress-up room has a chooser with a "Try it" button and a "No voice" option. For the best result, download a voice on the iPad first: Settings → Accessibility → Spoken Content → Voices → English.
- **Sound switch:** "🔊 Sound on" at the bottom of the home screen, and a speaker button next to Home while playing. It turns off all sound, including the voice, and the iPad remembers the setting.

## Learning from mistakes

The game is built to make mistakes feel safe, because she's a bit of a perfectionist:

- **Have a go first.** The frog's help button reads "Have a go first, then I can help" until she has tried once. Tapping it early gets a gentle "Your brain can do it" nudge. There's deliberately no limit on help once she's tried.
- **Mistakes are welcome.** A wrong first answer gets a soft tone, a gentle wiggle and a message like "Good try, Rosalie! Mistakes help your brain grow. Have another go!"
- **Fixing it counts.** Getting it right on the second go, on her own, earns a silver star (worth a full star) and keeps her run going. If the frog helps, she gets a green "learned with Hoppy" star but no point, and her run restarts.
- **Second wrong answer:** the frog shows the jumps and says the answer.
- **End of round:** "Brave brain: 8 sums on your own!", "You fixed 2 mistakes! Your brain grew!", and a round with no frog help at all earns "Brave brain! Every sum on your own!" plus 2 bonus stars.
- **Learning from the tricky ones:** goes through each sum she got wrong, showing what she typed ("Mistakes help us learn!"), the right answer, a tip for that exact sum (make 10 first, near doubles, take away 10 then add 1 back, count up when the numbers are close, friendly jumps to 100), and the frog acting it out. Then she can try those sums again.
- Sums she gets wrong are saved on the iPad and come back in later rounds until she gets them right first time.

## Updates

Each commit stamps `index.html` with a build time (`<meta name="build">`, set by a local pre-commit hook). When the home screen is showing, the game fetches a fresh copy of itself and, if the build is newer, reloads. It never reloads mid-round. The Records page shows the current version.

## Putting it on the iPad

It's a single page, `index.html`, plus its home-screen icons (`apple-touch-icon.png`, `icon-192.png`, `icon-512.png`) and `manifest.webmanifest`. There's no build step. It's hosted on GitHub Pages from this branch. Open it in Safari, tap **Share → Add to Home Screen**, and it opens full-screen like an app, with the frog icon and the name "Rosalie's Sums". Sounds play through the iPad speaker, so check the volume and that silent mode is off.
