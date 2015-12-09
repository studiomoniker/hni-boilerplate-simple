# Simple boilerplate for HNI Web Covers

A simple starting point for developing web covers for hetnieuweinstituut.nl

Learn more about what a web cover is and the guidelines to follow: [Web Cover Guidelines](https://docs.google.com/document/d/11jerHdJNZshRjuYrI7uJ0bNghiRwImqJuansFCTWejs/)

### Download

To download the boilerplate click on `Download ZIP` or clone this git repository.

### Proxy images
You need to include three proxy images with the cover. The filenames of these images need to correspond with those in the `settings.ini` file. (For example when you decide to use a jpg instead of a gif)
- `proxy-agenda.png`: 1120px by 630px image to be shown at [hetnieuweinstituut.nl/agenda](hetnieuweinstituut.nl/agenda)
- `proxy-landscape.gif`: 768px by 520px image to be shown on small screens in landscape mode
- `proxy-portrait.gif`: 520px by 768px image to be shown on small screens in landscape mode

### Image Compression
- Photographic images: use jpeg compression 80% or less
- Graphical bitmap images: png-8 or gif compression
- If your cover is purely vector based, you should try making an SVG version.

### Testing
To test out how your cover will look on the homepage of the New Institute, host the cover directory on a local webserver and visit `http://your-local-webserver/iframe-test/`. Make sure the following things work:
- When you hover your cursor over the cover, it should change to a hand.
- Clicking on the cover should send you to a page that tells you your click was successful
- You should be able to use your trackpad or the scrollbutton on your mouse, while your cursor is on top of the cover
- On an iPad, you should be able to scroll down the homepage, when your touch starts on the cover

### Packaging
The cover should be delivered to the web editor of The New Institute as a zip file. To create the zip file on Mac:

1. select all the files in the cover directory (not the cover directory itself)
2. control + click on them
3. select 'compress x items' in the contextual menu
