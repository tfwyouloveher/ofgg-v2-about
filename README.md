# OFGG v2

### The second iteration of the Online Frozen Gif Generator

A modern from-scratch update of the original Online Frozen Gif Generator, which was a
[warmly received](https://www.reddit.com/r/Frozen/comments/3ymbov)
2015 solo project by a younger and far more naïve myself.

Unfortunately, the sources for the original have been completely lost to the sands of time,
but thankfully a helpful user (shoutout to u/Demian_Dillers) submitted a screenshot of how it looked on their machine:

### Version 1 (ca. 1997, colorized):

![OFGG v1](https://i.imgur.com/NHDx6SG.png)

### Not great.

Users had to download the movie file separately. It was not at all mobile-friendly.
There was no preview function, no fps or subtitles options, and worst of all:
*it was entirely written in PHP*. 😓

## Presenting Version 2:

![OFGG v2](https://i.imgur.com/6Rduvg1.png)

#### A complete rewrite, v2 promises the features that v1 so desperately lacked:

- Mobile-first, modern design
- Live preview of the movie clip, allowing for scrubbing to the desired timestamp
- FPS and subtitle configurability
- In-browser gif preview generator, prior to full-size gif creation on server
- Completely written in Javascript, using Node.js and React 😎
- Gif preview *fully encodes* a new gif file *in-browser*, using a custom cutting-edge WebAssembly solution 🤯

#### What's next:

- Allow users to download movie files to their browser so app can be used offline (using ServiceWorker)
- Let users select which movie file to use for local preview, exchanging quality for disk space themselves
- Add other Frozen media, e.g. the short films, trailers, and upcoming sequel 🥰

## Okay, so how do I use it?

Just head on over to [frozengifs.com](https://frozengifs.com) and get giffing!

**If you encounter issues:** first take a look at the Issues tab up at the top to see if anyone else has reported your issue.
Not seeing it anywhere? Great, go ahead and report it yourself using the big green *New Issue* button on that tab.
If you do find your issue, you can subscribe to updates on it to know when it gets fixed.

**If you have a brilliant feature request:** same as the above steps.
Try to keep feature requests reasonable, we're a two person team.

**Wanted:** a good camrip of the sequel. If you find one, *don't open an issue here*. We don't want to invite trouble here.
Instead, DM me on [Twitter](https://twitter.com/tfwyouloveher) or [reddit](https://www.reddit.com/u/tfwyouloveher) and we'll sort it out.

<3 -- *tfwyouloveher*

## Credits

- A huge (continuing) thank you to @forresthopkinsa, my only collaborator and the singular reason this project is at all maintainable.
- /r/Frozen, the most remarkable, friendly group of people you might ever meet on the internet, my love for whom motivated me every step of the way.
- Jennifer Lee, Kristen-Anderson Lopez, Bobby Lopez, Chris Buck, Peter del Vecho, Brittney Lee, Christophe Beck, Idina, Kristen, Josh, Jonathan, Santino, Evan, Sterling, and the rest of the enormous cast, for creating the most moving animated franchise of our time.
