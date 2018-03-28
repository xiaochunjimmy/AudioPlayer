# AudioPlayer
A jQuery audio player plugin that is responsive and touch-friendly. The UI is css-only, no images used.  

This repo is a redesign of <a title="Osvaldas Valutis' work" href="https://tympanus.net/codrops/2012/12/04/responsive-touch-friendly-audio-player/">Osvaldas Valutis' work</a>  

![AudioPlayer](http://p5ijh16yw.bkt.clouddn.com/audioplayer.png)

I reesigned the UI to fit morden flat design, you can modify the css(such as color,height,with...) to fit your own website style.  

## How it works
The plugin replaces targeted `<audio>` elements with some HTML and JavaScript events attached to it.  
You can use it to your website or blog, Makrdown supported.  

## How to use it
Nothing special, just the typical usage of the `<audio>` tag.  
`<audio src="your-audio.mp3" preload="auto" controls></audio>`  
`<audio src="audio.wav" preload="auto" controls autoplay loop></audio>` autoplay&loop  

## How to install it
Place the  
`<link rel="stylesheet" href="css/audioplayer.css" />`  
`<script src="jquery.js"></script>`  
`<script src="audioplayer.js"></script>`   
into your header or footer.  

Place  
`<script>$( function() { $( 'audio' ).audioPlayer(); } );</script>`  
into your footer.  

call `<audio>` tag when you need attach a audio to your web page.  
`<audio src="audio.wav" preload="auto" controls></audio>`  


<a title="License" href="https://creativecommons.org/licenses/by-nc-sa/3.0/">License</a>  






