# Spart'n Theme for Octopress

Spart'n is a minimal theme for Octopress that doesn't look like Octopress. Too many Octopress tutorials and themes are nothing more than just changing the colors and typography of Octopress. I was tired of not being able to find a decent looking Octopress theme so I rolled my own (this was before I realized that the Octopress repo's wiki actually has a list of pretty good themes). You can read about the development of Spart'n [here](http://bilpatrianakos.me).

__IMPORTANT!__
Spart'n is currently in the early phases of development. Though it does work there are enough little kinks to work out to warrant a warning not to use this theme if you aren't ready to make a few customizations. That said, the theme is still complete enough for me to comfortable open source it.

# Installation

If you don't have Octopress yet...

```
git clone https://github.com/imathis/octopress.git
```

and then...

```
# Get the theme source
git clone https://github.com/billpatrianakos/spartn.git

# Place the resulting spartn folder in the Octopress themes folder
mv spartn ~/path/to/octopress/.themes/

# Install the theme
rake install['spartn']
rake generate
rake preview # or use rake deploy to view your blog
```

Alternatively, you could just `cd` into your .themes folder and clone the repo there.

# Features

Spart'n has nothing new and nothing has been left out. Everything you could do in the Classic theme you can do in the Spart'n theme.

# Roadmap

I'm currently using Spart'n for my own blog so you can be sure this project will be updated and a more polished version should appear here in the coming weeks. I'd be happy to include pull requests and respond to any issues you may have!