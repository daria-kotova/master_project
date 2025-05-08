# Master's project research progress

# 07-05-2025

Managed to make my assets grabable, now you can move and turn them. Interesting observation: my bf made a monster out of them without even being prompted and he loved the interaction.

<img src="/research/photos/2025-05-07/monster.jpg" width="500"/>

# 06-05-2025

Created my space trash assets by scanning weird trash I found at a construction site using Scaniverse. Textures from photos of trash.

<img src="/research/photos/2025-05-06/objects.jpg" width="500"/>

<img src="/research/photos/2025-05-06/objects_drawings.jpg" width="500"/>

Moodboard and storyboard for the discussion with photograph:

<img src="/research/photos/2025-05-06/moodboard.jpg" width="500"/>

<img src="/research/photos/2025-05-06/storyboard.JPG" width="500"/>



# 28-04-2025

Text 1 (rewritten from the aliens' perspective)

Not to be dramatic or anything, but the universe is a mess. Some aliens can't even keep their spaceships in order without scrambling for a last-minute cleanup before guests dock. Planets are littered with debris, as if waste disposals and recycling systems were some ancient humankind myth. But it doesn't stop on the planetary level. Ever heard of space junk? Thousands of dysfunctional satellites, shattered ships, pieces of abandonned stations, circling the space and potentially threatening to make it unusable one day. And now, you have the chance to see it for yourself. Travel across the galaxies, explore the cosmic chaos. And while you're at it, why not turn some of the junk into something nice? Create art, send a message, tell your story, leave your trace. Trash art isn’t just for planets anymore. The universe could use a little creativity. And don't worry, you won't be doing it alone. After all, unclattering the universe isn’t a one-person job.

# 27-04-2025

After some reflection, I think I want to go back to my original tests with cadavre-exquis-like side where people were building parts of a story one by one. So my project should be:

- Collective
- Creating a story / smth
- Step by step
- Fun!
- It would be nice to have a combination of 2D and 3D
- For who? Teens, young adults (15-35 yo)

———

Finally wrote some texts.

Text 1 (space junk)

Not to be dramatic or anything, but humanity is a mess. Some of us can't even keep our homes tidy without having to be prompted for a last-minute cleanup before guests arrive. Streets are littered with trash, as if there aren't enough bins around. And let's not even get started on pollution on all the possible levels. But it doesn't stop on the planetary level. Ever heard of space junk? Thousands of dysfunctional satellites and broken pieces of rockets orbitting the Earth and potentially threatening to make its orbit unusable one day. But guess what? We aren't the only ones like this. Turns out, aliens aren’t much better. We just haven’t made it to their galaxies yet to see it. But now you have the chance. Travel across the universe, explore the cosmic chaos. And while you're at it, why not turn some of the junk into something nice? Create art, send a message, tell your story, leave your trace. Earth invented trash art, it’s time the universe caught up. And don't worry, you won't be doing it alone. After all, unclattering the universe isn’t a one-person job.

- 3D objects that get sense through added 2D drawings, like in my first tests
- Can use real fun galaxy names for setting the AR scene of each galaxy

Text 2 (shooting stars, meteor showers)

A shooting star streaks across the night sky, leaving behind a fleeting trail of light. Once a solitary rock drifting through space for what seemed like eternity, witnessing everything and nothing, it entered our planet's atmosphere to shine for one brief moment before disappearing once and for all. But what if that moment could last longer? What if the stars could speak? What stories would they tell? In this game, you become the voice of the stars. Together with other players, you draw star trails, piece by piece, unfolding stories across the sky. Mark the sky with unseen trails. Tell the untold stories of the stars.

- Players draw star trails creating stories together, adding pieces of drawings one by one (AR cadavre exquis). The final result is added to the collective sky.
- A bit away from the space in space idea
- Just 2D lines, no 3D
- The collective sky view can be as it is now, but what about the drawing mode?

Text 3 (dark matter)

We were here before you. We will be here long after you are gone. You do not see us, but we see you. We exist in the dark, the dark matter. You wish to know us, but how can we understand each other? Words are too small, languages are too fleeting. There is only one way: the language of symbols and forms, a language understood by everyone and everything. The drawings. This is how you can begin to understand us. But this is not about uncovering who we are. It is about discovering each other. It is about seeing what is already there and what you have not yet learnt to see. Weave the unseen stories together across the void, one mark, one symbol, one thought at a time. Together, you will light up the dark.

- Got carried away, no space present oops

Text 4 (new life)

April 17, 2025 was marked by a new study suggesting the possibility of the presence of life on K2-18b, a planet 124 light years away from Earth. 

to be continued...

Maximize the survival of some cosmic tribe

# 16-04-2025 (mid-jury)

- What do I want to do with it later?
- Lacking the storytelling aspect that I used to have in my paper tests
- Tell more about the galaxy
- Use the actual space more (interactions, objects), prompting in the environment, environment can respond to what you do?
https://www.universaleverything.com/artworks/hyperspace 
- Mixed media from different realities, not just colour
- Me as a mediator of the game? Have a different dynamique
- Continue with the onboarding esthetics
- How to extend the engagement for it to last longer
- How to make people understand they can join others
- Universe view looks like light painting exhibition (...)
- Daniel was confused

# 15-04-2025

New figma prototype with onboarding
https://www.figma.com/proto/t68CNqnTVMu54R0LAwRDKz/Unseen42?page-id=0%3A1&node-id=193-86&viewport=252%2C356%2C0.31&t=BsOL57BuLktGFFtw-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=193%3A86&show-proto-sidebar=1

# 14-04-2025

Talked to Alexia.

- I should choose if I want real images (like from NASA) or somthing imaginary (would require a narrative)
- Vibe-coding -> vide world-building - creating with AI, get inspired by the way we generate stuff with AI
https://www.instagram.com/p/DHRwgEpStGk/?hl=fr
https://updates.midjourney.com/patchwork-user-guide/ 
- Mixed media: AR + physical objects. Co-create / interact with surroundings
- Right now onboarding is disconnected from the rest
- What's the incentive?
- Lacking metaphore, the core
- Who is it for? "Everyone" does't work
- Bring the magic, filters?
- At the end a text about what's been drawn?
- Maybe drawing is just a part of the experience

# 01-04-2025

Not to be dramatic, but so far trying to use Firestore is a big fail :(

It worked at first, saved my AR drawings and all. And then today I checked and there were hundreds of files. Turns out they're generated every time I simply open the app and don't even do anything. It seems there's a lag in the way it's updated, because I saw changes in the Firestore file structure an hour after I had added them in my script and when I no longer had them, cause I thought they hadn't work and deleted them... Probably issue comes from multiple calls. But I don't even know where they come from. At the end, I exceeded the daily free quota of writes and reads.

Gonna step back and try with a simple file. Sad.

# 30-03-2025

Managed to save and reload lines locally! Right now it's just with a txt file with only position data. Will now try it with Firebase.

# 28-03-2025

- How the galaxies are placed? Makes sense if they are spread in the space because in the actual space there's a lot of void. But not too much so that you can still explore by walking in one space without having to cover large distances.
- Possible animation: once you approach a galaxy it becomes active (changes colour?) and you can interact with it (see its name and other info). Can probably use distance from the camera for activation part.
- It can be a sort of a social experiment then I wouldn't need to curate it.
- Who's talking to the user? Somebody from the space who's curious to see the results?
- Possible way of helping with ideas: ask some random question (like "what's you favourite animal?") -> it'll define the name of your galaxy. Can also have "choose for me", where a random name is poroposed. Or choose from a database of names.
- Once you finish, oher galaxies appear around you. Maybe the lines appear gradually. The camera can become darker, while the lines can start glowing.
- May be better with just lines (no 3D objects) to make it minimalistic and coherent. Need to test.

Next steps:

- Onboarding. What exactly is this all about?
- Save lines and reload them

# 26-03-2025 (mid-crit)

Feedback:

- Space in space sounds good, my overall intention was clear.
- Need to think about the scale, how I make transitions between galaxies and the universe.
- Right now it feels like my project can be about space but it can also be about anything. Need to choose and angle and add more of space vocabulary / characteristics so that you can understnad that it's about space visually, without reading the text. - May become clearer once I figure out more the Universe part
- How would "join" work? Is it with someone nearby or with anyone currently using the app. What if they don't want you to join.

Reference about scale (infinitely small - infinitely large):

- Film "the Powers of ten"
- Game "Everything"
- https://mikma.ch/presskit/

# 24-03-2025

Made an onboarding of the app that explains what it is all about. The goal was to try to encourage people to get creative.

https://www.figma.com/proto/t68CNqnTVMu54R0LAwRDKz/Unseen42?page-id=0%3A1&node-id=1-30&viewport=712%2C60%2C0.83&t=H06jYhXZb2F2YFlV-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=1%3A30

The Tree Galaxy and The Happy Sphere Galaxy:

<img src="/research/photos/2025-03-24/IMG_3965.jpg" width="500"/>

https://youtube.com/shorts/PcMrJB1Vq4g

The Mateverse Galaxy:

<img src="/research/photos/2025-03-24/IMG_3968.PNG" height="500"/>

https://youtube.com/shorts/Ucl77LlmSfY

Feedback / observations:

- Already existng absurd names in the onboarding do make you think that you can create absurd stuff. But not everyone reads the text. Added "why not flying cows" in the explanation to give more ideas of what your galaxy can be made of.
- People need time to adjust to the interaction and understand how it works.
- Add some marker or plane to see where exactly you're drawing.
- Maybe it's better to name the galaxy before creating it. But one person didn't want to. Added "name your galaxy" field.
- The third person started creating his galaxy based on actual physical objects (cans of Mate). This wouldn't stay once the galaxy is added to the Universe. Need 3D objects or object detection (no idea how this may work, maybe with preselected objects?).
- Anchors didn't stay and moved once I paused the app :(
- Add possibility to join the galaxy that is currently being created.
- Create clusters of galaxies in the Universe to show those that were created in one space (one room).
- Try with colours.
- Possibility of changing style with a shader (e.g. environment is b&w and drawings are colourful, like UV mode in Deep Field project)
- What is the final goal? How to make people continue using it?
- AI that recognizes what you draw (cool, but I can't have everything)
- Objects can affect each other?
- Need to test with someone who doesn't know my project at all.

# 23-03-2025

Thinking about the structure of what people will be creating

<img src="/research/photos/2025-03-23/IMG_3971.jpg" width="500"/>

So, they will be creating galaxies with stars and planets inside. The galaxies will be then added to the Universe consisting of all the previously created galaxies. Once you create your galaxy, you can choose the "Explore mode" to see the collective Universe.

# 17-03-2025

Drawing lines in space with an ARDrawManager script using LineRenderer and ARAnchors (tutorial https://www.youtube.com/watch?v=kcqcUxVQu0o). Had to adapt his code because a lot of things were deprecated and not working in Unity 6. But it works now!

<img src="/research/photos/2025-03-17/IMG_3902.jpg" height="500"/>

Interestingly, the drawing stays even if I draw for a very long time moving far away from the ARPlane created at the beginning.

<img src="/research/photos/2025-03-17/IMG_3903.jpg" height="500"/>
<img src="/research/photos/2025-03-17/IMG_3904.jpg" height="500"/>

# 13-03-2025

More “serious“ context:

- unburdening yourself by drawing/writing emotions, stress, etc. Others can interact with it and make it go away - doesn’t encourage collaboration
- Switzerland = Alps. Recreating mountain landscape in urban landscape - can be repetitive
- Same but for Lac Léman
- Collective tapestry - boring

# 12-03-2025

Space = where we are, what surrounds us.
Space = outer space -> cosmos

Bringing space to space.

The galaxy is endless and we can only guess what happens at the furthest corners of it. This opens up space for imagination. Participants create together their parts of the galaxy (star systems). It may be something normal as just planets, spaceships, etc. But nothing stops them from coming with something super weird, like a flying cows civilisation. All created star systems form the interpretation of the galaxy.

- 2D + 3D drawings in space
- possibility of drawing together
- possibility of revisiting what you created or what others did in a specific location
- animation for objects

Reference: The Hitchhiker's guide to the galaxy

# 12-03-2025

Talked to Pierre. For multiplayer I'll need to use a server, as well as a database for keep created drawings so that you can see them later.

Need to ckeck out persistant anchors - for putting planes and saving them for later.

# 11-03-2025

Finally managed to import a key shape animation from Blender into Unity (just .fbx didn't work, alimbic requires a plug-in and there's a complication with textures).

How: 1) export from Blender your model in mdd (separate for each moving mesh) and .fbx (note 1: fbx should be without any animation to avoid extra frames; note 2: curves should be transformed to meshes), .mdd alows to create more frames between your existing frames, so that the animation is smooth in Unity; 2) reinport in Blender .fbx, click on the mesh and import its animation in .mdd. 3) export .fbx again. 4) import last .fbx in Unity, this time it has all the keyframe info. 5) add BlendShapeTool script that switches between frames. 6) ta-daa.

