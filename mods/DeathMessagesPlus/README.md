A mod to let you add your own death messages. By default will disable the base game's messages and only include a single placeholder message.

config options:

- `death_messages`
  - an `Array` of death messages to randomly pick from upon death. must be strings.
  - Example of a list of three different messages: `"death_messages":["frick!!", "frack!!", "frock!!"]`
- `include_custom_messages`
  - a `boolean` indicating if the mod should include the custom messages defined in `death_messages` or not. default is `true`.
- `include_vanilla_messages`
  - a `boolean` indicating if the mod should include the base game's messages or not. default is `false`.

This is an example mod to show how you would go about importing a custom scene into the game using GodotModLoader, so if you're a budding modder, unzip it and give it a look!
