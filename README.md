[![Netlify Status](https://api.netlify.com/api/v1/badges/529f4c62-9c9e-4325-b285-63d9c6a765e1/deploy-status)](https://app.netlify.com/sites/startling-dolphin-15f816/deploys)

# Tarek Anous's group website

This Readme is copied and edited from Chris Mcfarland's group website [github deployment page](https://github.com/cancerevo/website). Follow the link for more information.

This static website is built using the [Academic Template](https://academic-demo.netlify.app/) for hugo. It is deployed by Netlify at www.tarek-ano.us. 

New group members should follow this short tutorial in order add themselves to the website. This task should familiarize you with Package Management Systems for installing software, and git - the most common version control system in use today. If you haven't used these systems, I'd first read about them a little bit. 

The two most common package management systems are [apt (for linux/ubuntu)](https://help.ubuntu.com/community/AptGet/Howto) and [brew (for MacOSX)](https://brew.sh/). 

[Here's a short tutorial on git](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners). 

This tutorial should also teach you a little bit about 'static website builders', although you wont be doing anything sophisticated. 

## Local deploy 

1. Install Git, Hugo and Go (e.g. `apt install git hugo go` or `brew install git hugo go`). 
2. Pull website & launch:
```sh
git clone https://github.com/tanous/website.git
cd website
hugo server -D
```
3. Vist at http://localhost:1313/

## Adding yourself to the "People" page

Once you have the website deployed on your local machine, you can add yourself to the website.  

1. Migrate to the list of authors, and copy my folder as a template:
```sh
cd content/authors
cp -r anous <YourLastName>
```

2. Edit your bio by deleting my info and adding yours (the comments in my bio should be sufficient to clarify what goes where, but feel free to ask):
```sh
cd <YourLastName>
nano _index.md
```

3. Replace my `avatar.jpg` with a picture of yourself (but keep the filename the same). 

4. As long as the hugo server on your local machine continues to run, your edits will render in real time. Check out your page!

5. If all looks good, commit your changes, and push to github: 
```sh
git add *     # adds all changes that you made to your commit (do just "git add _index.md avatar.jpg" if you edited other files)
git commit -m "Adding <YourLastName>"
git push
```
There you go! You'll find your new version of the website on github instantly, and www.tarek-ano.us will update shortly thereafter. 

## Troubleshooting

1. Hugo caches the theme and certain intermediate files/modules, which can sometimes cause bugs to persist even after you remove them. Purging the cache will often fix these issues, which is accomplished by running the command: 
```sh
hugo mod clean
```
If, for whatever reason, that does not fix things note that I wrote the page with Hugo [v0.116.1 extended](https://github.com/gohugoio/hugo/releases/tag/v0.116.1). You can install older versions of Hugo e.g. by following the instructions listed in [this tutorial](https://www.gigigatgat.ca/en/posts/install-specific-hugo-version/)

## Adding a publication

To add a publication, use the `academic` CLI tool to create a new publication folder in the content/publications/ directory with 
```sh
academic import --bibtex data/<NewPublication>.bib
```
Don't forget to change the `draft` line item from `true` to `false` so that the new publication appears on the live website. 

 See https://wowchemy.com/docs/content/publications/ for more information.
