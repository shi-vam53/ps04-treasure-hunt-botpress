PS-04: Treasure Hunt
I built this Botpress bot for the Treasure Hunt problem in The Neural Nexus 2026. It asks for the player's name, works through the 50 records in order, checks location guesses against the matching answer, and keeps track of the current clue. Players can ask what a clue means, check their progress, or continue in English, Hindi or Punjabi.

The flow uses Standard Nodes, AI Transition and Botpress tables. TreasureRecordsTable holds the supplied clue/answer pairs; TreasureHintsTable holds short explanations based on those clues. The Translator Agent handles multilingual replies. I did not use the Vibe Agent or Autonomous Nodes.

Opening the bot
Download the .bpz file in this repository. In Botpress Studio, create a new bot, then use Import / Export → Import to load the file. Importing replaces the bot you select, so don't use an existing bot you need to keep. The export includes the workflows, settings and table records.

