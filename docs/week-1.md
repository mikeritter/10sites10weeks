# WEEK ONE

## OBJECTIVE: Build your portfolio website

_Note: how and what you build is up to you. Tailor this challenge to suit your needs._

The first website sets the tone for the rest of your challenges. Just kidding. I recommend beginning with a portfolio site because it is pretty much the standard. A typical portfolio site covers many of the fundamental components in a web project and provides a useful reference for future clients.

## KEY CONCEPTS

### COLLECTIONS

A portfolio is a __collection__ of projects. Collections are key to most web applications.

Examples of collections:

- Pages
- Articles
- Products
- Users
- Testimonials
- Albums
- Events

When you build a portfolio you practice fundamentals of working with collections:

- Looping
- Sorting
- Templating
- Object-orineted Programming
- Mapping

### TEMPLATES

Mentioned above, templates are reusable sections of code that contain placeholders for details from a collection. Consider the following:

```
---
Projects:
  - title: "My Portfolio"
    image: "/assets/projects/thumbnails/link-to-image.jpg"
    description: "A very descriptive description"
    url: "https://link-to-project"
  - title: "My Collections on Unsplash"
    image: "/assets/projects/thumbnails/link-to-this-image.jpg"
    description: "show off by talking about why you built the site andtechnologies you used"
    url: "https://link-to-this-project"
---
{ for project in Projects }
<section>
<h1><a href="{ project.url }">{ project.title }</a></h1>
<img src="{ project.image }">
<p>{ project.description }</p>
</section>
{ endfor }
```

The "Projects" collection contains two projects.

We _loop_ through the "Projects" collection. For every "project" in "Projects" template for a "project" describes what it will look like and what data is included.

### STYLE

A sense of style is important to good web design. Without it, websites look haphazard. When you follow some form of design your website stands out for good reasons and visitors feel better viewing it.
