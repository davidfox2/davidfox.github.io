# Title

## Heading 2 

### Heading 3
"website made and maintained by David"

Using Jekyll: https://help.github.com/en/articles/using-jekyll-as-a-static-site-generator-with-github-pages

about jekyll and iframes: https://stackoverflow.com/questions/31660273/markdown-jekyll-insert-an-iframe-that-fills-the-container

### Testing an iframe from Tableau with a permalink

"below is a iframe using the instructions given. "

<div class="video-container">
    <iframe src="http://www.youtube.com/embed/4aQwT3n2c1Q" height="315" width="560" allowfullscreen="" frameborder="0">
    </iframe>
</div>

.video-container {
    position: relative;
    padding-bottom: 56.25%;
    padding-top: 35px;
    height: 0;
    overflow: hidden;
}

.video-container iframe {
    position: absolute;
    top:0;
    left: 0;
    width: 100%;
    height: 100%;
}
