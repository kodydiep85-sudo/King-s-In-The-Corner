KINGS CORNER - WEBSITE FILES
============================

What's in this folder
  index.html             the whole game
  icon.svg               the site icon
  manifest.webmanifest   lets phones "Add to Home Screen" like an app

Put it online for free (about 2 minutes)
  1. Unzip this folder.
  2. Go to https://app.netlify.com/drop
  3. Drag the whole "kings-corner-site" folder onto that page.
  4. Netlify gives you a link like https://something.netlify.app
     Send that link to your friends.
  Make a free Netlify account if you want to keep the site and rename it.

Other free hosts that work the same way
  - Cloudflare Pages: Create project > Direct Upload > drop the folder.
  - GitHub Pages: upload these files to a repository, then
    Settings > Pages > Deploy from branch "main".

Playing with friends on different devices
  1. Everyone opens your website link.
  2. One person types their name and taps "Host a game".
     They get a 4-letter code.
  3. Friends type their name and the code, then tap "Join".
  4. The host taps "Start game" when everyone is in (2 to 4 players).
  - The host must keep the page open until the game ends.
  - If a friend drops out, the game plays for them until they
    join again with the same code on the same device.
  - Devices connect directly using the free PeerJS service
    (https://peerjs.com). On a few strict school or work networks
    direct connections can be blocked; switching to mobile data fixes it.

Playing against the computer works offline once the page is loaded.

Note: opening index.html straight from your computer works for the
computer mode. Online play works best from the real website link.
