![jungleScreeny](https://user-images.githubusercontent.com/70648519/115128514-496cf200-9fac-11eb-8587-9ffe705925fb.PNG)

<h3>Project Showcase</h3>
<h1>Invicta!<h1>
<h3>Mason Gossy</h3>

<h2>Introduction</h2>
<p>My project is broken up into 2 major parts, documentation and visual coding(scripting/blueprints) both played their own unique role in the development process of this project.</p>
<p>When it came to preparation I knew documentation was going to keep my project organized. Documentation is well practiced in the game industry, and I found that timelines, game design documents and developer notes are the three most important documents to keep track of.</p>

![timeline](https://raw.githubusercontent.com/MasonG27/Game-Development-Project/gh-pages/timeline.PNG)

![GDD](https://user-images.githubusercontent.com/70648519/115128257-77e9cd80-9faa-11eb-82c7-19e36ae9c876.PNG)

![notes](https://user-images.githubusercontent.com/70648519/115128260-7c15eb00-9faa-11eb-991e-2f90eb3870ad.PNG)

<p>Inspiration for this project was driven from Epic Games MOBA(multiplayer online battle arena) game Paragon, which was shut down for financial reasons and in doing so they also released all the assets for free on their game engine, Unreal. These assets are a perfect template for young game developers with limited skills because they provide all the triple A potential, you just need to figure out how to put the pieces(code) back together for things to function properly.</p>

<h2>Month 1 - Map and Environment Design</h2>

![jungleScreeny](https://user-images.githubusercontent.com/70648519/115128514-496cf200-9fac-11eb-8587-9ffe705925fb.PNG)

<p>Although I spent about 25% of development time on environment design, I believe it was a good idea because it allowed me to show my potential as an environment artist. Additionally, it shows professional design techniques since each lane, jungle path and camp had to be strategically placed in order to make sure each side was evenly matched. This was achieved by countless play testing, measuring and timing.</p>
<p>Having a lot of experience from playing this type of game gave me a great stepping stone in designing the map. MOBAS traditionally have 2 bases that each have 5 players start in. The objective is to destroy the opponents base core, each base is separated by 3 lanes and a jungle. Giving each character roles to take part in throughout the match. The five roles are Mid, Jungle, Solo, as well as the ADC(all damage carry) and Support, which play together in their designated lane.</p>

![mapTemplate](https://user-images.githubusercontent.com/70648519/115129528-d320bd80-9fb4-11eb-9f67-2c58727c7527.PNG)

![map](https://user-images.githubusercontent.com/70648519/115129359-1ed26780-9fb3-11eb-86bb-146ff804d39c.PNG)

<h2>Month 2 - Combat System and Character Stats</h2>

![combat system anim](https://user-images.githubusercontent.com/70648519/115127588-9bf6e000-9fa5-11eb-9737-a41754211c98.png)

<p>About a month into the project I began exploring different ways of starting a combat system. I ended up settling on a tag system for detection and overlap collision for damage.</p>

![kwangCombat](https://user-images.githubusercontent.com/70648519/115149294-6566a700-a031-11eb-85cd-020f32ebcdee.PNG)

![meleeBoxBP](https://user-images.githubusercontent.com/70648519/115149284-5ed82f80-a031-11eb-890f-bceb10748432.PNG)

![startCollision](https://user-images.githubusercontent.com/70648519/115149464-4b799400-a032-11eb-82da-b477087f1569.PNG)

![endCollision](https://user-images.githubusercontent.com/70648519/115149468-4fa5b180-a032-11eb-9403-9071e8c96133.PNG)

![Notify](https://user-images.githubusercontent.com/70648519/115149474-53d1cf00-a032-11eb-8500-c7ff93015539.PNG)

<p>The great thing about this combat system is the tagging allows for you to easily do damage to multiple enemies by just adding a tag to them. A great example is the turrets, all I had to do was give them a health variable and tag them as an enemy and boom, they are able to take damage from the player. The reason this is important is it saves so much time instead of reimplamenting the same blueprint and having to adjust different variables.</p> 

<p>Once I got my basic damage system setup it was time to design and add functionality to an enemy. I started with the red buff camp, MOBAS have small areas in the jungle called camps which have monsters that help your character gain experience and gold when killed.</p>

![AI](https://user-images.githubusercontent.com/70648519/115151251-107b5e80-a03a-11eb-8181-5596efb28cf1.PNG)

![notifyAnim](https://user-images.githubusercontent.com/70648519/115151254-140ee580-a03a-11eb-905d-82b946644631.PNG)

![AnimGraph](https://user-images.githubusercontent.com/70648519/115151257-1709d600-a03a-11eb-8b54-041e1714aaee.PNG)


