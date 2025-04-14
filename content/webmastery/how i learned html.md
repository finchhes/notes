---
draft: "true"
---
# to preface:
i learned html in 2022 as a coping mechanism. i wasn't happy with myself and my online image, so i scrapped it all and started a neocities page. 

when you start from scratch it seems easy to just copy people that you really like, take their code and maybe switch it around a little. i did this and i heavily regret it, not only does it mean nothing is your own but it means you skip all of the foundational skills that every webdev should learn. i learned flexbox before i learned very basic html and css tags. 

**start simple and start from scratch. the point of this page is to give you insight into how i learned and how you can too, without taking other peoples code.**

# is this for you?
## why are you learning?
mildly stupid question but most of you are here to learn how to build and maintain your own personal site, most likely on the indie web (specifically neocities if you're coming from there.) that is a different skillset than building a professional website, and has less of a learning curve.

personally, i think you should learn how to make a professional looking website even if your goal is to just make some 2000s core geocities site that isnt made to be viewed by more than a classrooms worth of people.

that being said, this is detailing how i learned casual css, not professional web development.

## what are you interested in making?

if you're just trying to make a shitpost site your best bet is to wing it, pull up a learning source like [w3schools.com](https://www.w3schools.com/) and just start. you dont need this if your goal is to build something that looks like this
![[geocities.png|300]] 
but youre welcome to keep reading regardless!

# humble beginnings
## formatting an html file
whenever you make a new html file itll start with the same... sections if you will.

heres an example of a typical (mostly empty) html file:

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>

</body>

</html>
```

this is extremely minimal, but it gets the job done. lets go over each section:

### DOCTYPE
`<!DOCTYPE html>` is simple, it tells the browser what version of html to expect. for html5, just `<!DOCTYPE html>` is used, but if you mess around with older html versions the tag will change.

this is not an html tag.

### html
`<html>`, or as we see here `<html lang="en">` is the html tag, meaning all html starts then. this is essentially the start of all the content on your page, and contains all other html elements.

`lang="en"` is used here to tell the browser what language the page is in, `en` here standing for english.

### head
`<head>` stores all metadata about the html document. this is not a header, though it can be confusing.

the `<head>` element usually has many different things in it, but here we only see `<meta>` used.

the following elements are able to be contained in a `<head>` tag.

`<title>`
`<style>`
`<base>`
`<link>`
`<meta>`
`<script>`
`<noscript>`

### meta
`<meta>` your metadata goes here. 
dont touch the parts in this example, you dont need to know what they do but without them youre kind of screwed. (they manage the character encoding and mobile responsiveness respectively)

`<meta>` is also used to manage your sites description and keywords and all that fun stuff.

`<meta name="description" content="this is my cool site or something">`

`<meta name="keywords" content="keyword, keyword">`

### body
finally something youll actually understand!
`<body>` is where all of the content that you want to actually be on your site will go! this is everything that gets loaded and that you can see  (with an asterisk at the end.)