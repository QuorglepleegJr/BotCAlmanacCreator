The code and exe generate a .html file for an almanac for a BotC script json automatically, in the Bloodstar style.

Night order is as of now not functional, but you can construct the rest of the setup by adding extra parts to the json.

All characters need:
  - "id" (sometimes in the format "namelowercase_scriptname", but any format works)
  - "name"
  - "team" ("townsfolk", "outsider", "minion", "demon", "traveler")
  - "ability"

The program will crash without these.

You can also add:
  - "overview"
  - "examples" (this is formatted as a list of strings, each one being one example - e.g. ["interaction1", "interaction2"]
  - "howtorun" (this is a single string)
  - "tip"
  - "image" (this is a link to the image file hosted online somewhere, as a string)

If it breaks, ping me on discord (@quorg), unless you can see an obvious problem with the json file or wish to try fix it yourself.
