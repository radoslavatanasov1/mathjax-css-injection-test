<<<<<<< HEAD
# MathJax CSS Injection Test

This repository demonstrates a potential CSS injection vulnerability using SVGs.

## Exploit Demonstration

The SVG file contains embedded CSS that attempts to manipulate the rendering environment:

### Direct SVG Embed

![Injected SVG](https://raw.githubusercontent.com/radoslavatanasov1/mathjax-css-injection-test/main/injected.svg)

### Link to the SVG

[View Injected SVG](https://raw.githubusercontent.com/radoslavatanasov1/mathjax-css-injection-test/main/injected.svg)

## Testing HTML Page

Open the following HTML page in a browser to see the effect of the SVG:

[index.html](https://raw.githubusercontent.com/radoslavatanasov1/mathjax-css-injection-test/main/index.html)
=======
<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="100%">
    <style>
        <![CDATA[
            body {
                background: url('https://via.placeholder.com/800x600/FF0000/FFFFFF?text=Injected+SVG');
            }
        ]]>
    </style>
    <text x="10" y="40" font-size="35">Injected SVG Content</text>
</svg>



![Injected SVG](https://raw.githubusercontent.com/radoslavatanasov1/mathjax-css-injection-test/main/injected.svg)
>>>>>>> 7586d970a8404cff9c6ab82588a45796c163c27e
