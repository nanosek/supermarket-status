# Is is busy? 
This is a prototype of an OpenStreetmap Mashup to show the current "waiting queue" length

### How does it work?

Almost everything runs in your browser via JavaScript, there is no dedicated server that belongs to this mashup.
Three external servers are being used (their public APIs are being queried by your browser):
- OpenStreetMap to get the map tiles (the map background)
- wss://mqtt.eclipse.org to fetch the reported status that others have published
- overpass-api.de/api/interpreter to get the actual data where the elements that you are interested are located
 

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nanosek/supermarket-status/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
