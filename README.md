# NPCgenerator

WIP Npc generator for use in TTRPGs. Based on Wololo-95's Chest of Many Faces, integrated with 
MiniLLM running LLAMA-13B. You will need to install MiniLLM according to https://github.com/kuleshov/minillm to this directory.
Download the model and place in lib/.

Using an API call for any major LLM will be faster and produce superior results - this project exists as proof of concept for locally running LLM tools.


# Selected Outputs

Input:
You are roleplaying as an NPC in a fantasy setting. Your personality and traits
can be described as:  Name:  Kappi Hicks Race:  Human Sex:  Male Alignment:
Neutral Good Personality:  I face problems head-on. A simple direct solution is
the best path to success. Ideal:  Aspiration. Someday I'll own my own ship and
chart my own destiny. (Any) Bond:  I once met a deity in disguise on the
material plane. It changed my life completely, for good or ill. Flaw:  I involve
myself in everything. Quirk:  Constantly distracted  Please write a short
background for the NPC in first person.

Output: 
Also, if you want to describe the deity
you met, do so.  Keep in mind the description you provide for your NPC will
directly affect the DM's treatment of him in the campaign.  This is your first
character, so please post something! Sorry for the late reply. I will do so in a
few minutes. I’m currently in the middle of writing my character’s background.


Input:
You are roleplaying as an NPC in a fantasy setting. Your personality and traits
can be described as:  Name:  Lilliana Malone Race:  Human Sex:  Female
Alignment:  Lawful Neutral Personality:  This NPC seems tired and talks and
walks slowly and kind of in a slumber. Ideal:  Power. Solitude and contemplation
are paths toward mystical or magical power. (Evil) Bond:  Finding my teacher
saved my life. Before meeting them I was on a dark path that likely would have
led to my untimely demise. Flaw:  I'll say anything to avoid having to do extra
work. Quirk:  Often zones out  Please write a short background for the NPC in
first person.

Output:
I've had a rough life, so I've been through a lot. My parents
died when I was very young, and I was raised by my older brother. We worked as
farmers, but one day a traveling band of bandits came to our town. They
kidnapped my brother and I, and forced us into a life of slavery. They treated
me with respect, and I was taught to fight and defend myself. I was trained to
fight by my brother, and when I was strong enough I took a job with the guards
in the town. I learned a lot there, and I learned to fight even more. After many
years of guarding the town, a group of bandits attacked. I fought bravely, and I
was able to hold them off for a while, but they were too strong and they
overwhelmed me. As they were about to kill me, I was rescued by a man named
Sartorius. He was a mage, and he was able to hold off the bandits long enough
for me to escape. He trained me in the ways of magic, and I learned much from
him. I eventually left to travel the world, and I've been learning magic ever
since. I've learned a lot of things since then, and I've gained quite a bit of
knowledge in the ways of magic. I've learned that I'm a wizard, and I'm quite
powerful. I've learned that I can cast fireballs, and I can summon creatures.
I've learned that I can use my magic to protect those that I care about, and I
...

# Details

<h2> Names, Race, Sex</h2>
Names are generated in a very simple system. Race and sex are first determined via simple py lists. Then, using that information, specific text files found in the main folder are accessed, converted to lists, formatted appropriately, before choosing a name at random from the list. More names are planned to be added later.

Names currently pull from random generators of different cultures or works. Some are from other fantasy environments, other from real-world inspiration or historical context.

<h2>Bonds, Flaws, Ideals</h2>
Bonds, Flaws and Ideals are each calculated from a larger list located in the main folder. They are chosen completely at random, with no regard for alignment, race, sex, or otherwise. These aspects can be easily adapted to any character, regardless of the aforementioned attributes, and so the random nature allows for a wider variety of characters to be made.

  <h3>Bonds</h3>
  Bonds are used to create a character's convictions, or their drives, and can often be used as plot pieces. These are often connections to people, palces, things, or events. Bonds are often tied to the character's background, and may be a major motivating factor for their interactions with players. Currently, the generator creates one bond, althought future functionality may allow a custom number.
  
  <h3>Flaws</h3>
  Flaws are used to show some level of weakness, often manifesting in the form of vices, compulsions, fears or weaknesses. If it can be used to exploit the character, it is a flaw. How the character reacts to their own flaws varies greatly from character to character.
  
  <h3> Ideals </h3>
  Ideals are the character's ties to the world; things they believe in fundamentally. These are often guiding moral/ethical principles, or core belief systems. Characters tend to live by their ideals, some may die or sacrifice great things to protect their ideals. Many of the generated tags have recommended alignments still attached to them, but these can be ignored and repurposed. Overall, Ideals do not have to be tied to any particular aspect of a character, but it is a major guiding pillar for them and should be used to help ascertain their motives.
  
<h2>Quirks and Physical Trait</h2>
<h3> Quirks</h3>
Quirks are very simple concepts. These are unique identifiers that might make an NPC stick out in the minds of the players. These can be physical gestures, social oddities, or even medical conditions.
