---
layout: "post"
title: Magic Guest Article&colon; Ariamaki on Card Mechanics
date: 2018-11-15 00:11:00 -0700
author: "Ariamaki"
categories: [Media, Guest Article]
excerpt_separator: <!--more-->

# Contributor stuff
contributor: true
---

Hello! I’m your guest author for the week, Ariamaki. I’ve got a very wide field of interests and expertise, arguably too wide on the first half and not deep enough on the second, but I still pride myself in versatility and balance. Lately that has ranged from adding content to games like Monster Prom (_you’ll know my credit when you see it_) and Wizard of Legend ([_the Scales_](https://twitter.com/Oreaven/status/998752862409650176) _may not be the best credit to my sense of balance_) all the way to working on board games with my good friend, collaborator, and general oddity [Andy ](http://oddmall.info/)[Hopp](http://cononthecob.com/). In the future I might dig into more arcane and esoteric topics, but today’s going to be a simple straightforward piece on game design.

We’re going to look at games from genres that have a lot in common, games that are often considered competitors, focusing on big broad-strokes differences in their core systems. This is all about just observing what makes them tick, why those differences are there in the first place, and drawing some basic conclusions from there. In the future I’ll probably take a step sideways-and-back to talk about game design from a more basic level or discuss the specific mechanics and how-to’s of these games, but right now?

Let’s make some hash.

<!--more-->

On the platter for comparison are three card games, in their digital standalone incarnations where relevant ([Magic](https://magic.wizards.com/en/mtgarena), [HEX](http://hextcg.com/), [Hearthstone](https://playhearthstone.com/en-us/)). The focus is going to be on where their designs have commonalities and differences, the intersection points of their (metaphorical, as my art skills are bunk) Venn diagrams.

I cannot guarantee we’ll be covering all of that this one time, but I hope to be back in the future to do my thing again as needed. So if we only end up covering the card games? Just think of those other names and links as flavorful tantalizing IOUs, and maybe familiarize yourself with the games before I make it back here.

### Section 1: Card Me

A reminder before we kick off proper: This is going to be a fairly high-level overview, and I don’t mean high-level as in “complex” I mean it like “as seen from a plane”: We’re not deep in the guts here, this is an aerial view. Details will be lost at this resolution, so to speak. Little car-mirror warning sign that reads: Game designs seen in this article are more complicated than they appear.

When looking at card games the default would be to do a simple two-part comparison of the biggest kids on the playground, the venerable and incredible **Magic: The Gathering** and the young upstart fed fat off Daddy BlizzActivision’s money, **Hearthstone**, nee Hearthstone: Heroes of Warcraft.

But just comparing those two alone doesn’t do a lot for us here, so instead we’re looking at a third game that _deserves_ as much or more attention than others, but sadly doesn’t get it: Cory Jones’ beautiful-but-sickly mindbaby, the deeply underappreciated **HEX: Shards of Fate**.

For the sake of pacing, we’ll back up and do a quick overview of each game’s history and concepts and then dig a little deeper into their niches by comparing the four of them in more specific ways. To be clear, I’m assuming at least some basic understanding of what a card game is (and not in the Poker-Rummy-Koikoi sense) and more generally what these card games look like. Google judiciously, click links, etc.

But for now, the overviews.

Magic is the classic, the king, Allfather, the OG. Most other card games in the modern era derive at least a hefty chunk of their DNA from this. Two players have customized decks of standardized cards with a goal of defeating the other: That’s true for every one of these games. In this particular game, that defeat will come in one of… Um. Roughly 37 different ways if we include your opponent making a games rules violation? Oh.

See that’s the issue with Magic: It’s got a lot of history. Sure, to a beginner “Make the opponent’s life go to 0” is the sole win condition. Get a little more experience under your belt and “Make the opponent’s deck run out of cards” becomes an apparent option. Even further and specific cards with their own built-in wincons like Approach of the Second Sun show up.

![image1](/assets/images/magic2/approach-of-the-second-sun-hi-res.jpg)

Even further beyond that and there’s stuff like “Judge-Call Tribal”, the half-joking archetype of legend dedicated to tricking your opponent into making illegal plays and getting them disqualified from the tournament or booed away from the game table.

…No seriously people have tried that: Google the Flores Dakra Labyrinth or click [here-ish](http://fivewithflores.com/2014/05/dakra-mystic-spirit-labyrinth-combo-controversy/).

![image2](https://i.imgur.com/removed.png)

We can’t go deep on every game’s rules today (aerial view, not inside the engine), but the short version is that Magic is huge and complex and will very likely outlive every person reading this.

HEX is the closest to Magic on this list, to the degree where a few trade dress lawsuits got thrown around early on, not because of their gameplay similarity, but because of certain words being used for certain zones: Things like ‘the place used-up cards go’ being ‘the Graveyard’. That got settled out of court (HEX’s dead card zone is now the Crypt, and so forth) but it does set the tone here: HEX is like an alternate universe’s Magic. Remarkably similar core rules, but the differences are the entire reason I’m here writing this.

The biggest difference is that HEX leans hard into the digital space, and it does so even more than our next game: Cards can change mid-battle, duplicate themselves, copies of stuff made from thin air are fully realized cards that can go back to your hand or deck. In Magic, those would be ‘tokens’ that go away back outside the game when they’re done with. Cards (not just units, but even spells) can be permanently buffed across a battle’s duration even if they leave the field of play… HEX does a lot of very weird things, for better and worse.

![image3](https://i1.wp.com/www.hexprimal.com/wp-content/uploads/PackRaptor.jpg)

Hearthstone is the next-most-similar game, but it takes things in a different direction still. Being based off of World of Warcraft to an extent, it emphasizes the decision of your character class as an integral part of gameplay. Instead of having resource management in any real sense, your card-playing resource goes up automatically over time and your deckbuilding restrictions are only based on card rarity and class choice. Again, this is for better and worse, and both the losses and gains push Hearthstone into a more casual direction.

Resource management, to be clear, is a very important part of most card games. In HEX and Magic, you have cards in your deck which produce resources, called Shards and Lands respectively (_more on those later_). In Hearthstone you automatically gain resources over time, and there are no deck slots dedicated to attaining the resources to play your cards. This means that in Hearthstone, your flow of plays is much more _guaranteed_, barring the opponent messing with you. It also means there’s fewer decisions to make, fewer chances to make your deck unique or special, and far fewer tactical options.

The thing is, for some people everything I just said is a _positive_: They don’t want decisions or tactical options or unique decks, they just want to play the game very quickly. That’s why Hearthstone is often referred to as the most casual of the modern digital card games. Another thing that pushes Hearthstone into the realm of casual-ity is the sheer amount of randomness. Card games are inherently based on randomness to some extent, but look back at this site’s own article about [Darkest Dungeons]({{ site.baseurl }}{% link _posts/2018-09-05-darkest-dungeon-git-gud-as-a-thought-terminating-cliche.md %}) and XCOM to see why layers of multiple kinds of randomness can be very very bad.

Very, very, VERY bad.

<iframe width="560" height="315" src="https://www.youtube.com/embed/TB1A_tSsDiM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Section 1.1: [DCFC Reference]

<iframe width="560" height="315" src="https://www.youtube.com/embed/T822kIkbFu0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

So let’s get into what isn’t a difference for our purposes here today, because that’ll matter. If this does end up becoming an ongoing concern, we’ll be coming back to this point a lot.

Flavor is not mechanics, mechanics are not flavor, trade dress is just a dress.

That is to say, the fact that HEX has a Void and a Crypt and a Deck instead of Exile, Graveyard, and Library doesn’t make those things mechanically distinct from Magic. As far as the game rules are concerned those things are all functionally identical to their counterparts. These are the _mechanics_ of the situation, while the names and descriptions are the _flavor_.

The thing is that, despite those flavor differences not _directly_ impacting the gameplay? Card games live and die off their flavor. If Magic were a game in which you just compared numeric stats on CARD #376 versus the stats on CARD #589, nobody would be playing it. Nobody rational anyways. But sometimes subtle flavor differences in turn lead to minor rules differences, which can make a surprisingly large disconnect between things that look identical at first blush.

For a first comparison of how that can be different, let us look at two abilities that serve similar roles in their respective games, but are not the same: Hearthstone’s Silence and HEX’s Revert.

<div class="images" markdown="1">
![image4](https://static.icy-veins.com/images/hearthstone/544-silence-golden.png)

![image5](https://i0.wp.com/www.hexprimal.com/wp-content/uploads/FishHands.jpg)
</div>

Both of these abilities share a similar flavor and even gameplay concept: They’re ways to strip off the modifiers and effects on a minion / troop. But the differences in the _hows_ and _whys_ make them distinct both flavorfully and mechanically.

In Hearthstone, when you Silence a card you remove all meaningful text from it that isn’t inherent to the card itself: It loses everything in its text box, any modifications placed on it go away, any keyword abilities or special powers are gone. All it keeps is the name, attack power, health (current health, damage included), and a type if it has one.

This is often used to neuter an enemy card or to remove the negative attributes of your own cards: Quite a few Priest decks (_Priest being one of the game’s classes_) have made good use of removing “This Cannot Attack” and equivalent text from undercosted troops.

![image6](https://d1u5p3l4wpay3k.cloudfront.net/hearthstone_gamepedia/4/49/Ancient_Watcher%28153%29.png?version=96b4e1b24b88c25a30e9782fb77dc507)

In HEX, when you Revert a card you return it to the state in which it began this game. Buffs go away, debuffs go away, damage goes away. If it was actually a different card that had been transformed by some effect, it returns to the original card’s original form. This is actually key to solving an optional sidequest in HEX’s fantastic single-player campaign.

This is often used for the exact same purposes as Hearthstone’s silence, both in design and in gameplay. Having a Revert or a Silence often lets you turn something scary back into its base attributes or at least remove the scary part, and you can unfuck your own cards after the opponent decides to mess with them.

But Silence doesn’t let you get a card back to pristine condition, and Revert doesn’t let you remove negative text that was already a natural part of the card. They’re very alike, but the small difference makes a big change.

### Section 1.2: Lands and Shards and Crystals, Oh My

At first blush this will seem like stuff that could have been part of the section above. But while that was about same-thing-named-differently and different-but-very-similar-things? These are the bigger departures, the places where things may have common roles and purposes, but their differences play a large role in how the games differ. Specifically, let’s dig into the resources that allow plays to be made.

In Magic, most of your cards have a cost, usually in mana. Most of the cards that don’t have a cost will be ***lands***, the cards that produce said mana. Each one has its own limits on what it can produce and how / when, but the default is “Once per turn, this land makes one mana of one specific color”.

In HEX, all of that is true up until the last bit. HEX’s shards don’t stick around to make resources themselves: They give you a color-marker called a Threshold and some amount of Permanent Resource and Temporary Resource, and then go away forever. That was a lot of word salad if you haven’t played or seen HEX before, so to elaborate:

In HEX you have a small meter on-screen that starts off reading 0/0. These are your _Resources_, the equivalent to mana. Temporary/Permanent, 0/0. When you play a Shard, that usually goes up by 1/1: You now have 1 Temporary Resource you can spend this turn, and you’ve also gained a Permanent Resource. Your Temporary Resources will refill up to the Permanent number at the start of each of your future turns: So if you spend the Resource, it goes to 0/1, and next turn it returns to 1/1. Play another shard, and now it’s 2/2.

At first blush there’s not a lot of difference here, but the key is in that Threshold you get from shards: Once you have a green Threshold in HEX, every resource you have can be spent on something that requires a single green point. By comparison, let’s take a look at a fairly normal sequence for a Magic deck, which will require a quick discussion of Magic and mana.

In Magic, you cast spells using a resource called ‘mana’. This is usually produced using cards called ‘lands’, which you can play once per turn. The majority of lands produce a single color: Plains produce white mana, Swamps produce black, etc. Card _costs_ can be in both colors as well as “generic” mana costs, represented as a number. A generic cost can be paid with any mana, regardless of color or lack thereof. The shorthand for this would be something like W meaning a cost of one white mana, or 1W meaning one generic _and_one white.

Turn 1, you play the basic green-mana-producing land Forest. Turn 2, you play the basic red-mana-producing land Mountain, and use them both together to play a 2-mana creature. It could be something that costs 1 green and 1 generic, 1 generic and 1 red, 1 red and 1 green, or 2 generic. You could also play two seperate cards that cost 1 generic, 1 red, or 1 green each, but not two cards of the same color: Your Forest can’t make red and your Mountain can’t make green.

![image7](https://i.pinimg.com/236x/1a/b2/f2/1ab2f241f1208dfa98b64a85501f6b17--the-gathering-mountain.jpg)

Let’s look at the same equivalent sequence in HEX:

Turn 1, you play the basic green(equivalent)-granting Wild Shard. Turn 2, you play the basic red(equivalent)-granting Ruby Shard. You could then play the same subset of cards as the Magic deck did: Anything that requires 1R, 1G, RG, or 2, or two cards that cost 1 or R or G.

![image8](https://d1u5p3l4wpay3k.cloudfront.net/hex_gamepedia/thumb/8/81/Wild_Shard.png/250px-Wild_Shard.png?version=3a8d74b9891ffc11bcd4400e98b33a3c)

But something you could do instead that you could not have done in Magic? You can play two cards that both need a single Red (R, R) or a single Green (G, G). This is because once you have a Threshold in HEX, you just have it.

You’re not activating a land that can produce a specific color of mana once each turn, you previously played a shard that permanently marked you saying “This guy can do anything that takes 1 Wild threshold, and has 1/1 more Resources to do it with.”.

Meanwhile over in Magic, maybe our aggro Dinosaurs player is stuck with an extra Elf in his hand he can’t use to power out more stupid lizards. And that’s the fate said player deserves.

Because fuck Dinosaurs.

![image9](https://cdn1.mtggoldfish.com/images/gf/Carnage%2BTyrant%2B%255BXLN%255D.jpg)

This doesn’t make either system strictly superior to the other, but it does create significant differences: In a Magic deck, you need enough mana sources of given colors to cast all of the cards of those colors you might want to unleash turn-to-turn. In a HEX deck, you just need to ensure you get the right thresholds by the right time, and then you can chill. This allows for more diverse decks and riskier ‘splashes’ into off-colors in HEX, and the designers know this and make the cards accordingly.

This also means that resource-denial is different in the two games: While Magic has ways to destroy lands and get them out of the game, HEX only has ways to subtract the Resources from the equation and not any way (last I checked) to remove Thresholds. That means that once a HEX player is on a given color, you’re never getting them off of it.

So now that we’re on a roll talking about resources, let’s look at how Hearthstone handles them for a deeper comparison.

Hearthstone has a Mana Crystal bar whose crystals fill up automatically at the start of each turn (just like HEX’s Resources, or the untapping of (most of) Magic’s lands). You gain one crystal every turn automatically as well, which completely replaces playing resource cards. However, some few classes do still get the ability to try and ‘ramp’, or accelerate their growth, with cards that add more crystals faster. One or two other classes likewise can remove the opponent’s crystals in an attempt at disruption, or even sacrifice their own crystals for bigger immediate benefits.

Notice that Hearthstone’s handling here relegates an entire mechanical niche (interacting with resources, both ways) to just a few of its 9 classes. Said niche tends to always massively dominate the landscape of the current environment whenever the developers so much as poke it. Even temporary resource generation has often caused such ruckus that it gets nerfed (has power removed in some way) into messy oblivion.

![image10](https://i.imgur.com/removed.png)

Using the example card above, the Druid class’ _Innervate_. An important benchmark here is that part of how Hearthstone balances the difference between going first and going second. In Magic and HEX, this difference is handled by having the first player skip their card draw on the first turn. In Hearthstone, the player going second starts with an extra card in hand _and_ starts with a card called The Coin, which has the exact text of the nerfed version of Innervate.

So why was Innervate so powerful in its grant-2-mana incarnation that it had to be cut in half, nerfed down to the level of The Coin? Well, it turns out that since Druid is the class that is already the best by a _very_ wide margin at improving their own mana growth, and because Druid’s higher-cost (_and thus nominally late-game_) cards are so strong? Innervate enabled plays that were, in a word, degenerate. Too much was just happening too fast before other classes could react.

But that might not have been the nail in Innervate’s coffin. The real killer was quite possibly its use _later_ in the game, not for acceleration purposes but for _overflow_. In Magic and HEX, you can grow your own mana supply over time as far as it will go. In Hearthstone, once you have a full allotment of 10 Mana Crystals, that’s that. You’ll never have 11. But Innervate and cards like it change that, theoretically letting a player cast 12 mana worth of spells, or more, in a single endgame turn.

Bit of an abrupt place to cut it off here, but that’s the thing about design space, even design space that’s already used: If we kept stretching we’d go on forever. There are foot-thick books of history and strategy for [**games as seemingly-simple as NES Tetris**](https://www.youtube.com/watch?v=9RaqVGzhQTM), so we’ve got to stop somewhere. Might as well be here. 

This has been Ariamaki filling in, see you (potentially) next time!