https://youtube.com/shorts/j7UD8O3bAqw
https://youtube.com/shorts/A6DjCMNqwNg

# 10-03-2025

Trying Unity AR mobile template that already has basic UI and interactions (+ XCode). It allows you to detect a plane and then spawn multiple objects on it, turn them around Z axis and scale.

<img src="/research/photos/2025-03-10/blob2.PNG" height="500" />

# 07-03-2025

First tests with AR using iPhone's AR Quick Look. Need to use .usdz file format, but couldn't figure out how to add animation with it.

<img src="/research/photos/2025-03-07/blob1.JPG" height="500" />

# 04-03-2025

Geneva is a true melting pot.

https://www.swisstranslate.ch/news/ville-de-geneve/
"Considérée comme étant l’une des villes et cantons les plus cosmopolites du pays, la réputation de Genève en tant que centre international a un effet durable sur sa culture actuelle. Aujourd’hui, près de 40% de la population se compose d’immigrants et de leurs descendants. Ainsi, cette présence de nombreuses communautés étrangères se reflète parune diversité linguistique et culturelle, et par un mélange unique d’influences françaises, allemandes, italiennes, portugaises et espagnoles."

Just like different cultures mix together and form a unique combination in the city, this project is also about mixing stories to end up with one unique combination (or not one). Participants introduce their objects into the space thus forming a collection of objects, they are then combined together and a final outcome is generated. You can interact with it because you write your own story in the city.

