# Oi, sou o Felipe! :D

### Sobre o repositório

Tudo bão?👋 Se vc entrou pra olhar 👀 e ver o que tenho de projetos prontos, estou estudando um pouco e vou ainda colocar meus projetos de portifolio por aqui, então perae que vai ter mais coisas vindo!

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/felipecarli/)](https://www.linkedin.com/in/felipecarli/)

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
Note: Available ranks are S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), and B+ (everyone). The values are calculated by using the cumulative distribution function using commits, contributions, issues, stars, pull requests, followers, and owned repositories. The implementation can be investigated at src/calculateRank.js.

Hiding individual stats
To hide any specific stats, you can pass a query parameter ?hide= with comma-separated values.

Options: &hide=stars,commits,prs,issues,contribs

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
Adding private contributions count to total commits count
You can add the count of all your private contributions to the total commits count by using the query parameter ?count_private=true.

Note: If you are deploying this project yourself, the private contributions will be counted by default. Otherwise, you need to choose to share your private contribution counts.

Options: &count_private=true

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
Showing icons
To enable icons, you can pass show_icons=true in the query param, like so:

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
Themes
With inbuilt themes, you can customize the look of the card without doing any manual customization.

Use &theme=THEME_NAME parameter like so :-

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
All inbuilt themes :-
dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

GitHub Readme Stats Themes

You can look at a preview for all available themes or checkout the theme config file & you can also contribute new themes if you like :D

Customization
You can customize the appearance of your Stats Card or Repo Card however you wish with URL params.

Common Options:
title_color - Card's title color (hex color)
text_color - Body text color (hex color)
icon_color - Icons color if available (hex color)
border_color - Card's border color (hex color). (Does not apply when hide_border is enabled)
bg_color - Card's background color (hex color) or a gradient in the form of angle,start,end
hide_border - Hides the card's border (boolean)
theme - name of the theme, choose from all available themes
cache_seconds - set the cache header manually (min: 1800, max: 86400)
locale - set the language in the card (e.g. cn, de, es, etc.)
border_radius - Corner rounding on the card_
Gradient in bg_color
You can provide multiple comma-separated values in bg_color option to render a gradient, the format of the gradient is :-

&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
Note on cache: Repo cards have a default cache of 4 hours (14400 seconds) if the fork count & star count is less than 1k, otherwise, it's 2 hours (7200 seconds). Also, note that the cache is clamped to a minimum of 2 hours and a maximum of 24 hours.

Stats Card Exclusive Options:
hide - Hides the specified items from stats (Comma-separated values)
hide_title - (boolean)
hide_rank - (boolean) hides the rank and automatically resizes the card width
show_icons - (boolean)
include_all_commits - Count total commits instead of just the current year commits (boolean)
count_private - Count private commits (boolean)
line_height - Sets the line-height between text (number)
custom_title - Sets a custom title for the card
disable_animations - Disables all animations in the card (boolean)
Repo Card Exclusive Options:
show_owner - Show the repo's owner name (boolean)
Language Card Exclusive Options:
hide - Hide the languages specified from the card (Comma-separated values)
hide_title - (boolean)
layout - Switch between two available layouts default & compact
card_width - Set the card's width manually (number)
langs_count - Show more languages on the card, between 1-10, defaults to 5 (number)
exclude_repo - Exclude specified repositories (Comma-separated values)
custom_title - Sets a custom title for the card
⚠️ Important: Language names should be uri-escaped, as specified in Percent Encoding (i.e: c++ should become c%2B%2B, jupyter notebook should become jupyter%20notebook, etc.) You can use urlencoder.org to help you do this automatically.

Wakatime Card Exclusive Options:
hide - Hide the languages specified from the card (Comma-separated values)
hide_title - (boolean)
line_height - Sets the line-height between text (number)
hide_progress - Hides the progress bar and percentage (boolean)
custom_title - Sets a custom title for the card
layout - Switch between two available layouts default & compact
langs_count - Limit number of languages on the card, defaults to all reported langauges
api_domain - Set a custom API domain for the card, e.g. to use services like Hakatime or Wakapi
range – Request a range different from your WakaTime default, e.g. last_7_days. See WakaTime API docs for list of available options.
GitHub Extra Pins
GitHub extra pins allow you to pin more than 6 repositories in your profile using a GitHub readme profile.

Yay! You are no longer limited to 6 pinned repositories.

Usage
Copy-paste this code into your readme and change the links.

Endpoint: api/pin?username=anuraghazra&repo=github-readme-stats

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
Demo
Readme Card

Use show_owner variable to include the repo's owner username

Readme Card

Top Languages Card
The top languages card show a GitHub user's most frequently used top language.

NOTE: Top Languages does not indicate my skill level or anything like that; it's a GitHub metric to determine which languages have the most code on GitHub. It's a new feature of github-readme-stats.

Usage
Copy-paste this code into your readme and change the links.

Endpoint: api/top-langs?username=anuraghazra

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
Exclude individual repositories
You can use ?exclude_repo=repo1,repo2 parameter to exclude individual repositories.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
Hide individual languages
You can use ?hide=language1,language2 parameter to hide individual languages.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
Show more languages
You can use the &langs_count= option to increase or decrease the number of languages shown on the card. Valid values are integers between 1 and 10 (inclusive), and the default is 5.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
Compact Language Card Layout
You can use the &layout=compact option to change the card design.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
Demo
Top Langs

Compact layout
Top Langs

Wakatime Week Stats
Change the ?username= value to your Wakatime username.

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
Demo
willianrod's wakatime stats

willianrod's wakatime stats

Compact layout
willianrod's wakatime stats

All Demos
Default
Anurag's GitHub stats

Hiding specific stats
Anurag's GitHub stats

Showing icons
Anurag's GitHub stats

Customize Border Color
Anurag's GitHub stats

Include All Commits
Anurag's GitHub stats

Themes
Choose from any of the default themes

Anurag's GitHub stats

Gradient
Anurag's GitHub stats

Customizing stats card
Anurag's GitHub stats

Setting card locale
Anurag's GitHub stats

Customizing repo card
Customized Card

Top languages
Top Langs

Wakatime card
willianrod's wakatime stats

Quick Tip (Align The Repo Cards)
You usually won't be able to layout the images side by side. To do that you can use this approach:

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>


Made with ❤️ and JavaScript.



<!---
fehcarli/fehcarli is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
