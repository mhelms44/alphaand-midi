# alphaand-midi
Version control and central repo for MIDI tracks utilized for controlling Fractal AxeFx units. For live performances/practices, my band leverages MIDI output from Reaper for automating all AxeFx changes. The benefit is that there is no need to manually control presets or program seperate foot controllers, deal with carrying additional gear to gigs, less points of failure, etc. 

The biggest downside to all of this is managing the MIDI between the two AxeFx units and ensuring there is consistency between projects and some form of version control. This repo is setup with the following design goals:

- Master branch should be the most recent MIDI tracks utilized for current show/practice sessions.
- Individual branches for each song that are still in development and will eventually be merged with master. 
- Legacy branches that aren't intended for live use, but may have archival value. 

The added benefit is that we won't have to rely on sharing files/keeping up with who has the most recent versions/etc. Everything is centralized here, and there is no concern over which Reaper project has the most up to date MIDI or which file is older or has incorrect CC messages, etc. 
