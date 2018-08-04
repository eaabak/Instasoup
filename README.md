[![Build Status](https://travis-ci.org/Alan4747/Instasoup.png?branch=master)](https://travis-ci.org/Alan4747/Instasoup)

# Instasoup
Instasoup is an API-free tool to fetch image/video data from Instagram. To effectively use this library, you will need [JSoup](https://jsoup.org/) library installed to the project.

## Example
To fetch an image from the given Instagram link:

```Java
import InstagramDownloader.FromInstagram;

// <image_id> is the image id of the given link, 1fKFsokdgEj for example.
String url = "https://www.instagram.com/p/<image_id>";

// Specify the URL on parameter 1, and filename on parameter 2.
FromInstagram.downloadImage(url, "filename.jpg");
```

Also, to fetch a video from the given Instagram link:

```Java
import InstagramDownloader.FromInstagram;

// <video_id> is the video id of the given link, fj39jqt9v3e for example.
String url = "https://www.instagram.com/p/<video_id>";

// Specify the URL on parameter 1, and filename on parameter 2.
FromInstagram.downloadVideo(url, "filename.mp4");
```

## Documentation
[Click here](/doc/)

## Support
If you have any questions or suggestions, please get in touch via [my mail](mailto:alan47m@gmail.com).
