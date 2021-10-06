# How to submit plugins

### Walking through the submission process

1. Compile your plugin as normal.
2. Upload your release and any resources you need to [Catbox](https://catbox.moe/). This will be the download link for your plugin.
3. Upload the source code to your plugin to GitHub. You do **not** need to make your source a copyleft license (like GPL) or even make it anything other than proprietary.
4. Copy the template below and add in the required things in the required spots.
5. Send a pull request to this repository. Add your plugin to the list above near the other plugins.
6. Add tags such as 🔗 or 🔨 if any apply to your plugin. They will be requested in the review if they're not present.
7. Don't remove anything that isn't yours and don't change anything you didn't already add.
8. When your plugin is approved, it will be added to the list.
9. When you need to update your plugin, change the version number or other attributes, upload to [Catbox](https://catbox.moe/), and then re-submit your plugin.
10. New plugins can appear at the top of the list. You are not guaranteed to be at the top of the list for long. If you comment on whether or not you should or shouldn't be placed at the top of the list, you will be placed not at the top of the list. You are forbidden from 'renaming' a plugin to a different name and resubmitting as a new plugin to appear at the top of the list. If we suspect that you have done this, you will be moved to the bottom of the list.

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

### What if plugin reviews are taking forever?
If your plugin hasn't been reviewed in 1 day (give or take a few hours), please send a message to particles#0015 in Discord and a message to argo@hey.com. You will either get $10 US or a Discord Nitro subscription as reward for being significantly delayed. This offer only applies if you are not a TShock collaborator and if the pull-request contains only one plugin change. Please expect a response time of one day per plugin.

### What plugins will get rejected?
* If you update your plugin but don't update `AssemblyVersion` it will be rejected.
* If you upload unknown assemblies that cannot be verified for security origin, it will be rejected.
* If your plugin contains obvious security flaws, including SQL injection attacks, it will be rejected.

### What can I do to help make my review fast?
If you include 3rd party dependencies, please link to dependency download page on nuget. Please minimize the number of dependencies to a reasonable amount. If you submit an exorbotent amount of dependenices, we reserve the right to not review your plugin. If you modify a third party dependency please explicitly state this. Your plugin will be rejected if your third party dependency, e.g., `Discord.Web.dll`, exists on nuget but the assembly you submitted does not match a real version.

Do not make more than one plugin submission per PR.

### What happens if I submit malware?
Your plugin will be rejected, your GitHub account will be reported, and you are required to pay $200 via Bitcoin for the inconvenience of dealing with you. Also, you will be permanently banned from all Pryaxis or TShock related services and your plugin(s) may be rendered inoperable by TShock.
