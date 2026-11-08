# Learning Log

## Copilot interactions

| Prompt or question | What Copilot suggested | What I accepted, changed, or rejected | How I checked it |
|---|---|---|---|
| add a hover effect to the project titles in style.css so they turn amber when you hover them | Added a color transition to `.project h3` and a `.project h3:hover` rule that sets the color to amber | Kept it as is, it matched the buzzer colors already on the site | Opened index.html in my browser and hovered over each project title |
| explain how the buzz button JavaScript at the bottom of index.html works | Explained that it wraps each word in a span, reveals one every 140ms, and on buzz stops the timer, shows the answer, and gives +15 if you buzz before the (*) or +10 after | Accepted the explanation, didn't change any code | Opened the site and buzzed early (got Power! +15), then reloaded and buzzed after the (*) (got +10) |
| check if the nav and the tossup question work on a phone-width screen and fix anything that breaks in style.css | Tested the page at 375px and 320px wide and found no overflow. The nav wraps, the question and Buzz button fit, and the links work, so it said no CSS change was needed | Agreed, left style.css unchanged | Opened dev tools phone view and checked the nav, the tossup, and the Buzz button myself |

## Testing

- [x] Live URL opens in a private/incognito window without signing in
- [x] All required sections are there with my own content
- [x] Navigation, GitHub profile, and project links work
- [x] Readable on desktop and at phone width
- [x] Photo loads and has alt text
- [x] No private info on the site, repo, or screenshots
- [x] Latest change shows up on the published site

## Reflection

GitHub stored my code and kept track of every change I made, and GitHub Pages is what turned that repo into an actual website at nikflash100.github.io. VS Code made it easy to edit the files and commit and sync them without leaving the editor. Copilot helped by changing the code exactly how I asked, like adding the amber hover on the project titles, and it also explained code and tested the site at phone sizes for me.

The hardest part was making the tossup at the top of the site. I had to figure out how to write it like a real quizbowl question and get it to read out word by word.

One piece of code I can explain is the buzz button. It splits the question into words and shows one every 140 milliseconds. When you buzz, it checks if you buzzed before or after the (*). Before gives +15 for a power and after gives +10.

Next time I want to add more tossups to the site so you can play through a few about my different projects.