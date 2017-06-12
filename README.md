# /r/climbing CSS
[/r/climbing](https://www.reddit.com/r/climbing/)'s CSS stylesheet currently contains experimental code that displays a collapsed comment's children on hover.  This results in constantly expanding/collapsing blocks and other potentially undesirable behavior.  The following instructions utilize Reddit Enhancement Suite (RES) to replace [/r/climbing](https://www.reddit.com/r/climbing/)'s CSS stylesheet with an identical stylesheet, minus the hover behavior.  Note that this is intended only to be a temporarily workaround until the official [/r/climbing](https://www.reddit.com/r/climbing/) stylesheet is updated.

## Installation

  * Install Reddit Enhancement Suite (RES) - http://redditenhancementsuite.com/
  * Go to https://www.reddit.com/#res:settings/stylesheet
  * Click `Add Row` in the `Snippets` section
  * Copy+Paste the entire **contents** of [climbing.css](https://raw.githubusercontent.com/zombull/reddit-climbing/master/climbing.css) into the `snippet` textbox, i.e. Ctrl+A Ctrl+C
  * Select the `Only On:` radio button
  * Enter `climbing` in the `applyToSubreddits` textbox
  * (Optional) - Add a toggle name (see [Toggle](#toggle)), e.g. `climbingCSS`, if you want to be able to enable/disable the stylesheet
  * Click `Save Options` in the upper right to save the new RES settings
  * Disable the [/r/climbing](https://www.reddit.com/r/climbing/) subreddit style (see https://www.reddit.com/r/Enhancement/wiki/faq/srstyle#wiki_.2611_use_subreddit_style)

## Toggle
Adding a toggle is optional.  A toggle allows you to enable/disable the custom CSS snippet.  A menu item can also be created, which allows you to control the toggle via the RES dropdown menu.

  * Go to https://www.reddit.com/#res:settings/customToggles
  * Click `Add Row` in the `Toggle` section
  * Enter the name of toggle name you created, e.g. `climbingCSS`
  * Enable or disable the toggle as desired
  * Enter a name in the `menuItem` textbox, e.g. `Climbing CSS`, if you want the toggle to be displayed in the RES dropdown menu