---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Installing and Managing Python Using pyenv on Mac'
subtitle: ''
summary: ''
authors: []
tags: []
categories: [Python]
date: 2023-01-02T00:00:00+01:00
lastmod:
featured: false
draft: false
text-align: justify
extensions: 
 - hardLineBreak
# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder.

# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.

image:
caption: ''
focal_point: ''
preview_only: false
# Projects (optional).

# Associate this post with one or more of your projects.

# Simply enter your project's folder or file name without extension.

# E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.

# Otherwise, set `projects = []`.

## projects: []
---

<div style="text-align: justify">    
  
The goal of this post is pretty trivial: act as a reference on how to install and manage Python versions on Mac/Linux. I recently got annoyed I had to Google it again across several websites to grab the necessary terminal commands, so here we are.


## Commands to Execute


First you'll need [homebrew](https://brew.sh/). Install it if not already done.

We will use [pyenv](https://github.com/pyenv/pyenv), which is (probably?) the best way to manage Python on your system in 2023. Let's get started by opening your terminal and enter:

```bash
brew install pyenv
```

Once done, modify `vim ~/.zprofile`by adding:

```bash
eval "$(pyenv init --path)"
```

And then `vim ~/.zshrc` with:

```bash
if command -v pyenv 1>/dev/null 2>&1; then
    eval "$(pyenv init -)"
fi
```

Then install Python and set it globally by running (latest at time of writing this is 3.11.1, modify accordingly by checking the available list at `pyenv install -l`):

```bash
pyenv install 3.11.1 

pyenv global 3.11.1
```

Finally add the following to `~/.zprofile`:

```bash
eval "$(pyenv init --path)"
```

Tada! We're done. Relaunch your terminal or run `source ~/.zprofile` and Python will now be installed and ready to go.


## Additional Useful Commands and Resources

```bash
pyenv versions # List installed Python versions
pyenv install --list # List available Python versions
```

To manage versions on your systems, read: https://realpython.com/intro-to-pyenv/#specifying-your-python-version.


Happy coding!

</div>
