# Minecraft Game Design

JENS BERGENSTEN

| Page | Chapter                                   |
| ---- | ----------------------------------------- |
| 4    | [Introduction](#introduction)             |
| 12   | [What is Minecraft?](#what_is_minecraft)  |
| 34   | [Guiding Principles](#guiding_principles) |
| 80   | [Anecdotes](#anecdotes)                   |

<h2 name="introduction">INTRODUCTION</h2>

Welcome! If you're reading this, you probably work directly or indirectly with the Minecraft franchise. This booklet gives background into previous game design decisions, as well as some that will influence future design. The principles and rules described here mostly refer to the "vanilla" game, but can also help to develop other Minecraft-related products.

This guide will be updated as our perspectives change alongside Minecraft's growth. We hope you find it informative.

As a disclaimer, I want to call out that this is written from the first person "I" because it's my interpretation of what Minecraft is. The intention is not to take credit for all things Minecraft, but to point out that these takes are often subjective and up for debate. Game design is very driven by taste and individual's experiences with games.

Notch and I worked together on Minecraft for about one year, and I've tried to recollect the things he mentioned as inspiration. He would cite games, what kind of gameplay features he liked, and set a direction for the Minecraft universe. He often mentioned Dwarf Fortress, RollerCoaster Tycoon, and Dungeon Master. The real genius was to combine this direction with the interaction model of Infiniminer. 

I grew up under the influence of Games Workshop products including 40K, Fantasy Battle, Space Hulk, and Warhammer Quest. As a game designer, the games that left the biggest mark were probably Blood Bowl and Necromunda.

### Dwarf Fortress

![Dwarf Fortress](res\Dwarf_Fortress.png)

**RELEASE DATE:** 8 August, 2006

**DEVELOPER:** Tarn Adams

**PUBLISHER:** Bay 12 Games

Dwarf Fortress is arguably the most in-depth simulation game in the world. You are tasked with the survival of a clan of dwarfs, and need to care for mining, beer brewing, goblin defenses, and the mental health of your citizens. All incredibly procedurally generated.

---

### RollerCoaster Tycoon

![RollerCoaster Tycoon](res\RollerCoaster_Tycoon.png)

Atheme park-building game in which creativity and roblem solving goes hand-in-hand. Visitors to your park will act on their own using simplistic Al, but the player always has the tools to deal with urgent problems.

**RELEASE DATE:** 31 March, 1999

**DEVELOPER:** Chris Sawyer

**PUBLISHER:** Hasbro Interactive

---

### Dungeon Master

![Dungeon_Master](res\Dungeon_Master.png)

The first 3D spelunker role-playing game that used real-time mechanics. A traditional fantasy game that Notch often referenced, and an inspiration for one of my own favorite franchises, Eye of the Beholder.

**RELEASE DATE:** 15 December, 1987

**DEVELOPER:** Doug Bell, Andy Jaros, Wayne Holder

**PUBLISHER:** FTL Games

---

### Infiniminer

![Infiniminer](res\Infiniminer.png)

Infiniminer was posted to The Independent Gaming Source's forums and became the breakthrough inspiration for Minecraft's entire interaction model. It may be a very simple game, but has helped creating something amazing. Zach has continued releasing many successful games since then.

**RELEASE DATE:** 29 April, 2009

**DEVELOPER:** Zach Barth

**PUBLISHER:** Zachtronics Industries

---


In the third edition of Blood Bowl - a violent fantasy take on American Football - Games Workshop moved from intricate character attributes relating to their talents and replaced them with a more readable one. For example, in Third Edition, a Lineman and a Catcher would have the same base statistics, but a Catcher would also have a "Catch" skill which added a new behavior when catching balls. This clean design struck a chord with me, and taught me to value when game rules have a clear and specific purpose. We should call out effects and differences in the game mechanics and not hide them in numbers.

Minecraft is not a board game though. Minecraft is a creative video game set in an infinite world, where almost anything you can imagine can be created. The question is how a large development team can handle development over years and years, and a multitude of updates. Let's begin with, what is Minecraft? 

\- Jens Bergensten

<h2 name="what_is_minecraft">WHAT IS MINECRAFT?</h2>

### MINECRAFT IS EXPLORATION

Each Minecraft world is unique, and filled with thousands of things to find and explore. What's behind that hill? What's inside this house? Where can I find the best spot for my villa? Curiosity is a strong motivation to play the game and push forward. The sense of infinity inspires players and boggles their imagination. 

It doesn't matter that most players never go far from the world's starting point — just the idea of having no boundaries gives the feeling of grandeur. 

We should strive towards rewarding players who explore without making it feel like a necessity. As I will return to later: finding things is fun, searching is not. 

### MINECRAFT IS ADVENTURE

As players explore, there's always something at stake and reward to reap. Craft your equipment to prepare for a journey. Fight scary monsters and collect the loot. Spelunk dungeons and find its treasures.

Dangers and hazards gate these rewards, but rewards unlock new functionality and boost the players' ability to take on more challenges. This feedback loop lets players invent their own missions and quests and provide an overarching goal of defeating the ender dragon. 

We should keep giving players new challenges, but challenges should give adequate rewards. The balance is often hard to achieve. 

### MIMECRKAFT IS CREATIVITY

One of the fascinating things about Minecraft is how it inspires creativity. Once you learn how to create a small dirt house, you realize that you can scale to castles, bridges, great pyramids, or even modern-day imitations of airports or football stadiums. 

Creativity is great for self-fulfillment and satisfaction, as well as creating a social environment for sharing and enjoying other's works. Creativity in Minecraft is not limited to construction but also encapsulates storytelling, role-playing, art, music, and much more. This platform for creativity has fitted in nicely with today's social media and "click-collecting" culture. 

### MIMNECRAFT IS ENGINEERING

Notch designed some systems in Minecraft specifically with engineering in mind, such as redstone and farming mechanics. 

These systems create gameplay out of understanding how the game works. Other areas, such as the way monsters spawn at night, create ways for players to optimize their progress and "exploit" the game rules in clever ways. 

We have since added more tools and behaviors for players to explore. Hoppers, slime blocks, and even the way chorus plants grow, are just some examples. We should remember that some people express their creativity in the form of logic and technology. Nothing beats outsmarting the game.

### MINECRAFT IS PERSISTENT 

It's easy to take this for granted, but every time a player removes a block, it leaves a permanent mark on that world. Blocks end up in the player's inventory, and over time dozens of chests are filled with dirt and stone. Breaking block after block may sometimes feel like grinding, but earning minuscule drops appeals to the psychology of hoarding. 

We need to remember that sometimes the journey is more interesting than the destination. A grand castle would not be the same if it appeared with the click of a button. 

### MINECRAFT IS LIMITLESS

There are no boundaries and there is no end to Minecraft. Your castle could always be more magnificent, the fields of wheat could reach beyond the horizons, and you could attempt to terraform the entire of the Nether. Such aspirations may be over-ambitious but never pointless. 

No one can rule how players choose to enjoy Minecraft. Strip mining for hours and hours can be calming and meditative and, when you move on from that state, you may have created something awe-inspiring. 

### MIMNECRAFT IS SCARY

Digging your way to bedrock is often a tense experience. Not only are there monsters in the darkness, but lava pools, cave-ins, and spooky sound effects add to the suspense. The danger of losing all your equipment in the void while building in the end is nerve-racking. Not only do you need to worry about your own safety, but monsters also threaten the things you've painstakingly constructed.

We should remember to keep the players active and engaged. Indifference is a worse enemy than creepers. 

### MIMNECRAFT IS SIMPLE

The art style of Minecraft is a result of keeping things simple and giving the world a relatable personality. The blocky characters and low resolution textures might occasionally restrict a certain kind of expression, but the pigs' crossed eyes, cows looking at players dumbfounded, and the illagers' bushy brows all add to the unique feeling of the universe. We sometimes refer to this as "ugly cute." 

We keep a low barrier for the community to reimagine textures and models. Anyone should feel that they can create their own animal or monster for the game, and for it to feel relevant. At the same time, we should find out what makes a creature come to life. Such behaviors can be simple things like wolves tilting their heads, pandas rolling over, or the funny noises made by shulkers. 

### MIMECRAFT IS RIDICULOUS

Lots of the things featured in Minecraft are a bit silly. More often than not, a feature makes it into the game simply because it made us happy. The frowny face of the observer block, the ender dragon head, and the way beds look if you put them on a player's head (using commands). 

Though it looks ridiculous to an outsider, the characters in Minecraft take things extremely seriously. The absurdity is similar to Monty Python's humor: a snow golem does not care its face looks derpy when engaging a blaze, and the villagers' hums are real to them. 

In a universe that can be scary and sometimes even morbid, we should allow ourselves to have some fun. 

### MIMECRAFT IS MULTIVERSE

Each Minecraft world is not separated by space or time; they co-exist in their unique realities, and what happens in one does not affect another. If there is a before or after, it would be something else than "vanilla" Minecraft. 

This concept may open a few questions for our related projects. Is a story taking place in a specific world or is it relevant to the multiverse of Minecraft? More specifically, is a spin-off game expanding the lore, or is it an isolated event taking place in one of the many worlds? 

In the core game, it is better to be unspecific and generic to fit all possibilities, but a static story can have more details, such as named characters and items. 

<h2 name="guiding_principles">GUIDING PRINCIPLES</h2>

On the following pages, I will try to outline a few guides and "rules" that can help when designing new features for Minecraft. They are intended to help understand the reasoning behind features. They are not set in stone and we reserve the right to break our own rules from time to time! 

It could be useful to remember that these guidelines are intended for the core vanilla game. Features designed for spin-off games, in mods, or even with the game's built-in commands exist outside the scope of this booklet. However, even if these directions are for vanilla, other projects should be very clear about why and when they decide to break the rules. These decisions should bring value, and be made with intent. 

### ONE BLOCK AT A TIME! 

The primary principle is that all actions interact with one block at a time. You break one block, pull one lever, and till one block of dirt. There should not be any copy-paste functionality, building templates, or similar convenience tools. Interacting with a block may impact multitudes of other blocks of course, such as planting a tree, blowing up a TNT, or activating a network of redstone, but from the player's perspective, it's all starts with that singular interaction.

Why is this important? It allows us to maintain the interaction model of Minecraft, but it also sets an essential constraint to how you build things with other players. I want a player to understand what is happening when they see someone else play. Instantaneously placing buildings with templates would make it hard for an observer to assist.

### THERE IS NO STEVE OR ALEX

Steve and Alex are intended as placeholders for players. A player should make their own skin and make their own story. Players are playing themselves or maybe a character that fits in their unique world.

We use Steve and Alex in our merchandise as mascots for Minecraft, but they should not have an active role in spin-off projects or storylines.

### NOT QUITE AN RPG

Since Minecraft's original inspiration came from games such as Dwarf Fortress and Dungeon Master, it has evolved in the direction of a fantasy role-playing game. But Minecraft is not quite a traditional role-playing game, and a significant distinction is that the player character doesn't develop skills over time. The only thing that defines what a player can do are the items they carry and their knowledge of the game.

One common misunderstanding stems from the levels that players are awarded when defeating monsters or trading with villagers. These are not experience levels in the traditional sense of games, but rather enchanting levels that players can use to improve their equipment.

### BAD THINGS HAPPEH...

... but it's technically the players' fault. Disaster is common in Minecraft, be it falling in lava or having your house blown to pieces by a creeper. The point is that these accidents happened when there were players there to see them happen. Avoiding such dangers is done by playing differently and more carefully. The game should not create situations that are impossible to avoid, and when it does, they should have a reasonably small impact.

Making sure the player is treated fairly is one reason why the worst natural disaster is a (relatively tame) lightning strike, and the list of blocks the endermen take is limited to natural-and plentiful-blocks such as dirt and stone. If a game mechanic is going to destroy hours of players' hard work, players should be the ones initiating it, and players should be able to stop, or even prevent it entirely.

One practical example is how iron golems ignore creepers, because otherwise the creeper would explode and destroy buildings without any player interaction.

### NEW FEATURES NEED TO BE RESPECTFUL OF EXISTING ONES

New features need to adapt to the balance of other features. "Different" is more interesting than "better," and that is true for both gameplay mechanics and power metrics. The mood and gameplay of the End cities are very different from what you might find in an ocean monument, for example.

### ITEMS SHOULD BE MULTI-PURPOSE 

The players' inventories are already quite over-encumbered with the hundreds of items that exist in Minecraft. When we add even more to the pool, we should think hard if we can make them multi-purpose or have a broader use-case. 

For example, the totem of undying only has a single use, but it's one with sufficient gameplay impact. Sometimes the solution is another potion-brewing ingredient, but often the best option is to provide a decoration block for players to craft. 

### IT'S UP TO THE PLAYERS TO BUILD THE WORLD 

When we added the villages in the Minecraft beta, we made a conscious decision that they wouldn't develop automatically. The villagers would not build houses, and there would not be any mechanics for adding more template-based buildings. If the village needs a protective wall, the players will need to construct it for them.

Minecraft offers a setting for players to interact with, but the players decide what, when, and where that happens. 

### YOU ARE NOT WEARING A HUD 

As far as possible we should try to describe what happens using objects in the game world, and not rely on text messages or a heads-up display. Good examples of items that show information in an in-world sense are the map, compass, and clock. Avoiding Ul and text messages can be a real interaction design challenge. 

I'm personally also an opponent of the "F3 debug screen." I don't want players to know or care about game engine components such as coordinates, block states, or light levels. If these are important to play the game, we need to design in-character tools to deal with them. 

### FINDING THINGS IS FUN. SEARCHING FOR THEM IS NOT 

If the Minecraft world is infinite, you can be pretty sure that everything that can exist, does exist, but the question is how to find what you want. It can be very frustrating to randomly walk around looking for the most recent feature update. We want to surprise our players and reward them for exploring, but we should also make sure that we give players a reasonable way of finding things. Exploration maps to the woodland mansion, the eye of ender, and the bubble columns leading to under water ruins are a few examples of how this can be achieved. 

### REAL-LIFE ANIMALS SHOULD BE FRIENDLY 

Animals in Minecraft should be friendly, or neutral at worst. Letting animals remain friendly is partly done in favour of the "ugly cute" direction, but also to enable them for players in the peaceful difficulty setting. 

Some animals can still defend themselves, like wolves and polar bears, but real dangers are reserved for the nocturnal monsters. 

### HOSTILE MOBS SHOULD BE UNIQUE

We have the opportunity to create an entirely new mythology, and we should make good use of it. When designing a hostile monster, look beyond traditional fantasy beasts like minotaurs and unicorns, and push for something unique. 

The undead serve a purpose in the sense that they give players a reference enemy they can compare other monsters with. The iconic dragon is one of the more traditional things that Notch wanted to add. We can try many other things as we go forward. 

### MOBS NEED PERSONALITY

It's important we catch the essence of the personality a mob has, regardless if it's a hostile monster or a friendly animal. The visuals, the sounds, and the Al behaviors all add to how players relate to these creatures.

The most straightforward starting point is to make sure they have eyes and that they look at the players when they are nearby. Sound effects also help a lot but beyond that, each mob should find at least one behavior that makes it stand out. Llamas spitting, shulkers peeking out, and ocelots sneaking up on chickens are a few examples. 

### HUMAN CHARACTERS ARE HUMAN BEINGS

Steve and Alex are placeholders for players, and there are no other human characters in Minecraft. Only human beings (the players) may look like humans.

There are a few exceptions: in Minecraft: Education Edition we added more villager skins to help with tutorial NPCs, and in Minecraft: Story Mode, the concept is that all characters are "players on a server"

### NO BLOOD, NO GORE

Cartoon violence in Minecraft is very prominent, but we do our best to avoid blood and gore in animations, particles, textures, and so on. We changed the killer bunny and zombie pig man textures from their original versions to remove blood details.

### KEEP IT VANILLA

Our community is very creative and productive. There are hundreds of thousands of mods, adventure maps, mini-games, texture packs, tools, and many other things made by our players.

We need to remember that Minecraft appeals to many different player types that are looking for different things to do. We should make sure we expand the game in "all directions," and let the community dive deep into their favourite topics.

### NO ITEM IS TRULY UNIQUE 

Tying back to the concept of the multiverse, we should avoid having unique items and characters. Of course, each world and player experience is unique but adding named weapons, such as a crossbow called "Heartseeker" would add connection points between worlds that would make them feel less special. This would go against the multiverse idea, where all possibilities exist at once. 

### EXPAND THE MYSTERIES

There are many weird and strange things in Minecraft. They often don't make a lot of sense, but it's not our job to explain them. Why are there monsters at night? What are the illagers? Who built the stronghold? Such questions can be the starting point of a story, and even if we have our own idea, we should keep it to ourselves.

### GENDER NEUTRALITY IS A CORE PRINCIPLE

With all creatures and monsters we add, we should assume they are genderless or of unknown gender. In some languages, this is very hard to achieve, but in English, we should avoid using words such as "brethren," "king," or "dutchess."

Player characters represent individuals and can obviously Be "he" or "she." In these cases our objective is to make sure these are portrayed with equal ability and purpose. 

### DEATH IS REAL

We should always design things with Hardcore difficulty in mind. Death and demise are real, and gameplay mechanics should not rely on respawn. As an example, it was once suggested to have an achievement for dying spectacularly, but since this 1s not possible to achieve in Hardcore without ending a run, it was turned down.

### BUGS ARE NOT FEATURES 

Quirks and glitches are often fun and charming, but we should not rely on undefined behaviour. It's easy to accidentally "fix" something player depend on if they're not implemented as intentional features. 

With this in mind, we fixed the booster tracks and replaced them with powered rails. We removed the negative durability bug and replaced it with an "unbreakable" item tag. 

### MINECRAFT IS NOT AN EDITOR

We need to remember that Minecraft is a game. It's about breaking and placing blocks, finding treasure, hoarding items, and defedt1ng the nightly monsters. You turn to creative mode to build things with friends and have a good time. Along with the "one block at a time," we should not let game rules, command blocks, or configuration pages take away from the core of what people want from Minecraft.

That said, don't be surprised if it features an "Editor Mode" in the future. We are making a game, but the community is also creating experiences for other players, and we enable those where possible.

<h2 name="anecdotes">ANECDOTES</h2>

Throughout the years making Minecraft, we have collected plenty of tidbits about changes and feature improvements. In the following section, I randomly selected a few anecdotes that you may find funny or interesting. 

### THE TRAGIC FATE OF THE ROSE FLOWER

As part of the "Update that Changed the World," we added new flowers such as the oxeye daisy, allium, and the tulip. I also wanted to add a peony flower, but a community member pointed out that peonies are flowering shrubs and not flowers. I called out that the same was true for roses, and another community member sarcastically chipped in that "Gee, wonder who could fix that?" 

They had thrown down the gauntlet, and the rose flower became a poppy. We added roses back as double-block bush plants, but the community still has a "remember the rose" day, half in jest and half serious. 

### THE EVIL VILLAGERS 

Minecraft: Dungeons is a dungeon crawler taking place in a Minecraft environment. This project was in need of significantly more hostile monsters than those that appear in the vanilla game, and we were toying with different concepts to solve this. 

Things would have been much easier if we had a generic evil character, and this led to the creation of the "evil villagers." We called these enemies "ill-willed villagers," or "illvillagers" but "evillagers" and just "illagers" were also suggested. We picked the shortest option, and it was probably also the most fun. If you speak Swedish, the correct translation would be "fybo" ("bad villager") since it creates the same meaning and uses the same pun out of "bybo" ("villager"). 

Illagers are useful for creating spin-offs and related stories. They can have any agenda or any skills that are necessary to fuel a plot, though these skills should be more towards "magic" than engineering. 

### THE REDSTONE REPEATER

The redstone repeater was the first specific-purpose block added for redstone contraptions. The original purpose was to act as a diode, which means that a redstone signal would only pass through the block in one direction. 

The repeater also acted as a delay, and since we had a few more data bits available, I made the delay configurable. The initial values were 1, 2, 5, and 7 redstone ticks because those would require the lowest number of repeaters to create all delays from 1 through 10. The community pointed out that 1, 2,5 and 6 would be better for delays all the way up to 12, but I ultimately chose 1, 2, 3 and 4 because it was more straight-forward and easier to understand. 

### THE BEACON

One day I joined a Survival mode server just for fun, and the players in that world had achieved everything possible. They had all the items, all the monster grinders, and had built amazing buildings. I felt that for these kinds of players there needed to be something that required more "grinding" and teamwork. This experience led to the creation of the beacon block, and the "expensive" pyramid of precious metals and jewels upon which it sits. 

The players outsmarted this system, though, and exploited the fact that iron golems automatically generate in large villages. They would get all the materials they needed through automation instead of grinding. 

We invented the reward (the beacon) before we designed the challenge of how to obtain it (the wither). It's often much more natural to come up with challenges than rewards since these have less impact on overall game balance. 

### CHARCOAL

In the old days of Survival mode, it was crucial to find coal as quickly as possible. Coal would unlock torches, and subsequently mining, which allowed the player to survive the night. When we added charcoal, you could with less effort get a light source wherever there were trees. Charcoal had, in other words, quite a significant impact on the game's technology tree and meta gameplay. 

We are usually careful not to upset the progression in the game as part of new features. We prefer to expand or deepen the technology tree if possible. Charcoal helped to solve a problem and allow for different play styles. 

### THE ENDERMEN 

We never want to explain the endermen to our players. They are the silent observers, and their mysterious behavior of moving blocks should remain a mystery. Notch added the endermen as a nod to the Slenderman meme, but they have since then grown to become a core Minecraft lore element. 

This well-kept secret is that they are trying to bring about the collapse to all dimensions, by displacing blocks that are key to the world's existence. They do this one block at a time, hilariously slowly. But...they have eternity on their side. 

---

MOJANG 

TM & © Mojang Synergies AB 

**TEXT:** Jens Bergensten 

**ILLUSTRATION:** Ninni Landin, Markus Toivonen, Martin Johansson, Anton Stenvall, Bsmart 

**BOOK DESIGN:** Markus Karlsson Frost 

First edition 

Printed in Sweden 2019 

For internal use
