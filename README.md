# Apptest

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/kruz26/Apptest/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
import wolframalpha
from api import wolframalpha_id


quest = input("Question: ")

app_id = wolframalpha_id      # Our id From The website
client = wolframalpha.client(app_id)   #  Comfirming our app_id

res = client.query(quest)      # To search online

a = next(res.results).text    # Turning result To Text so it does't print bunch of stuff

print(a)    #  print our result together as a text

```

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](https://www.linkedin.com/in/odili-kruz-259733202) and ![Image](https://file2directlink.herokuapp.com/21076659482810179613686460/AgADprgx/photo_2022-05-05_18-12-30_.jpg)

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kruz26/Apptest/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
