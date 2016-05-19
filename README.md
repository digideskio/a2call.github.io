# a2call.github.io
Web front for a2call.com hosted at the amazing github

# This repository contains dev files required to set up a2call.com webfront.
##a2call is an open source voice technology services provider in the emerging markets of Asia and Africa

### Requirements

* Ruby
* Jekyll

If both of these dependencies are installed you can just run `jekyll build` to compile the lastest version of the website into the `_site` folder.


## How member data works

Each member is listed in `_data/members.yml`, this section will explain what you need to fill in and how to get it working in no time. Follow through:

```
- username: "username" // your username
  title: "title" // your profession, tagline, whatever fits your needs
  description: "description" // a short description about you
  skills: // list up some skills of yours
    - "just"
    - "a"
    - "list"
  website: "http://example.com" //your website (with protocol please)
  github: "username" // your Github username
  twitter: "username" // your Twitter username
  avatar: "image.png" // your profile picture (place in /assets/img/members/ )
  background: "http://example.com/example.png" // (panel background image, please add URL here, upload to imgur or somewhere else)
```