Thoughts:

- Prompts for participants, something that would uncover different perspectives; - what is Geneva for you? What do you like the most about Geneva?
- Can be too political
- Can be repetitive - need to ask around

## 27-02-2025

Searching for context.

Post. It's mainly used now for parcels and administrative mail. But what about personal letters? The project can be about leaving messages/words that you want to say to someone far or who’s no longer there or can’t be reached. - Will be more about text rather than drawing. Also, why would you share something personal about your relationships with the rest of the world? Needs to be a context that is in general more global but can be interprated in a personal way.

## 26-02-2025 (mid crit)

Feedback:

- I need to think more about (tangible) context, right now my project is more about a tool. - Kinda what I felt.
- Can be for a museum on some specific topic (like ecosystem in Deep field) (Musée de la Main, Musée de la Rivière, Musée de l'éthnographie). Case study as an investigation
- Can be a tool for mediation / information / education. - Don't really want it to be educative.
- Something in the space where people get together and work (library, co-working space?, grande maquette de la ville)
- Telling stories in different layers: physical scenography + participants' digital input on top. - Don't really want to have a physical part.
- Theatrical performance
- Visit of the city, history of the city. - Not a fun.
- Website of Ville de Genève - have weird themes, like "250 amazing trees of Geneva" https://www.geneve.ch/themes/environnement-urbain-espaces-verts/ville-nature/arbres/250-arbres-decouvrir. - Can be fun

## 25-02-2025

Did one more test with storytelling, 3D objects (png of 3D models) and 2D drawings. This time with Magma, a website that allows you to draw with other people on one canvas - don't need to be physically together.

<img src="/research/photos/2025-02-25/magma-0.png" width="500" />
<img src="/research/photos/2025-02-25/magma-1.jpg" width="500" />
<img src="/research/photos/2025-02-25/magma-2.png" width="500" />

- The goal was actually to test if I needed prompts. I used some random text from ChatGPT. Turned out the prompts were just distracting, sometimes we would even forget about them.
- Confirmed again that the assets do help with inspiration. Even more when they are chosen for you. However, I can't really justify why you would use them in a normal setting.
- It was fun to guess what the other person was trying to create.
- Canvas was limitting.
- Against my idea of doing it in a physical space.

———

Found this project. https://tinanded.com/projects/deepfield

<img src="https://media.graphassets.com/output=format:webp/resize=fit:max,width:1536/0JbaLCXoSGGJOrX6Q6Xc" width="500" />
<img src="https://media.graphassets.com/output=format:webp/resize=fit:max,width:3072/pejA4af9QNbFnslR7HTy" width="500" />

It's super close to what I want to do. Not sure about 2D input on iPads. Otherwise I like how it is transformed into 3D plants and how it's about co-creating an ecosystem.

———

Preparation for mid-crit

Project text: Unseen is a project that explores the
hidden stories surrounding us and that
are waiting to be told.
The project investigates new ways of
collective storytelling in the space by
using 3D objects and 2D drawings in
augmented reality within a social context.
The primary goal is to encourage physical
encounters and co-creation through
new technologies while reconsidering
our surroundings. Aiming to bring people
together through art, it welcomes a broad
audience interested in new forms of
storytelling and spatial experiences.

## 24-02-2025

Tested some possible ways of drawing in space with body/ hands.

1. P5js Mediapipe handtracking. Modified the code that I found so that you could draw with right hand, stop drawing with the left one, and when there're no hands detected by the camera the drawings is erased.

<img src="/research/photos/2025-02-24/mediapipe-1.PNG" width="500" />
<img src="/research/photos/2025-02-24/mediapipe-2.PNG" width="500" />
<img src="/research/photos/2025-02-24/mediapipe-3.PNG" width="500" />

The code is not perfect, there're some random dots sometimes. The precision is meh, very tricky to draw.

2. Drawing with your body using Kinect. Unity + Kinect Azure + Avatar + trail.

Trail attached to a hand

<img src="/research/photos/2025-02-24/kinect-1.PNG" width="500" />

Trail attached to two hands, useful for simmetrical drawings

<img src="/research/photos/2025-02-24/kinect-2.PNG" width="500" />

Trail attached to hands and feet

<img src="/research/photos/2025-02-24/kinect-3.PNG" width="500" />

It's fun, but useless for meaningful drawing. No wonder that most of the time Kinect is used for large-scale experiences, where it's not about the precision but more about getting general body movements to overlay them with some effects.

3. AR apps

a) Gravity. It's not made for drawing, more for putting text or images in the space. But if you put several "-" in a row it gives you a line.

