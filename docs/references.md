---
title: References
layout: default
nav_order: 10
---



Many of the sources overlap in the topics presented in this work, since they often address multiple concepts.
Including these as in-text references would not only be an arduous task, but it would also clutter all the text and risk being confusing to the reader, instead of providing useful information about the origin of the different concepts and statements.

For these reasons this approach serves as an alternative. 
What follows is a list of sources about level design, where each entry summarizes the concepts or guidelines it contributes to.

<div id="manual-toc" class="custom-toc-container site-nav" markdown="1" >
**Page Structure**
{: .no_toc .text-delta }
- TOC
{:toc}
</div>

# Description of Sources
## Publications
- **A Phenomenological Approach to the Design of Spatial Experience in Open-world Games**. [^MeaningfulPlaces]
    Research article that explores how players perceive and make sense of the world around them.
    This source explains the difference between a space and a place.
    It is used as a foundation to define the meaning guideline, and it also collects several concepts about hidden guidance and orientation.

- **Exploration in Open-World Video games: Environment, Items, Locations, Quests, and Combat in The Witcher 3**. [^OpenWorldExploration]
    Research article that explores many concepts of open-world games pertinent to level design.
    These include unpredictability, immersion, curiosity, POIs, goals, and more.
    It defines exploration as the process of locating POIs.

- **Level Design Patterns in 2D Games**. [^LDConcepts]
    Paper that provides a list of many key concepts proper of 2D level design, which can be also applied to 3D spaces.
    These include guidance, breadcrumbs, safe zones, pacing, foreshadowing, curiosity, layering, branching, choices, risk VS reward, and more.


## Book Chapters
- **The Art of Game Design: A Book of Lenses**. [^LDAsExperience]
    This book is used as the main source to explain how level design can influence a game experience.
    It explains how to design with a focus on the intended player experience, and explores goals, motivation, meaningful choices, challenge, feedback, pacing, and more.
- **Level Up! The guide to great video game design: Levels**. [^LevelDesignClutteredOverview]
        This source merges level design principles, with practices and game design considerations all in one.
        It explains types of spaces and their characteristics, how to approach level prototyping, it talks about different types of variety to keep the experience fresh, it mentions the importance of goals, and it also includes a section to talk about the integration of PCG.
- **An Architectural Approach to Level Design**. [^ArchitecturalLD]
        This book explains most of the concepts explored in the spatial communication and spatial structure guidelines.
        It mentions layout hierarchies, wayfinding techniques (landmarks, sightlines, etc.), it talks about spatial readability and affordances, pacing through spaces, and the experiential impact different structures can have over the player.
- **Level Design Practices for Independent Games**. [^LDPractices] 
        This source is the main reference that explains how level design can be defined as the process that implements game design, and how it should be structured around the game's core mechanics.
        It focuses on practices for a development process, like the implementation of iteration, or the use of an object-oriented approach.
        However, it gets diluted in level design patterns and game design considerations, such as pacing, challenge balancing, guidance, sandbox spaces, and emergent gameplay.        
- **The Illusion of Choice - How to hide linearity of levels**. [^HiddenGuidance]
        This source explicitly states the concept of `hidden guidance'.
        It explains several guidance concepts like landmarks, branching, types of narrative deterrents, and more.
        It also explains the consequences of an unsuccessful implementation, like the lack of engagement or immersion of the player.
- **Level Design Planning for Open-World Games**. [^LevelDesignPlanning]
        This book chapter explains a useful practice of creating a living documentation.
        It explains how to define the world map and the list of important locations, along with all their metrics and properties.
        It also explains a possible workflow, from pitching the idea and greyboxing, to art and polish.
        However, it also explains how a toolkit for level design cannot be provided, since `any game's needs are different from one another'.
        This quote was important to define the scope and purpose of the guidelines.
- **Procedural Generation in Game Design: Meaning**. [^Meaning]
        This source is used as a foundation of the meaning guideline.
        It explains how meaning is born from connections, and the different types of connections there are.
        Although this source sometimes confuses the concept of meaning with importance or relevance, it explores how this meaning can exist or not in procedurally generated games.
- **Procedural Generation in Game Design: Graphs and Cycles**. [^GatesTypes] 
        This source explains how to understand game progression from a mathematical perspective using graph theory.
        It explores many concepts for graph traversal that implement tools presented in the pathing guideline, such as branching, shortcuts, one-way valves, critical paths, and more.
        It also serves as the main source to define gates, through the theory of types of keys and locks mentioned in the obstacles guideline.

