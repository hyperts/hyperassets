# hyperassets
Assets and json references for hyper software

### loadingquotes.json | Phrases
Array of phrases used during load & waiting time for any hyper software.
```json
["That's one phrase!", "Here's another!"]
```

### loadingartwork.json | Images
Array of artwork objects, provides custom artworks to hyperbar loading window, similar to Photoshop and other adobe products.
```json
  {
    "author": "Author of the artwork",
    "name": "Name of this artwork",
    "link": "A link crediting this creator",
    "image": "URL for this image (can be hosted in the repository as well)"
  }
```

### communityrepository.json | Hyperbar approved widgets & Themes
Object with two arrays (one for themes, another for widgets).
The idea behind this repository file is to only allow curated widgets to be installed directly from hyper.
This list doesn't affect hyper ability to install unknown/thirdparty widgets

Format is the same as a github URL for the widget repository.

Anyone can contribute to this list as well
```json
  {"themes":[
    {"user": "GitHub author username", "package": "Repository name"} 
  ],
  "widgets":[
    {"user": "GitHub author username", "package": "Repository name"} 
  ]}
```