<img src="/research/photos/2025-02-24/gravity-1.PNG" width="500" />
<img src="/research/photos/2025-02-24/gravity-2.PNG" width="500" />

Closer to what I want, but lacks precision, the lines don't start exactly where you want them to. Not sure about the interaction: you tap and then drag by moving the phone.

b) Draw in air (Magic Art - Augmented Reality on App Store). Made specifically for AR drawing, but the quality is questionable, just one rating on App store.

<img src="/research/photos/2025-02-24/draw-in-air.PNG" width="500" />

Line position is even worse, they all start at the centre of the screen. Impossible to draw what you want, unless you don't lift your finger from the screen. But drawing with a finger on the screen seems more natural. Also, lines are volumous without closed caps, looks ugly.

4. Spatial p5 by Tibor (MD graduate). P5js in VR with seethrough mode. One of the scripts involves hand-tracking and allows you to draw

<img src="/research/photos/2025-02-24/spatial-p5-2.jpg" width="500" />
<img src="/research/photos/2025-02-24/spatial-p5-1.jpg" width="500" />

The most precise out of everything tried, hand-tracking is incredible and it's very easy to get what you want. However seethrough mode doesn't really work with Quest 2 (it's all grey and blurry and not visible if you try to cast and record), more suitable for Quest 3. Hence, not super accessible.

Since I want my project to be a) about creating stories through drawing; b) accessible for people; it seems that an AR app would be the best solution. However, I'll need to really figure out how to make it precise. My fear is that it's super tricky and that's why I couldn't find anything decent. But maybe I should look more.

