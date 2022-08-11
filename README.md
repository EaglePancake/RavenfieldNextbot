# Ravenfield Nextbot Tutorial
### This tutorial expects that you know how to export mods and have the newest Ravenfield Tools Pack project setup.
---
1. Download the "NextbotSample" package provided in the releases and import it into your project.

2. You will get 3 files;
  - NextbotContent: This is the file that you will be exporting in the end
  - NextbotDefiniton.lua: This is the script that sets up your nextbots data ingame. The Nextbot Base mutator uses this to setup all of the bots, you shouldn't mess with this.
  - NextbotDefinition (Prefab): This is where you setup your bots properties like the ingame name, texture and sound clips.
  
3. Select NextbotDefinition prefab and change the settings of the bot to your liking:
![image](https://user-images.githubusercontent.com/63953014/184123368-87ab9b07-e784-45eb-a805-81ab8ceb2596.png)

- "isNextBot" : This is what the Nextbot Base mutator uses to determine if this is a nextbot or not, it absolutely has to be in the data container.
- "name" : The ingame name that shows up when selecting nextbots.
- "botTexture" : The texture used for the bots face.
- "roamingClip" : The sound clip that plays on loop while the bot is roaming around.
- "attackClip" : The sound that plays when the bot attacks someone.

### All of these settings have to exist on the data container. Their values can be none but they absolutely have to exist !

4. After you're done setting it up, select the NextbotContent prefab and setup your mod for exporting.
![image](https://user-images.githubusercontent.com/63953014/184124379-4a7032d3-e6b5-49db-92f0-458d76bc99f0.png)

### The configuration fields in the content mod should be pretty self explanatory.

### After exporting the mod you are safe to upload it to the workshop !
