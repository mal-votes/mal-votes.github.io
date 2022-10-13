GitHub Markdown emoji don't seem to work in Github Pages, so I found a good blog post in enabling them in Github Pages. Beware that the emoji are slightly different (I assume different sources/licenses), so do test the results when you use them.

E.g. I was using ''':white_check_mark:''' ("white_check_mark" enclosed in ":" colon characters) which is usually a white check mark against a green background and Jemoji presented a slightly greyer white check mark against a white background (my page's background) instead, so I switched to ''':heavy_check_mark:''' ("heavy_check_mark" enclosed in ":" colon characters) expecting the standard bolded black check mark, and got, instead, a green check mark, against my page background (white), so it worked out, but not as I expected it to.

Here's a [good blog](https://davemateer.com/2019/05/27/Jemoji) explaininng how to enable the Jemoji plugin into GitHub Pages. 

Also note that further complicating matters, when your .md files that you create in GitHub proper for your GitHub Pages site are rendered in preview, they use GitHub Markdown's standard emojis, so you only see the final, published results when you publish the page to the GitHub Pages site. So yeah, test in production. Yay!