## 23-02-2025

Trying to define better my concept.

Pistes:

1.  A cadavre exquis in the space but for creating stories. Collaborative drawing in space as I've tried before. No constraints, people just draw together using 2D drawings and 3D forms as a base for the objects they add to the story. Tests showed that it already works as it is.

2.  Help a character. Reference: Ivisible roomates by Eran Hilleli and Nicole He https://www.are.na/block/34729964 You find little characters around you with an app, they're motionless and sad. But once you start adding stuff into the space (aka creating an environment or home for them) they become active and happy, may interact with what you've added. More players - more characters, may interact with each other.

<img src="/research/photos/2025-02-24/concept-1.jpg" width="500" />

## 07-02-2025

What kind of storytelling do I want? Simple can be powerful. If it's more elaborated I need to have prompts. But do I actually? Previous tests showed that no prompts lead to more absurd and interesting results. I guess I would like it to be simple though. Right now my project lacks definition, as in why I want to do this. What's the main topic? Currently, it's more about a tool.

Less is more.

Is it a game with constraints or it's up to the users to create the story? A combination would be nice, so that there's still some space for freedom and creativity. But controlled. How do I define it? No idea.

I like the idea of building (creating) together. What do we build? Worlds. Like in Minecraft. But how to keep people interested in creating, really to encourage them to engage. And that's ignoring the technical side...

I also want to have this side of uncovering. Maybe there's something invisible and users can notice that smth is missing and they need to reveal it in some way.

What's the interaction? How do you move things? Definitely hands. Simpler in a way, smoother and more immersive. And how do objects interact with each other? I guess they can affect each other, like merge for example. Or if one is much bigger than another, it can devour the later? A modular world that's constantly transforming.

## 31-01-2025

Need to define parameters of my project:

- How many users? at the same time several or one by one, all together in one space? - can be one, can be multiple, can also observe previous creations made by others
- Sounds, music inputs/prompts? - bg upbeat simple music. not sure about prompts
- But how will the user understand what he needs to do? - need a simple onboarding - text and animation? maybe voiceover will be easier after all
- Is it more about the experience itself or the final outcome? - can't really separate one from another, the two are important. But need to be able to share the result, even if it's by leaving it in the space for others to discover

General thoughts:

- Life motion tracking allows you to be yourself in the space. But is it easy to use? How precise?
- Collective aspect works better in the physical space than 3D. True, it was quite complicated to manipulate 3D objects in Aero. How to make it work?

## 18-01-2025 (open days)

The setup was similar to that from the Test day, but I also added a piece of paper with instructions and a blank spaces for writing down the part of the story you added.

<img src="/research/photos/2025-01-18-open-days/IMG_3345.JPG" width="500" />

<img src="/research/photos/2025-01-18-open-days/IMG_3346.JPG" width="500" />

Observations:

- Some people seemed lazy to read the instructions. Someone saw that it was a project involving drawing and they just drew on the canvas, without learning what it was all about.

- It's easier to create a story using an object as inspiration, as opposed to fitting the object into the story yu want to make.

Ideas:

- Make it trully collaborative. One person puts an object, another draws, the third one explains.

- Make people tell the story based on the created space.

## 16-01-2025 (jury)

References to check:

- Dirk Koy https://www.designboom.com/art/dirk-koy-zurich-360-video-3d-scan-03-10-2017/ - ?
- Bret Victor https://worrydream.com/

Comments:

- Think about prompts, should it be free as it is now? Can be a sound or a word
- Think about scenarios, use cases, context
- Test scales
- Make mockups
- Paper landscape that can be unfolded - ?
- Ignore technology limitations
- Can be pedagogical, for kids?
- What is my role in the experience?

———

Official feedback from the jury:

For the Test Day you created a simple but fun and engaging social activity creating stories through drawing objects in geometric spaces etc, like a 3 dimensional Cadavre exquis. This opens up a lot of possible spaces to work in and brings an engaging social aspect to your themes around drawing across spaces.

Your experiments in AR continue these ideas but beware of jumping into digital too early. You have lots of good ideas so keep going with different physical experiments to explore types of space, scales (tables to cities), interactions to understand what works well, how stories are involved, where there are the most interesting human dynamics, interactions etc and what aspects interest you the most to take forwards.

## 15-01-2025

What I learnt so far:

- Abstract objects work well in helping to overcome the blank page syndrome. More concrete objects can work too, but it's more complicated.

- People love creating together.

- The environment itself may not always be enough to spark ideas and may even be distracting.

- World-building and story-telling is more fun than just a character creation.

- Being able to use the 3D space with both horizontal and vertical surfaces is better than a common horizontal plane.

- _Physical objects + 3D + 2D_ is so far the best combination. But I should think of different purposes for each of the levels.

- Forcing to use certain objects can be more creatively stimulating.

What's next??

<img src="/research/photos/2025-01-15/IMG_3266.jpg" width="500" />

## 14-01-2025

