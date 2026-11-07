# Learning Log

## Copilot interactions

| Prompt or question | What Copilot suggested | What I accepted, changed, or rejected | How I checked it |
|---|---|---|---|
| add a hover effect to the project titles in style.css so they turn amber when you hover them | Added a color transition to `.project h3` and a `.project h3:hover` rule that sets the color to amber | Kept it as is, it matched the buzzer colors already on the site | Opened index.html in my browser and hovered over each project title |
| explain how the buzz button JavaScript at the bottom of index.html works | Explained that it wraps each word in a span, reveals one every 140ms, and on buzz stops the timer, shows the answer, and gives +15 if you buzz before the (*) or +10 after | Accepted the explanation, didn't change any code | Opened the site and buzzed early (got Power! +15), then reloaded and buzzed after the (*) (got +10) |

## Testing

- [ ] Live URL opens in a private/incognito window without signing in
- [ ] All