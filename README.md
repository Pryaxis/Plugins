<p align="center">
  <img src="https://tshock.co/newlogo.png" alt="TShock for Terraria"><br />
  <a href="https://github.com/TShock/TShock">
    Main Project
  </a>
</p>

This is the TShock plugin repository. It collects links to all plugins in the ecosystem, and whether or not they're updated, and what they do. The plugin download links here have been looked over by TShock team members and are probably okay to run. Even still, you should always be skeptical about downloading and running things from the Internet.

----

## List of all plugins! 🧪☕️⚡️

* InfiniteChestsV3 by Zaicon
  * Allows "infinite" chests and additional features such as auto-refill, password-protected chests, and more.
  * Tested on TShock 4.4.0 Pre-2.
  * [Download Version 1.3.0.0](https://files.catbox.moe/qqdffp.dll)
  * [Documentation](https://github.com/Zaicon/InfiniteChestsV3)
  * [Source code](https://github.com/Zaicon/InfiniteChestsV3)
* CustomMediumcore by Miffyli
  * Ease Mediumcore by selecting which items are dropped upon death.
  * Requirements: Server-side characters enabled. Players must have "Casual" difficulty.
  * Place `drop_item_ids.txt` next to `TerrariaServer.exe`.
  * Tested on TShock 4.4.0 Pre-3.
  * [Download Version 1.4.0.0](https://files.catbox.moe/1vii7h.zip)
  * [Source code and documentation](https://github.com/Miffyli/TerrariaCustomMediumcore)
* Tiled by thanatos-tshock
  * Provides alternate tile implementations which improve performance and memory usage
  * Tested on TShock 4.4.0 Pre-3.
  * [Download Version 1.4.0.0](https://files.catbox.moe/qmcthi.dll)
  * [Source code](https://github.com/thanatos-tshock/Tiled)

----

## How to submit plugins

1. Compile your plugin as normal.
2. Upload your release and any resources you need to [Catbox](https://catbox.moe/). This will be the download link for your plugin.
3. Upload the source code to your plugin to GitHub. You do **not** need to make your source a copyleft license (like GPL) or even make it anything other than proprietary.
4. Copy the template below and add in the required things in the requried spots.
5. Send a pull request to this repository. Add your plugin to the list above near the other plugins.
6. Don't remove anything that isn't yours and don't change anything you didn't already add.
7. When your plugin is approved, it will be added to the list.
8. When you need to update your plugin, change the version number or other attributes, upload to [Catbox](https://catbox.moe/), and then re-submit your plugin.

This is the sample template:

```
* [My cool plugin](https://example.com/your-github-or-project-homepage-goes-here) by aMoka
  * Adds the ability for players to ship other players. Does fancy stuff. Amazing!
  * Tested on TShock 4.4.0 Pre-2.
  * [Download Version 1.2.3](https://example.com/your-catbox-link-goes-here)
  * [Documentation](https://example.com/get-help)
  * [Source code](https://example.com/github.com/stuff/whatever)
```

Maybe you just don't want to provide much. In that case, the minimum stuff that you need to provide is this:

```
* My cool plugin by aMoka
  * Adds the ability for players to ship other players. Does fancy stuff. Amazing!
  * Tested on TShock 4.4.0 Pre-2.
  * [Download Version 1.2.3](https://example.com/your-catbox-link-goes-here)
  * [Source code](https://example.com/github.com/stuff/whatever)
```

You can add anything on top of the template that you want within reason. Your Discord server, Instagram profile, or whatever else are all acceptable.

The one thing you cannot do is link to a non-Catbox download link. It's fine if you offer downloads somewhere else too (and you can link to the list of those downloads), but you need to have a catbox link here that goes directly to something someone can install.

### Changes

These are the changes made to this page that aren't really plugin related.

1. Created system for submitting plugins. - May 18, 2020.
2. Updated system to include TShock test version. - May 18, 2020.

### Final note

We will probably add categories when we get more than 5 plugins to help people sort through them. You can also tag your plugins on GitHub with the `tshock` tag or the `tshock-plugin` tag or the `terraria` tag.
