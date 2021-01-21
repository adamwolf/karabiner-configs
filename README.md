# karabiner-configs
Configuration files for Karabiner Elements, an open source keyboard customizer for macOS

## Usage

Install Karabiner Elements.  Open Karabiner Elements.  It will create a directory for predefined rulesets at `~/.config/karabiner/assets/complex_modifications/`. Copy or symlink JSON files into that directory. In Karabiner Elements, go to Complex Modifications, and under Rules, click Add Rule. You should be able to enable the rules from the JSON files.

## Configurations

* adamwolf-fingerstretchers.json

  If you type a "fingerstretcher" (like capital Y with the right shift or a capital T with the left shift), beep instead of inserting the character.

* adamwolf-microsoft-keyboard.json

  Makes "Microsoft" keyboards with Control/Windows/Alt/Space/Alt/Menu/Control into Control/Option/Command/Space/Command/Option/Control.  You probably only want this applied to certain devices, or your Apple keyboards will go wonky too! (I do not know how to expose locking this to certain devices via the UI, but you can do it with an editor.)
  
## Feedback

If you have any questions or comments, let me know!
