# Reading 11

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content){:target="_blank"}

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

    In the early 2000s, video and audio on websites usually needed third-party plugins such as Adobe Flash Player, QuickTime, or Windows Media Player.

2. Describe the use of the `src` and `controls` attributes in the `<video>` element.

    src attribute in a <video> element specifies the path or URL of the video file the browser should load, while the controls attribute tells the browser to display built-in playback controls such as play, pause, volume, and a timeline so the user can interact with the video.

3. Why is it important to have **fallback content** inside the `<video>` element?

    In case the video fails to load, then you have some kind of content to "fallback" on.

4. Write a very short story where `<audio>` and `<video>` are characters.

    There once was a knight named Audio who would discombobulate his enemies with horrid screaching sounds.
    There was also another knight named Video who terrified his enemies with horrible imagry of their imenent doom.

[A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/){:target="_blank"}

1. How does Grid layout differ from Flex?

    Flex is meant for 1-dimensional positioning, grid is for 2-dimensional positioning.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

    Grid container is the container for the grid, what "becomes" the grid with display.
    Grid item is whatever is inside the grid like the "grid cell"
    Grid line is what separates the grid items, it's like a border but invisible/visible depending on how you want it to look.


[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images){:target="_blank"}

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

    For accessiblity and in case someone is using you're website on a mobile device. 

1. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.

    The `<img>` tag is used when you want to add an image to you're HTML.
    The `srcset` attribute lets you give multiple versions of the same image and make the browser chose which one is best based on the user device.
    The `sizes` attribute tells the browser how wide the image will appear in the page layout, so it can choose the most appropriate image from the options provided in srcset.

1. How is `srcset` more helpful for responsive images than CSS or JavaScript?

    js can swap imgs but it reloads the page after rendering.