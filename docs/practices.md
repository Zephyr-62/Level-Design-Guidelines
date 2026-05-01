---
title: Design Practices
layout: default
nav_order: 3
parent: Guidelines
---

This section goes through some common practices professional level designers apply in the industry.
This is just a collection of the most relevant practices.
They are presented in no particular order, so you can read them as independent pieces of information to consider when working on a video game.

## Iteration Pipeline 
The most basic practice that is always present in any project is iteration. 
Approach the design process in small steps and loop through them to find out what works and tune the result to your specific needs.
Specifically for level design, a contender list of steps includes:

- **Design on paper** <br> 
    Before you start putting too much time and effort into building your levels, you should first design them and make sure that their structure follows the design guidelines you want to implement.
    The process of building a level should only happen when you think it is ready to playtest.
- **Apply greyboxing** <br> 
    This concept refers to building your level with as simple geometry as possible (usually grey or white cubes), without paying any attention to the looks or details.
    Some specific level elements might be required in this step, such as point lights, sound sources, or moving elements, but these should be part of specific level design needs (as the guideline [Curiosity](../docs/Guidelines/2.Guidance/guidelineCuriosity) explains through *spatial lures*).        
    Once the level is greyboxed, it is usually playtested internally.
    Here, you iterate and go back to design on paper whatever did not fulfil your needs.
- **First Playable** <br>
    This refers to the version of the level that is ready to playtest in a wider context. 
    It is usually denoted as a pre-alpha version, where game ideas are more consolidated, and the level works as a whole, and not individual pieces.
    At this stage the levels can be populated with temporary assets as decorations.
- **Level Art** <br>
    Once the level design has been polished and designers have a feeling their level is ready for production, the level artists can take the lead and start giving life to these environments.
    It is still important for level designers to be somewhat present in this step, since level art can drastically impact how a level is perceived.
    The use of colour, light, sound, or movement (_spatial lures_) can direct the player's attention away from the path they were intended to follow. 

We can see represented in this process of iteration one of the most common recommendations: `Early Design and Early Testing'. 
This refers to the introduction of level design early in the development process of the game.
Level design is one of the most crucial steps for a game to be engaging, and getting it right is a difficult and tedious task.
Making sure your designs work as early as possible allows for work parallelization and detecting core game design flaws early in the development process.
It is also helpful for tracking different level design properties such as pacing, variety, downtime, risk VS reward, etc.

## Blank Canvas
One common problem we can run into as designers is the blank canvas syndrome.
To overcome it, there are a few well-known practices that can be used.

To start off, we can build *metric playgrounds*.
These are a type of playground used by developers to measure and evaluate the implementation of their mechanics.
They are more widely used in games that heavily relay on movement or shooter mechanics.
In these spaces, level designers can also understand what type of interactions the player can have with the game elements.
In a way, these spaces are a collection of all the 'building blocks' level designers can use.

Level designers can make use of *action blocks*, also known as 'Gardens'.
These are defined as simple combinations of game elements that portray a specific gameplay instance.
One example could be how to use a mechanic to surpass an obstacle in a specific way, such as bouncing on top of an enemy to jump over a wall.
With this, levels can then be prototyped by combining different action blocks.

As a final remark in the topic of the blank canvas syndrome, remember that **constraints** allow for new ideas.
It is easier to create something interesting by solving your way around a constraint than it is to create it from thin air.
An example could be designing the layout of a small town, where you impose yourself the constraint to arrange it in a tiny plot of land, or with uneven terrain, including cliffs or rivers.

## Polymorphic Variety
The [Engagement](../docs/Guidelines/2.GameDesign/guidelineEngagement) guideline talks about the importance of **variety**. It can be very resource intensive to create many different level elements. One practice to tackle this problem is applying some principles from object-oriented programming to level design.

Polymorphism for example, can be implemented by taking level elements and mechanics and creating small variations.
This implies saving development time and resources, while still providing value to the game.
One example of this implementation occurs in the Zelda series, where different tiers of the 'bokoblin' enemy introduce gameplay variation by showing small differences.
These differences include difficulty (health and damage variance), different types of weapons (bows, swords, spears...), and sometimes even different mechanics, like bokoblins that can use a horn to invoke more enemies.

In the context of level design, this practice could be applied to the aforementioned *action blocks*, where simple mechanical ideas can present small variations so that you can easily expand your selection of building blocks.

## Living Documentation
Senior level designer J. Burgess[^1] explains how his design planning process works for open-world games.
He explained how a toolkit cannot be provided, since any game's needs are different from one another and "... the creative goals of a game should shape the process of creating it".

This knowledge is only to be applied mindfully in the appropriate context, for a workflow with iteration as a core value.
His planning process consists of a *'living documentation'* constituted of 3 parts that can be used to organise and track the design of a large scale open world.

- **The Map** <br>
    This is a literal representation of the space.
    It is used to visually understand how the different level elements relate to each other spatially. 
    Burgess explained here different considerations that are already mentioned in the [Design Considerations](../docs/considerations) section, along with some principles included in several guidelines. 
    It is encouraged to read his specific input in this topic.
- **The Master List** <br>
    This is a list of all the important locations with details on several aspects so that you can filter and compare them. 
    This can be arranged in a spreadsheet software.
    Some example attributes to store in this list are: the coordinates of the location, the footprint radius, the relevance, the designer in charge, related quests, etc.
    With this information, you can later run different data visualization methods, like plotting the locations with their influence radius in the map, tracing out the path players might take when they are following a quest, or colour-code the different areas depending on how much progress has been made development-wise.
- **The Location Directory** <br>
    This is akin to the master list, but here every location entry is explained in detail.
    Long descriptions are used to explain the purpose, the looks, the feel, and many other aspects of the different locations.
    This is a more traditional representation of documentation that can be followed by designers to implement and introduce these areas into the game.

## Metrics
Finally, I wanted to mention the importance of the usage of *metrics*. 
These refer to the in-engine measurements developers carry out to track the relative scales the player has with the different level elements and the environment itself.
These are quite useful at the early stages of prototyping levels (like *playgrounds*), since you can keep track how the player interacts with its surroundings and its limitations, such as how high the steps of a staircase should be, or the scale mountains should have to appear 'large'.
Take into account that games rely on a *sense of scale*, not real scale.
This means that using real-world metrics can mess with the sense of scale the players have.
Metrics should be built around players, not humans.

## In-Game Documentation
There are three representations of documentation that can be built within a game engine: [^2]
- Gyms, also known as playgrounds, serve as a space where the developers can put to the test the controls of the character. This space is built to display every possible motion interaction, and usually serve as obstacle courses.
Metrics are a primordial tool used to build these development scenes.
- A Zoo is a type of space where developers get to display all of the game elements and assets in an orderly fashion. These are helpful to understand at a glance the possibility space of blocks that can be used to build a level. Here, a single asset can also be displayed multiple times to showcase different configurations, e.g. textures, or states, like a collapsible bridge. 
- Museums focus on displaying systems and interactions with in depth explanations on how they function or how they can be implemented. These share some similarities with Zoos, but the content displayed is more dynamic, e.g. how the grass reacts when it is set on fire.
*Action blocks* could be displayed in this type of space.

--- 
[^1]: See [Level design planning for open-world games](/docs/references/#LevelDesignPlanning) in the References
[^2]: See [Spatial documentation: Gyms, zoos, and museums](/docs/references/#SpatialDocumentation) in the References