## Articles and Web Sources
- **My Level Design Guidelines**. [^LDGuidelinesProfessional]
        Industry professional Michael Barclay presents in his Web article several key concepts of level design.
        It explains concepts from several guidelines all at once, like themes, pacing, signposting, landmarks, denial spaces, POIs, breadcrumbs, spatial lures, boundaries, vistas, visual languages, set pieces, gates, objectives (goals), rewards, branching, player agency, sandbox levels, choke points, and one-way valves. 
- **Level Design Fundamentals**. [^FortniteLDFundamentals]
    Article published by Unreal Engine that explores a wide variety of concepts in level design.
    These include core mechanics, possibility space, shape language, space theory (negative space, occlusion, and player perception), metrics, scale, cognitive maps, graph theory, hierarchies, player motivation, rewards, and player choice.
- **The Level Design Book**. [^LevelDesignBook]
    Digital book which serves as a guide that explains how to create a game from the ground up.
    It presents a workflow pipeline, explaining pre-production, game design, layouts, scripting, environment art, and release, among others.
    It explains important theory about the use of lighting as a spatial lure along with framing theory.
    It explains layouts and greyboxing, and how it can be integrated in an industry pipeline.
    It also provides dozens of tools and resources to start practising game development.
- **`Define first, design levels later' (Translated from Spanish)**. [^JesusMachinaLD]
    Industry professional shares his insights about game design documents and paper prototyping in this video.
    He explains different tools on how to properly use drawing tools to communicate ideas on paper.
    Other entries of his channel explore block outs, understanding levels as game experiences, types of spaces, and open-world guidance, among others.

## Talks and Developer Insights
- **Spatial Communication in Level Design**. [^SpatialCommunication]
    Talk at Develop Digital (2020) that explores many concepts in pathing, curiosity, goal, and spatial communication.
    It provides a practical example on how the following concepts apply in a space: greyboxing, clear goals, sightlines, cognitive maps, reinforcing goals, affordances, bidirectional gameplay, contrast and spatial lures, denial spaces, one-way valves, vistas/vantage points, branching, mystery, shortcuts, backtracking, pinch points, vocabulary, affordances, locks and keys, and design constraints.
- **Ten Principles for Good Level Design**. [^LDPrinciples]
    GDC talk that explores several principles of level design.
    These include: visual languages, space navigation, environmental storytelling, clear objectives, layering goals, expectations, consequences, difficulty, risk vs reward, modularity, bidirectional gameplay, architectural theory, and MDA.
- **An Approach to Holistic Level Design**. [^HolisticLD]
    GDC talk that explain how a game consists of a story, gameplay, and their presentation, and how designers control these through intentionality, affordances, world building, goals, desires inception, and more.
- **Designing Radically Non-Linear Single Player Levels**. [^GDCNonlinearLD]
    This GDC talk explains how to implement branching and choices, managing pacing and player tension.
    It explains different layouts of spaces with high and low risk, and the different types of level elements that are used to create these, such as attractors or deterrents.
    This same concept is used in one of the prototypes resulting from this thesis.
- **Stop Getting Lost: Make Cognitive Maps, Not Levels**. [^CognitiveMaps]
    This GDC talk explains in detail how players' cognitive maps work and how they follow graph theory, where nodes, edges, and hierarchies are the basics.
    It also explains landmarks, minimaps drawbacks, districts, and how to use all these elements to orient your players or to get them lost.
- **Playgrounds and Level Design**. [^GDCPlaygrounds]
    Another GDC talk that explains the nature of playgrounds and sandbox spaces, and matches them to graph theory, following nodes, edges, and hierarchies.
    It also explains the usage of modules, landmarks, goals, obstacles, and rewards.
- **The Making of The Legend of Zelda: Breath of the Wild**. [^BOTWModularity]
    This is an official video entry from Nintendo explaining different considerations behind the creation of *Zelda BOTW (2017)*.
    This thesis uses it as a resource to explain how modularity can be used as a tool to implement with PCG.
- **Skyrim's Modular Level Design**. [^LDInteroperability]
    This GDC talk explains how games like *Skyrim (2011)* use a modular approach to create content like its dungeons.
    In particular, this resource is utilised in this thesis to explain how level design has an interdisciplinary nature, and how level designers need to keep active communication with the rest of the team (level art, narrative, tech team, and game direction).
- **Gyms, Zoos, and Museums: Your documentation should be in-game**. [^SpatialDocumentation]
    This talk explains different types of in-game documentation and their purpose.
    This is a useful practice for level design to keep all the building blocks organised.
    It can also be extended to organise action blocks.
- **Sparking Curiosity-Driven Exploration Through Narrative in `Outer Wilds'**. [^GDCCuriosity]
    This GDC talk serves as the main source for the curiosity guideline. 
    It explains how to inspire curiosity by allowing the players to pull information, instead of pushing it onto them.
    It then explains how to guide the player along these attractors maintain curiosity and push the flow forward.
    It also talks about layering goals and rewards.
