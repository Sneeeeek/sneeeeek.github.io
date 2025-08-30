
# Feixiao Discord Bot Capabilities

My bot, Feixiao, is an AI-driven Discord bot role-playing as Feixiao from *Honkai: Star Rail*. At the time of update, Feixiao uses GPT-5. Here are its main features and capabilities:

1. Commands:
   - !about: Shows information about Feixiao and her features.
   - !context: Uses the last 20 messages in the channel as context instead of the stored history for the next response.
   - !clean: Queries a pure GPT 5 without anything extra (system prompt history). This command is whitelisted to only me currently.
   - !think: If this command is invoked, Feixiao will spend extra time thinking before giving her response.


2.   Custom pronoun options:
      - !setpro: you can use !setpro to set a custom pronoun that will be added to your input (if youve set one), to change your set pronoun you just do !setpro again. 
      - !delpro: To delete your custom pronoun, use !delpro.

3. Chat History: Interactions are logged per channel in JSON files for context and continuity. This means she will, by default, only know whats been said directly to her unless the !context command is invoked. It also means she has a different "memory" per text channel and things dont carry over to other channels.

4. Image Support: Users can send images (png, jpeg, gif, or webp), and Feixiao will attempt to respond with it in mind. She can also read image embeds, though with a caveat: Discord needs to create the embed BEFORE Feixiao recieves it, so if its a brand new link without an embed associated with it, she doesnt get the embed data (becuase it doesnt exist).


5. Custom Emotes: Feixiao can use a set of custom emotes in her replies. At the time of writing, feixiao can use:
   - feixiaoIceCream
   - feixiaoYippee
   - feixiaoGrin
   - glorp
   - glorpXiao
   - feixiaoExcited
   - feixiaoBugCat
   - feixiaoHeart
   - nekoMwah

6. Dog & Cat Images: If asked for a dog or cat (or a funny cat), Feixiao will include an embed with a random dog or cat image using the APIs provided by https://dog.ceo/ or https://cataas.com/.

7. Knowledge Base (WIP): The program recognizes certain keywords when they appear in user messages, and adds a brief system message with some info about the topic to improve her domain knowledge. The system is mostly complete, but the knowledge base needs to be written. **Im looking for writing help, if you are in any way interested in contributing to the knowledge base, please contact me!!!**

8. Error Handling: If an error occurs, Feixiao respond with the error message. If youre getting errors without an obvious reason why, please contact me and provide what youre trying to do or something idk.

For more details, just look at the code or ask me. 
