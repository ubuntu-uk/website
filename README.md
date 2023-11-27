## Ubuntu-UK LoCo Website repo

This repo contains the content for the Ubuntu UK Local Community Team website. The goal is to have the content here hosted at https://ubuntu-uk.org/. Currently the site is at https://ubuntu-uk.github.io/website/

## Get involved

We welcome contributions to improve the site!

The site is built using [Hugo](https://gohugo.io/) and deployed with a [GitHub action](https://github.com/features/actions).

### Install Hugo

[Install](https://gohugo.io/installation/) Hugo using their documentation for [Linux](https://gohugo.io/installation/linux/), [Windows](https://gohugo.io/installation/windows/), [macOS](https://gohugo.io/installation/macos/), or [BSD](https://gohugo.io/installation/bsd/).

### Get the code

Fork the repo, then clone it to your local workstation.

### Prototype

Start hugo in the directory you cloned to.

`hugo serve`

You'll see output similar to the following:

```
Watching for changes in /home/alan/Source/ubuntu-uk/website/{archetypes,assets,content,data,i18n,layouts,static,themes}
Watching for config changes in /home/alan/Source/ubuntu-uk/website/hugo.toml, /home/alan/Source/ubuntu-uk/website/themes/ananke/config.yaml
Start building sites … 
hugo v0.119.0-b84644c008e0dc2c4b67bd69cccf87a41a03937e linux/amd64 BuildDate=2023-09-24T15:20:17Z VendorInfo=gohugoio


                   | EN  
-------------------+-----
  Pages            | 10  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     |  2  
  Processed images |  0  
  Aliases          |  1  
  Sitemaps         |  1  
  Cleaned          |  0  

Built in 17 ms
Environment: "development"
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1) 
Press Ctrl+C to stop
```

### Visit site

Visit [localhost:1313](https://localhost:1313) to view the site

Hugo will update the site whenever files are changed, typically there's no need to refresh the page.

The Hugo documentation can be found at [gohugo.io/documentation/](https://gohugo.io/documentation/).

### Submit PR

Push your changes to a pull request, where we can review and discuss the changes, prior to merging. 

## Code of Conduct

Please respect the [Ubuntu Code of Conduct](https://ubuntu.com/community/ethos/code-of-conduct) when interacting with others in this repo. 