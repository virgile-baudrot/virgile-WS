# virgile-WS

[personnal website at this link](https://www.virgile-baudrot.me/)

This web site as been generated with the `blogdown` R package.

For more information about 'blogdown': [blogdown book website](https://bookdown.org/yihui/blogdown/)

# Add new content

To add a new post, publication, project or talk, go to the file `content` and
then in the file corresponding to the type of article.

To add a new post with Rstudio, the best is to use the `addin` `New Post` or
with the `blogdown` R package use the following code:

```
blogdown::new_post()
```

# Place to look at for any changes

To change something in the global (pictures, institution, menus, ...), see: `config.toml`

- Darwin tree picture: `public`-> `img`
- ID picture: `public`-> `img`

- `Home`:  `content` -> `home` -> `start.md`
- `About Me`:  `content` -> `home` -> `about.md`. To change about left banner (picture, position, links), see `config.toml` and `public`-> `img`
- `Publications`: `content` -> `publication`
- `Posts`: `content` -> `post`
- `Projects`: `content` -> `project` (the log for trophicR is in `public`-> `img`)
- `Teaching`: `content` -> `home` -> `teaching.md`
- `Contact`: `content` -> `about` -> `contact.md`

To add a new publication, the best is to copy/past a previous publication.

# Syntax in articles

The LATEX syntax does not work ! Resulting in failed in the publication of posts.

# For publication

- Project is *Gitted* on the Github repository [virgile-WS](https://github.com/virgile-baudrot/virgile-WS)
- Netlify is then used to deployed the website [netlify](https://www.netlify.com/)
