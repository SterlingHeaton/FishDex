# FishDex
Minecraft fabric mod to index all of the tropical fish

## Planned Features

### MVP (Minimum Viable Product) aka V1
- Tracks all the unique fish caught (or at least in your inventory).
- Caught a new fish? Get a notification.
- Open a UI via key bind to see all of the unique fish, which ones you've caught, and the ones you need.
- Quick stats.

### Either future features or scope creep their way into V1
- Share option
  - Lets you 'export' your dex as a string to share with people.
  - Lets you 'import' a shared string to see which fish the other person has caught.
  - Lets you see the differences between your dex and the shared dex.

### Way future/Maybe won't see the light of day
- Create some sort of website to show everyone's current FishDex.
- Server-wide FishDex

## FAQ

### How will fish be registered to your FishDex?
Two ways: Catching the fish in a bucket or having the fish in your inventory.

### How will the UI work?
Planning on opening the UI with a keybind, maybe a command as well.

There are 2700 different kinds of tropical fish that can spawn naturally. It wouldn't be ideal to shove everything into a single page. So I'm planning on using a tab system. The V1 plan is to have an all tab (maybe, maybe not, have to see performance) and tabs for each fish type. I might have sub-tabs as well for primary/pattern colors, but that is TBD.

Additionally, I've been thinking of a search function where you select different properties you want to see, like types, colors, or patterns.
