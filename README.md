## JAVASCRIPT CODE QUALITY BOT

Snarky code style reviewer, now automated _and_ consistent!

This is a 'bot' written in bash that will run eslint on all the files you've added/changed since the last commit and _automagically_ make snarky remarks if you have errors. Probably best used as a pre-commit hook, or as a rage-inducing test for your CI pipeline (you are of course welcome to place it anywhere ~~where it it likely to reject the most code~~ you might find it useful). 

Requires __git__ and __eslint__, for obvious reasons. Eslint config is not included. Feel free to replace eslint with prettier, flake8, checkstyle, or whatever else you use. 

Inspired by the code quality XKCDs, which is also where the snarky comments come from. Replace the 'XKCD' in 'XKCD-BOT' with the ALL-CAPS name of that reviewer on your team who derives _way too much_ pleasure from being an asshole and slowing everyone down by complaining endlessly about very arbitrary code style 'issues' (and whose job is now mostly automated) for optimal results.

Unfortunately _xkcd-bot_ does not know how to complain about your variable names. I'm working on it. 