Wanted to try out a bigger setting, but it didn't work, couldn't recognize the surfaces. Maybe it's the limitation of the software or of my iPad.

## 13-01-2025

Trying similar tests with Adobe Aero which allows you to add 3D models in the space around you. Limits:

- There's already a collection of premade abstract objects. Unfortunatelly, half of them didn't work. And you can't change their colour.

- Can't choose several surface anchors, so had to work with one.

- Can't draw straight away, so had to take photos and add drawings in Procreate.

- Not super convenient to doo it with iPad, and my iPhone couldn't handle the Aero app.

Test 1. World-building by adding 3D objects and 2D drawings.

<img src="/research/photos/2025-01-13/1-1.PNG" width="700" />

<img src="/research/photos/2025-01-13/1-2.jpg" width="700" />

Story: a galaxy with an infinite spiral in the centre with planets circling around. A milkyway with tiny skateboarders. A portal with tentacles coming out of it. A many-eyed angel (idea from a previous test). A giant glass of milk that's being poured in the swirl. (Not a super coherent story).

<img src="/research/photos/2025-01-13/2-1.jpg" width="700" />

<img src="/research/photos/2025-01-13/2-2.jpg" width="700" />

Story: there was an alien spacesheep crush in the mountains not far from an attraction park. There some victims and a memorial was build. Little did we know that some aliens survived and stayed in mountains waiting to attack. Meanwhile, in the park a guy wanted to propose on a roller-coaster but dropped his 10k dollar ring in the pond with catamarans. It's all happening in the full moon.

Feedback/observations:

- It was fun, but limitating.

- Paper tests felt more comfortable and less restrictive. Allowed you to work on several surfaces, both horizontal and vertical.

- For one participant the real background (window, table) was distracting. Felt weird, because classroom is a social place made for working. Had to pretend that we weren't in the classroom. Possibly limited creativity and forced to do more abstract stuff. Another participant didn't really mind the bg.

- It was hard to place 3D objects (bugs of the software and bulkiness of my iPad). But the possibility of placing and scaling the objects was good.

- Colour of objects distracted.

- Preferred drawing more than placing the objects. Limitation of not being able to draw straight away.

- The 3D objects brought back the 3D aspect as opposed to photo tests.

———

Test 2. World-building by adding 3D objects, physical objects and 2D drawings.

<img src="/research/photos/2025-01-13/3-1.jpg" width="700" />

<img src="/research/photos/2025-01-13/3-2.jpg" width="700" />

Story: a weirdly shaped modern building with a pond in front of it and a forest nearby. A road leading to a factory. A floating level of the city and a stairway leading to it.

<img src="/research/photos/2025-01-13/4-1.jpg" width="700" />

<img src="/research/photos/2025-01-13/4-2.jpg" width="700" />

Story: there's a football cup happening in the forest with giant robots playing. The referee is on a platform floating above the ground. The human crowd is observing on the stadium. Once the game is over the robots will go back to the world through a portal.

Feedback/observations:

- More fun with paper stuff due to trickiness of placing physical objects while taking into account the digital ones that you can only see through the app on iPad.

- Was appreciated more than test 1, because of the multiple layers of details (physical, 3D, 2D).

- Still confusing because of the bg.

