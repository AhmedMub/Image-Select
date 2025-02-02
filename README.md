```
   ╭────────────────────╮                                                                  
   │     /\/      ╭──────────╮╭────┬───┬──╮╭──────╮╭─┬────╮╭──────╮                        
   │         \/\  │  ╭╮  ╭╮  ││           │├────  ││ ╭╮   ││  ──  │                        
   │  /\/         ╰──╯│  │╰──╯│   ╭╮  ╭╮  ││ ╭╮   ││ ╰╯   ││      │                        
   │                  │  │    │   ││  ││  ││ ╰╯   │├───   ││  ────┤                        
   │        Λ         │  │    ╰───╯╰──╯╰──╯╰───┴──╯╰──────╯╰──────╯                        
   │       ╱ ╲   /░░\ │ ╭──────╮╭──────╮╭───╮╭──────╮╭──────╮ ╭───╮                         
   │      ╱   ╲  \░░/ │ │  ────┤│  ──  ││   ││  ──  ││   ╭──╯╭╯   ╰╮                        
   │     ╱ \/\/╲      │ │      ││      ││   ││      ││   ╰──╮╰╮   ╭╯                        
   │    ╱       ╲ ╭──╮│ ├────  ││  ────┤│   ││  ────┤│      │ │ ──┤                         
   │   ╱         ╲│  ╰╯ ╰──────╯╰──────╯╰───╯╰──────╯╰──────╯ ╰───╯  v2.0                       
   │  ╱           ╰──────────╯
   ╰────────────────────╯                                                                  
```

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/websemantics/Image-Select/master/LICENSE) [![GitHub forks](https://img.shields.io/github/forks/websemantics/Image-Select.svg)](https://github.com/websemantics/Image-Select/network) [![GitHub stars](https://img.shields.io/github/stars/websemantics/Image-Select.svg)](https://github.com/websemantics/Image-Select/stargazers)
[![Percentage of issues still open](http://isitmaintained.com/badge/open/websemantics/Image-Select.svg)](http://isitmaintained.com/project/websemantics/Image-Select "Percentage of issues still open")

> We designed this plugin extension as a humanized UI element for social networking sites that need to facilitate relations between people. Research shows that people are extremely sensitive to photos of others, so we needed to revamp the traditional UI elements to make them more intuitive and human.

## NOTE

websemantics/ImageSelect Got Abandoned By Its Owner, This Forked Working Fine As Missing Files Has Been Added.

## New Style
> Fresh flat styles and new logo & web design for better user experience

<img src="http://websemantics.github.io/Image-Select/img/sample-w540@2x.png" style="width:540px" alt="Image Select"/>

#### Try [Live](http://websemantics.github.io/Image-Select/) or [Examples](http://websemantics.github.io/Image-Select/example.html)


## Use Scenarios

You can use these plugin extensions for modelling multiple (one-to-many) or single (one-to-one) relations between people.

We couldn't find any scripts that had this full functionality, so we developed it ourselves on top of Chosen. Hope you find it helpful, and get back if you have any feedback/improvements.


## Installation

- Clone locally,

```bash
git clone https://github.com/websemantics/Image-Select
```

- Install dependencies,

```bash
bower i
```

- Browse to `index.html` or `example.html`


### Bower Package

Install in your project,

```
bower install image-select --save
```

To get information about available packages

```bash
bower info image-select
```

## Usage

First Add below styles before `</head>` tag and required scripts before `</body>` tag.

```html
<link rel="stylesheet" href="src/css/semantic.min.css">
<link rel="stylesheet" href="src/css/codemirror.css">
<link rel="stylesheet" href="src/css/mdn-like.css">
<link rel="stylesheet" href="src/css/chosen.css">
<link rel="stylesheet" href="src/css/ImageSelect.css">
<link rel="stylesheet" href="src/css/Flat.css">

.................

<script src="src/js/jquery.min.js"></script>
<script src="src/js/chosen.jquery.js"></script>
<script src="src/js/ImageSelect.jquery.js"></script>
<script src="src/js/codemirror.js"></script>
<script src="src/js/xml.js"></script>
<script src="src/js/javascript.js"></script>
<script src="src/js/shell.js"></script>
<script src="src/js/tmlmixed.js"></script>
<script type="text/javascript" src="https://cdn.rawgit.com/websemantics/bragit/0.1.2/bragit.js"></script>
```

Then you need to add a `data-img-src` attribute to your `<option>` tag.

```html
<select class="my-select">
  <option data-img-src="img/adnan.png">Adnan Sagar</option>
  <option data-img-src="img/rena.png">Rena Cugelman</option>
  <option data-img-src="img/tavis.png">Tavis Lochhead</option>
  <option data-img-src="img/brian.png" selected="selected">Brain Cugelman</option>
</select>
```

Then call Chosen as you would with the options you need.

```javascript
$(".my-select").chosen();
```


## Support

Need help or have a question? post a questions at [StackOverflow](https://stackoverflow.com/questions/tagged/image-select)

*Please don't use the issue trackers for support/questions.*


## Contributions

We are more than happy to accept external contributions to the project in the form of feedback, bug reports and even better - pull requests :)


# Used by

[PyroCMS Social Field Type](https://github.com/websemantics/social-field_type)

![demo](https://raw.githubusercontent.com/websemantics/Image-Select/master/img/social_field_type.gif)


## Open Source
Chosen, http://github.com/harvesthq/chosen
Bragit, http://websemantics.github.io/bragit


## Copyright and license

[MIT license](http://opensource.org/licenses/mit-license.php)
Copyright (c) Web Semantics, Inc.
