## JAVASCRIPT CODE QUALITY BOT

Snarky code style reviewer, now automated _and_ consistent!

This is a 'bot' written in bash for people who for some reason don't want to install python that will run eslint on all the files you've added/changed since the last commit and _automagically_ make snarky remarks if you have errors. Probably best used as a pre-commit hook (but you are welcome to place it anywhere you might find it useful). 

Requires __git__ and __eslint__, for obvious reasons. Eslint config is not included. Feel free to replace eslint with pep8 or checkstyle or whatever else you use. 

Inspired by the code quality XKCDs, which is also where the snarky comments come from. Replace the 'XKCD' in 'XKCD-BOT' with the ALL-CAPS name of that reviewer on your team who derives _way too much_ pleasure from being an asshole and slowing everyone down by complaining endlessly about very arbitrary code style 'issues' (and whose job is now automated) for optimal results.
