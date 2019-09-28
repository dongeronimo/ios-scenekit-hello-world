# Hello World SceneKit
In this project I created my first scenekit app, displaying a scene and picking which component i touch. The color of the touched component changes randomly.
## Learned about:
### Creating sceneKit projects in XCode
To create a sceneKit capable project I had to create a new project in XCode, selecting SceneKit Project. I don't know, at this moment, it it is possible to add sceneKit later to an existing project.
### Creating a Scene in XCode
XCode has a sceneKit scene editor: a simple 3d editor to create things in a scene. No complex manipulations, only spatial placements, light and camera position and materials.
### Loading a scene into SCNView
The SCNView is the view responsible to render the scene. You load a scene from the assets and pass it to the SCNView. In my code this is written in the func showMyFirstScene().
### Creating animations
When I tap an object I create a SCNTransaction. A transaction takes some time (animationDuration) and interpolates some property to another value during this time. At least that's how I understood it.
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dongeronimo/ios-scenekit-hello-world/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
