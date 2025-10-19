
# Speed Up Your GB Studio Game!

Ever feel like your hero is wading through molasses? Want to give your game a little more zip? You're in luck! In this quick-fire guide, we'll show you how to tweak your player's speed in GB Studio.

## The Secret File

Your GB Studio project holds all its core settings in a special place. The file you're looking for is `project/settings.gbsres`. This little text file is the control panel for your game's engine.

## The Magic Line

Open up `project/settings.gbsres` in your favorite text editor. Amongst the various settings, you'll find this little gem:

```json
"startMoveSpeed": 1
```

This line controls the walking speed of your character in top-down scenes. By default, it's set to `1`.

## How to Change It

To change the speed, simply change the number. For a noticeable difference, try a value of `2` or `3`:

```json
"startMoveSpeed": 2
```

Save the file, build your game, and watch your character zoom!

## Pro-Tip

Experiment with different values to find the perfect speed for your game. Small changes can make a big difference to the feel of your game.

## What about other game modes?

For those of you making platformers, you might have noticed the `project/engine_field_values.gbsres` file. This file contains more advanced settings for things like jump height and gravity. We'll dive into that in a future issue!

Happy game making!