- **Designing for Curiosity in Outer Wilds**. [^LDCuriosity2]
    This talk  given in the Full Indie Summit provides a list of concepts used to make the player curious.
    It particularly focus on how *Outer Wilds (2019)* frames it, but its information can be extrapolated to other games.
    It mentions concepts like: layering goals, pacing, clear objectives, meaningful choices, meaning (narrative relatedness to the player), and signposting.        

----
# APA References


[^MeaningfulPlaces]: <a id="MeaningfulPlaces"></a> B. Wang, Z. Gao, and M. Shidujaman, “Meaningful place: A phenomenological approach to the design of spatial experience in open-world games,” *Games and Culture*, vol. 19, no. 5, pp. 587–610, 2024. [Online]. Available: [https://doi.org/10.1177/15554120231171290](https://doi.org/10.1177/15554120231171290)

[^OpenWorldExploration]: <a id="OpenWorldExploration"></a> N. E. M. Vickery and P. Wyeth, “Exploration in open-world videogames: Environment, items, locations, quests, and combat in the witcher 3,” in *Proceedings of the 34th Australian Conference on Human-Computer Interaction*, New York, NY, USA: Association for Computing Machinery, 2023, pp. 310–318, isbn: 9798400700248. [Online]. Available: [https://doi.org/10.1145/3572921.3572926](https://doi.org/10.1145/3572921.3572926)

[^LDConcepts]: <a id="LDConcepts"></a> A. Khalifa, F. de Mesentier Silva, and J. Togelius, “Level design patterns in 2d games,” in *2019 IEEE Conference on Games (CoG)*, 2019, pp. 1–8. doi: [10.1109/CIG.2019.8847953](10.1109/CIG.2019.8847953)

[^LDAsExperience]: <a id="LDAsExperience"></a> J. Schell, *The Art of Game Design: A Book of Lenses*, 3rd ed. CRC Press, 2019

[^LevelDesignClutteredOverview]: <a id="LevelDesignClutteredOverview"></a> S. Rogers, “Levels” in *Level Up! The guide to great video game design*, John Wiley & Sons Inc, 2014, ch.9

[^ArchitecturalLD]: <a id="ArchitecturalLD"></a> C. W. Totten, *An Architectural Approach to Level Design*, 2nd ed. CRC Press, 2019

[^LDPractices]: <a id="LDPractices"></a> J. O. Fares Kayali, “Level design practices for independent games,” in *Level Design Processes and Experiences*, CRC Press, 2017, ch.6

[^HiddenGuidance]: <a id="HiddenGuidance"></a> B. C. João Raza, “The illusion of choice - how to hide linearity of levels,” in *Level Design Processes and Experiences*, CRC Press, 2017, ch.10

[^LevelDesignPlanning]: <a id="LevelDesignPlanning"></a> J. Burgess, “Level design planning for open-world games,” in *Level design: Processes and Experiences*, CRC Press, 2017, ch. 12, pp. 243–272

[^Meaning]: <a id="Meaning"></a> D. M. R. Johnson, “Meaning,” in *Procedural Generation in Game Design*, CRC Press, 2017, ch. 27, pp. 301–311

[^GatesTypes]: <a id="GatesTypes"></a> D. J. Dormans, “Graphs and cycles,” in *Procedural Generation in Game Design*, CRC Press, 2017, ch.9

[^LDGuidelinesProfessional]: <a id="LDGuidelinesProfessional"></a> M. Barclay. “My level design guidelines.” (2016), [Online]. Available: [https://mikebarclay.co.uk/my-level-design-guidelines/](https://mikebarclay.co.uk/my-level-design-guidelines/)

[^FortniteLDFundamentals]: <a id="FortniteLDFundamentals"></a> E. Games. “Level design fundamentals.” (2023), [Online]. Available: [https://dev.epicgames.com/community/learning/tutorials/3VKJ/unreal-engine-fortnite-level-design-fundamentals](https://dev.epicgames.com/community/learning/tutorials/3VKJ/unreal-engine-fortnite-level-design-fundamentals)

[^LevelDesignBook]: <a id="LevelDesignBook"></a> R. Y. Smith. “The level design book.” (2023), [Online]. Available: [https://book.leveldesignbook.com](https://book.leveldesignbook.com)

[^JesusMachinaLD]: <a id="JesusMachinaLD"></a> J. Machina. “Define primero, diseña tu nivel después.” (2020), [Online]. Available: [https://youtu.be/1nq-FemmLrM](https://youtu.be/1nq-FemmLrM)

[^SpatialCommunication]: <a id="SpatialCommunication"></a> P. Field, “Spatial communication in level design,” in *Develop Digital*, (2020). [Online]. Available: [https://www.youtube.com/watch?v=AKeUZVikPV8](https://www.youtube.com/watch?v=AKeUZVikPV8)

[^LDPrinciples]: <a id="LDPrinciples"></a> D. Taylor, “Ten principles for good level design,” in *GDC*, (2013), [Online]. Available: [https://gdcvault.com/play/1017803/Ten-Principles-for-Good-Level](https://gdcvault.com/play/1017803/Ten-Principles-for-Good-Level)

[^HolisticLD]: <a id="HolisticLD"></a> S. Lee, “An approach to holistic level design,” in *GDC*, [https://gdcvault.com/play/1024301/Level-Design-Workshop-An-Approach](https://gdcvault.com/play/1024301/Level-Design-Workshop-An-Approach), 2017

[^GDCNonlinearLD]: <a id="GDCNonlinearLD"></a> A. Serr, “Designing radically non-linear single player levels,” in *GDC*, [https://gdcvault.com/play/1026398/Level-Design-Workshop-Designing-Radically](https://gdcvault.com/play/1026398/Level-Design-Workshop-Designing-Radically), 2021

[^CognitiveMaps]: <a id="CognitiveMaps"></a> N. Oueijan, “Stop getting lost: Make cognitive maps, not levels,” in *GDC*, [https://gdcvault.com/play/1027206/Stop-Getting-Lost-Make-Cognitive](https://gdcvault.com/play/1027206/Stop-Getting-Lost-Make-Cognitive), 2022

[^GDCPlaygrounds]: <a id="GDCPlaygrounds"></a> A. Yoder, “Playgrounds and level design,” in *GDC*, [https://gdcvault.com/play/1025884/Level-Design-Workshop-Real-World](https://gdcvault.com/play/1025884/Level-Design-Workshop-Real-World), 2019

[^BOTWModularity]: <a id="BOTWModularity"></a> Nintendo EPD, *The making of the legend of zelda: Breath of the wild*, Developer Interview, 2017. [Online]. Available: [https://youtu.be/30jGWna4-Ns](https://youtu.be/30jGWna4-Ns)

[^LDInteroperability]: <a id="LDInteroperability"></a> J. Burgess, *Skyrim’s modular level design*, Game Developers Conference, 2013. [Online]. Available: [http://blog.joelburgess.com/2013/04/skyrims-modular-level-design-gdc-2013.html](http://blog.joelburgess.com/2013/04/skyrims-modular-level-design-gdc-2013.html)

[^SpatialDocumentation]: <a id="SpatialDocumentation"></a> R.-Y. Storm, *Spatial documentation: Gyms, zoos, and museums*, (2021), [Online]. Available: [https://youtu.be/5PJRCz0t7yY](https://youtu.be/5PJRCz0t7yY)

[^GDCCuriosity]: <a id="GDCCuriosity"></a> K. Beachum, “Sparking curiosity-driven exploration through narrative in ’outer wilds’,” in *GDC*, [https://gdcvault.com/play/1027368/Independent-Games-Summit-Sparking-Curiosity](https://gdcvault.com/play/1027368/Independent-Games-Summit-Sparking-Curiosity), 2021

[^LDCuriosity2]: <a id="LDCuriosity2"></a> A. Beachum. “Designing for curiosity in outer wilds.” [https://youtu.be/vGnce1Dp9BU](https://youtu.be/vGnce1Dp9BU). (2023)
