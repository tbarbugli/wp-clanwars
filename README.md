## WP-ClanWars plugin for WordPress

WP-ClanWars is a content management plugin for e-sports teams and gaming communities. It supports multiple games, sidebar widget, match browser, and allows multigamings to delegate match scheduling between multiple war arrangers using simple access control system.

Plugin creates a post for every match, all posts are published under category set in plugin settings. I suggest to create a separate category for all matches so you don't mix it with any other blog posts. Since every match is a regular post, it means that they will show up all over your website. If it's not desired, you will have to restrict matches category from being shown on specific pages of your website (e.g. on front page). I guess there are plenty of plugins for that or you can always do it manually by fixing your theme files. I would also suggest to avoid any changes to the content of created posts because plugin overwrites post content on match update.

By default plugin uses it's own stylesheet which can be disabled in plugin settings. If you decide to make a custom CSS for your website, as example, take a look at default styles: [site.css](https://github.com/pronebird/wp-clanwars/blob/master/css/site.css) and [widget.css](https://github.com/pronebird/wp-clanwars/blob/master/css/widget.css).

Plugin supports a match browser, which can be displayed for visitors using `[wp-clanwars]` shortcode. I suggest to create a separate page for it.

## Help out to translate this plugin

Wanna see WP-ClanWars in your language? Help out to translate it!

https://www.transifex.com/projects/p/wp-clanwars/

Thanks everyone for participation!

## TODO

* Set post date to match date to hide future posts
* Import or export teams
* Add tournament logo
* ~~Add team logo~~
* Add twitch / stream URL to the match (display it in sidebar)
* ~~Add screenshots to match editor.~~
* Add line up.
* Limit game icon dimensions
* Option to disable upcoming matches
* Add sort options in widget
* Match search
* Pagination in widget or load more

I work on this plugin in free time and I don't have much of it, so all contributions are welcome.

### Installation

The plugin is available on WordPress.org:

https://wordpress.org/plugins/wp-clanwars/

__This plugin requires at least PHP 5.3__

### Features

* __Games management__: add your own games, manage maps, export, import others.
* __Match management__: create match, there is no limit for number of maps per match or number of rounds per map, extra information like "External League URL", "Practice War" or "Official Match" can be also specified, final score is calculated automatically.
* __Teams management__: mostly informational, the only useful thing is to setup your team and mark it as home team. Home team is selected by default when you add a new match.
* __Import/Export__: you can save a pack of games that you created on your own, all games are exported with maps attached to them. Can be useful if you need to transfer a game from one website to another. Plugin comes with 7 game packs built-in which can be installed from Import menu.
* __Access Control__: grant your war arrangers an access to match management.
* __Match Browser__: site visitors can navigate through all matches.

### Screenshots

#### Score card and widget
![Score card and widget](screenshot-1.png)

#### Install & share games
![Install & share games](screenshot-2.png)

#### View matches
![View matches](screenshot-3.png)

#### Edit match
![Edit match](screenshot-4.png)
