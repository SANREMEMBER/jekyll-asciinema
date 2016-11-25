Jekyll Asciinema - The lazy way to embed Asciinema on Jekyll 
==============

A plugin for Jekyll to embed [Asciinema](https://asciinema.org), you can choose to embed Aciinema player or Asciinema image link on Jekyll.

> Based on [Easy Youtube Embed for Jekyll](https://github.com/pibby/jekyll-youtube) by [Katie Harron](https://pibby.com/)

## Demo
[Jekyll Arsciinema Plugin](https://sanremember.com/2016-11-25-jekyll-asciinema-care-cepat-sematkan-asciinema-di-jekyll/)

## Installation Instructions
Download the file `asciinema.rb` and place it in your `_plugins` folder of your Jekyll installation.

## Usage Instructions
In your Markdown post, simply include the following command:

+ `{% asciinema_play ASCIINEMA_ID %}`
+ `{% asciinema_img ASCIINEMA_ID %}`

Asciinema Player example, `{% asciinema_play 92383 %}` will render as:  
```html
<center>
	<script type="text/javascript" src="https://asciinema.org/a/92383.js" id="asciicast-92383" async></script>
</center>
```

Asciinema Image Link example, `{% asciinema_img 48201 %}` will render as:

```html
<a href="https://asciinema.org/a/48201" target="_blank"><img src="https://asciinema.org/a/48201.png"/></a>
```
