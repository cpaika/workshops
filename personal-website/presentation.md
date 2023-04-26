# Setting up a Personal Site
---

### Pre-req's
* Have a domain name purchased.  I recommend Hover or Namecheap.
  * I own chrispaika.com and paika.tech for example
* Have a Github Account
* [Install Homebrew if you already haven't](https://brew.sh/)

---

### Why a personal website
1) Own your online brand
* Google your name in a incognito window
---

### Why a personal website
2) Differentiate yourself
* Show your work
* Show your interest
* Would you hire this person?
  * https://ja3k.com/
* I got my job through my writing
---

### Why a personal website
3) Practice writing
* Writing is a critical skill for software

---

### What to put on a personal website
* Every project you do
* Annoying problems you solve
  * ex: "Couldn't figure out how to copy this file into my docker container"
* Keep a low bar - I publish chapter notes. Just regularly publish
---

### How to build personal websites?
* Easiest thing is a static website
* A static site is a bundle of HTML, CSS, and Javascript.
---

### Static Website Generators
* Take Markdown and convert it to HTML
* Super simple - You can write one yourself in a couple days
* Bunch of options: Jekyll, Hugo, Gatsby, Next.js, Slate...
---

### Building the website
* Going to use Jekyll because it integrates with Github well and I know it
* Hugo is a lightly better but your stuck with Jekyll

---
### Overview
1) Create a repo for the blog
2) Initialize a Jekyll blog locally
3) Enable Github Pages
4) Redirect DNS to point at your blog
5) Connect it to your LinkedIn/Twitter/Whatever

### Create a Repo
* Let's go on Github and create a repository, without an initial commit

### Get Ruby Working
```
brew install asdf
asdf plugin add ruby
asdf plugin-update ruby
asdf install ruby latest

asdf reshim

asdf global ruby latest
```

### Install Jekyll
```
gem install bundler jekyll
```

### Initialize a new blog
```
jekyll new <blog name>
cd <blog name>
git init
git remote add origin <git repo>
```

### Enable Github Pages
* Should just work (tm)

### DNS Setup 😬
* We're going to CNAME to our github pages blog

### Publish a "hello world" post

### Link to your LinkedIn

### We're done!