- I find it cool that without an app you can only see some random objects on the table and than with the app you can reveal the significance and see the story (obviously not currently possible, since we can't draw diretly in the app).

———

Conclusion:

- 3 levels of objects turned out to be more fun. Probably need to distinguish what 3D and physical objects can be used for.

- Maybe objects could interact with each other?

- Hide some parts of the story and reveal the whole picture at the end?

- Try different scale/setting (whole room, outdoor)

- Set an abstract theme?

## 10-01-2025

Test of drawing in the space (city), reference: Shira Barzilay (Koketit)

<img src="https://cdn.shopify.com/s/files/1/0269/4846/8770/files/Website_05_fd98475d-9f7a-4bcc-a80b-5f4c34d61c24.jpg?v=1665066911" width="500" />

Test 1: create a character based on objects on the photos

<img src="/research/photos/2025-01-10/test1-1.jpg" width="500" />

<img src="/research/photos/2025-01-10/test1-2.jpg" width="500" />

<img src="/research/photos/2025-01-10/test1-3.jpg" width="500" />

<img src="/research/photos/2025-01-10/test1-6.jpg" width="500" />

<img src="/research/photos/2025-01-10/test1-7.jpg" width="500" />

Feedback/observations:

- Creating characters turned out to be easier and faster, because we all have an idea of what a character is. But once you know what you're doing, it becomes repetitive leading to a new constraint of trying to do something that you haven't already done.

- For some it was difficult to go further than just a face or a stick man. Lack of variation in the results.

- One participant said that it was obvious when she saw the pine tree photo and drew a peacock, while for me a hedgehog was more obvious. Different perspectives on the same thing.

<img src="/research/photos/2025-01-10/test1-4.jpg" width="500" />

<img src="/research/photos/2025-01-10/test1-5.jpg" width="500" />

- Drawback: you can't choose the object (proved on 09.01.2025 that a "forced" object sparks more creativity) and position it as you want. Freedom in positioning is necessary.

- Lacked social aspect and unexpected contribution to the story from others like in previous tests.

- Photos were viewed more as a 2D space, the 3D aspect was often lost.

Conclusion:

- Overall, the objects on photos helped with ideas, but didn't lead to super creative results. Limitation of the task "create a character"?

- Character creation and world-building are two different tasks. The former one is more suitable for one person, while the latter is more fun in collaboration.

- The objects were curated by me. Not everyone pays attention to their surroundings?

———

Test 2: make the space on the photo yours, make it more beautiful, add what's missing or whatever you want. Reference: Concrete genie

<img src="https://i.ytimg.com/vi/BdOucoGD6EE/maxresdefault.jpg" width="500" />

<img src="/research/photos/2025-01-10/test2-1.jpg" width="500" />

<img src="/research/photos/2025-01-10/test2-2.jpg" width="500" />

<img src="/research/photos/2025-01-10/test2-3.jpg" width="500" />

<img src="/research/photos/2025-01-10/test2-4.jpg" width="500" />

Feedback/observations:

- The task wasn't always clear and people interpreted it differently. One participant took it literally and was turning public spaces into her personal ones, ignoring the space itself (the ugly graffiti)

<img src="/research/photos/2025-01-10/test2-5.jpg" width="500" />

- Participant who was struggling with the previous test and claimed he couldn't draw seemed much more invested this time and gave more creative results, since the task was more open in a way.

- Photo with graffiti - painting on wall, not really new

<img src="/research/photos/2025-01-10/test2-6.jpg" width="500" />

- Sometimes people didn't want to add any elements to familiar places.

<img src="/research/photos/2025-01-10/test2-7.jpg" width="500" />

Conclusion:

I wanted to see how the space itself can inspire people, but results showed that it isn't always sufficient to spark ideas.

## 09-01-2025

From the test day, it was clear that people enjoyed the experiment and had a lot of fun creating worlds using abstract objects and drawing. To see clearer what aspects of the experiment impacted more the satisfaction from it, I tried a number of quick variations of the original test.

First, I asked one of the original participants to do the same task but all alone (no photo).

Feedback/observations:

- The experience was less smooth and sometimes she was struggling with where to lead her story further, while in the collective test you can let the other person decide for you the next part

- Since it was just her, she wanted to keep the consistency and used similar objects

- At some time she switched her initial idea: a mountain later became a building

- She was reusing ideas that they had had during the second session of the test day. Need variation of objects. How to make sure that people do not get bored of the same objects?

- Overall impression: less fun and too much to think about. It was in a way easy, but she had to deal with too many ideas, while with others the control of the story-telling is shared.

———

In the second test, the objects were chosen for you.

<img src="/research/photos/2025-01-09/IMG_3207.JPG" width="500" />

Feedback/observations:

- "When the level of freedom is too high, you don’t have freedom anymore". Being forced to use an object actually simplified things and pushed one's imagination.

- Somehow it makes you focus more on the story.

———

Those two quick tests showed that collaboration was essential in making the experiment fun and contributed to a ricjer story-telling, while the freedom of choice of the objects didn't matter that much and rather complicated things.

———

It made sense to try out a similar test (world creation in a group), but with more concrete objects.

<img src="/research/photos/2025-01-09/IMG_3210.JPG" width="500" />

Feedback/observations:

- Using real objects adds to the fun. If you look without knowing the story, it’s random objects, and only the creators really know the story. May be suitable for a drinking game?

- Some people may be trapped by the real object. You really need to ignore their original purpose and focus on the shape which is not always easy.

- Abstract objects open imagination. They immerse more in the world. The story is easier to build. More serious and artsy.

## 18-12-2024 (Test day)

In the first session, I took part in the experiment with others. We started by choosing a place and a time and ended up with a beach scene, nothing crazy. Participants suggested trying to start from zero and not intervening to see what it gives.

<img src="/research/photos/2024-12-18-test-day/session1-01.jpg" width="500" />

<img src="/research/photos/2024-12-18-test-day/session1-02.jpg" width="500" />

Feedback/observations:

- As time went on, we started switching to larger objects (started with small and ended with something big). Some people rely more on the objects and add little drawings, while others become more creative.

- It seems that I unconsciously created "families" of shapes, which was approuved.

- 3d aspect is good and playful (the 3D objects, as well as different surfaces). Would be curious to see it at a bigger scale, maybe in a room.

- Sound as a prompt?

- What people already do: everyone gets the same prompt, you draw a part, then switch with others and continue someone’s drawing -> shows different interpretations of the same thing

———

In the second session things got weird. We started from zero and I was just observing.

Story: flying jacket on the cloud, that can have some rest by hanging on the cliff. The war of three armies. Underworld, with a castle and evil eye. Someone died playing a giant tic tac toe. A gate to enter tic-tac-toe. It’s all imagination of a girl dying her hair.

<img src="/research/photos/2024-12-18-test-day/session2-01.jpg" width="500" />

<img src="/research/photos/2024-12-18-test-day/session2-02.jpg" width="500" />

Feedback/observations:

- Randomness in objects is good. 3D ones are better, they can be interprated differently, from different perspective (angle, viewpoint). Bigger 3D objects work better in terms of story telling, they force you to create a story with them, more imposing. Small ones are more like accessories. Hollow once are more interesting, can draw inside.

- Less fun with predetermined setting.

- Having to describe what you’re doing is good because you have background from the others and have to consider them.

- It's easier to start with a place, but maybe these ideas constrain the way you use the props.

- Different surface levels have different scales.

- Went out of the canvas. But yesterday we didn’t use all of the canvas

- Always wanted to put stuff in the centre.

- Move objects to other places? Smth modular. Rewrite a story?

——

Results

- People found the experiment really fun and entertaining.

- Starting from zero with no predetermined setting really frees up imagination, even though at the beginning it may be complicated to start. It seems that this fact led to a more absurd and fun outcome.

- 3D objects and the possibility of creating in space is more interesting. 3D objects can be interpreted from different angles (same with flat once? Can turn them). From the 3D objects, ones that had halls presented additional opportunities for creation. Bigger objects were driving more the storytelling aspects, while smaller once added details.

- It was important to describe what you were doing, which was holding the structure of the story and forced you to coordinate with previous people.

- The scale varied throughout the levels and really impacted the perception of the world.

- Overall the activity was fun and the use of visual/physical abstract prompts did help with the blank page syndrome and fueled the creativity.

- Should consider using sounds as prompts. Maybe something similarly abstract, that just has a certain rigor or emotion.

- Consider scale of the experience. Some people want to get out of the canvas, while others stay within it.

- Can you move the objects and rewrite the story?

## 17-12-2024

<img src="/research/photos/2024-12-17/IMG_2973%202.JPG" width="500" />

Did some tests with classmates. The first one was with Andrés. This time I left the canvas clear. We were creating the world together by drawing and adding objects in turns, starting from Andrés choosing a place and time. At some point I introduced a rule: every turn you needed to pick an object and draw something around it to integrate it into the space. The space had several dimensions, not just common horizontal surface.

In the end, we didn't really build a world, but rather created a story. Story: New York, 2020, summer. It's a very hot day, there's steam rising from the ground. We can see the Central park, skyscrappers. Andrés is on his way to drop his kid at the kindergarten, but he's stuck at the highway, there're traffic jams and a car accident. Ambulances are trying to get to the injured man, but can't. Andrés gets his coffee and then goes to the accident scene to film it live. But he's not the only one recording, in the sky behind a cloud a helicopter with a cameraman appears. There's also a park with a Guggenheim exhibition. Under the ground, the subway lives its life and a bit above - a system of pipes. In one of them a rat is running attracted by the smell of trash. The trash stinks so terribly that flies are circulating around it on the surface thinking that it's a pile of poop.

The second test was with Jasmine. This time, I changed pieces of paper to rolls of paper, since it's easier to set up. I definitely need more objects, but the concept works well, everyone is entertained and it's interesting to see how people interprate the objects.

<img src="/research/photos/2024-12-17/IMG_2975%202.JPG" width="500" />

Story: we're in Germany, in the mountains. There's a castle on top of the mountain like in Cinderella. On another mountain, goats are running and enjoying their lives. There's a lake with a waterfall and rocks at the bottom. A playground. Suddenly, in the sky a dragon appears. But don't worry, a diabolic angel with thousand eyes is going to fight it. Supporters on the stadium are observing the scene.

Spent the rest of the day making more objects and setting up for the test day.

<img src="/research/photos/2024-12-17/IMG_2988.JPG" width="500" />

<img src="/research/photos/2024-12-17/IMG_2989.JPG" width="500" />

## 16-12-2024

Created various paper/cardboard abstract objects and placed them in the space. Just placing them like that did not give any ideas, need some prompts.

<img src="/research/photos/2024-12-16/IMG_2960.JPG" width="500" />

## 11-12-2024

Brief

_What I want to explore_

How people can interact with their surroundings through drawing.

_How I am going to do it_

- Solutions to “I do not know what to draw” problem (prompts, cues?)
- Ways to draw in the space (movements, voice, digital brushes)
- Motivations
- Community aspect (collaboration, sharing)

_What am I going to create for TEST DAY_

- visual cues (paper prototypes, objects)

_What are the first steps/experiments?_

- see above
- taking photos of ugly spots around the city and “improving them”
- audio cues on a larger scale with GPS-drawings (tried before)

# How it all started

For my master's thesis I chose the topic of GPS-drawings and running. Among the aspects that I liked and decided to carry on with are:

- drawing with your body
- interacting with the space, getting a new perspective on it
- using city as your playground
- community: sharing and creating with others
- the idea of leaving an invisble trace

<img src="/research/photos/thesis/all.jpg" width="500" />

Some of the tests

- giving each other a task of what to draw while running and doing it on the spot without consulting the map

<img src="/research/photos/thesis/cloud.jpg" width="500" />

<img src="/research/photos/thesis/star.jpg" width="500" />

- trying to draw together simultaneously

<img src="/research/photos/thesis/hi.jpg" width="500" />

Results:

- The GPS-tracking wasn't precise enough.
- It was hard to position yourself in the space and even harder to coordinate with each other.
- Curious to see the outcome. Doing it together added to the fun.
