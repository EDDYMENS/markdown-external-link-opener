## Why Markdown External Link Opener?
There is no accepted Markdown standard or specification for setting up links to open up in a new tab, forcing different platforms to come up with their own implementations. 

Your next best bet is to use the HTML anchor tag ie: `<a href="#">Open in new tab</a>`

The goal of this small script is to allow you use the standard `[]()` syntax for your links and still enable your users to open them in a new tab.

## How does it work?

In other to use the external link opener you will have to append your URL to the end of `external.ink?to=` eg: [external.ink?to=yourlink.com](https://external.ink?to=yourlink.com), this will redirect the user to the link opener page whenever they click it and from there your provided link will open up in a new tab.

![markdown external link opener demo](https://user-images.githubusercontent.com/8077713/168576147-e4148ecf-7bd7-48b3-9986-a62a06ee8332.gif)
 

