# NPCgenerator

WIP Npc generator for use in TTRPGs. Based on Wololo-95's Chest of Many Faces, integrated with 
MiniLLM running LLAMA-13B. You will need to install MiniLLM according to https://github.com/kuleshov/minillm to this directory.
Download the model and place in lib/.

Using an API call for any major LLM will be faster and produce superior results - this project exists as proof of concept for locally running LLM tools.


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
