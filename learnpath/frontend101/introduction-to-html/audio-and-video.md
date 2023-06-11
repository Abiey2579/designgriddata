# Audio and Video

In HTML, you can use the `<audio>` and `<video>` elements to embed audio and video content in your web pages, allowing you to provide a rich multimedia experience for your users. These elements support various formats and provide built-in controls for playback.

To embed an audio file:

```html
<audio controls>
  <source src="audio-file.mp3" type="audio/mpeg" />
  Your browser does not support the audio tag.
</audio>
```

To embed a video file:

```html
<video controls>
  <source src="video-file.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>
```

In these examples, the `src` attribute specifies the path to the audio or video file, and the `type` attribute defines the MIME type of the media file. The `controls` attribute adds playback controls to the audio or video player. If the browser doesn't support the audio or video tag, the fallback content within the `<audio>` or `<video>` element will be displayed.

### **Let's learn by doing**

---

**Let's Add Audio**

Copy any audio and paste it in the same folder as your `index.html`, in case you keep your `index.html` in desktop just paste the audio in desktop too. (The Idea is to keep the `index.html` and the audio in the same place)

I have an audio called `my-audio.mp3`

> **NOTE:** Avoid using space when naming the audio use **Hyphens** `-` or **Underscores** `_` or no space at all

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>My Audio</h1>
    <audio controls>
      <source src="my-audio.mp3" type="audio/mpeg" />
      Your browser does not support the audio tag.
    </audio>
  </body>
</html>
```

Right-click anywhere in code and select "Open in Browser"

You will see something like:

![Code Preview](https://raw.githubusercontent.com/Abiey2579/designgriddata/master/learnpath/assets/images/audio-video-code-preview.jpg)

**Let's Add Video**

Copy any video and paste it in the same folder as your `index.html`, in case you keep your `index.html` in desktop just paste the video in desktop too. (The Idea is to keep the `index.html` and the video in the same place)

I have an video called `my-video.mp3`

> **NOTE:** Avoid using space when naming the video use **Hyphens** `-` or **Underscores** `_` or no space at all

I have an video called `my-video.mp3`

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>My Video</h1>
    <video controls>
      <source src="my-video.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </body>
</html>
```

Right-click anywhere in code and select "Open in Browser"

You will see something like:

![Code Preview](https://raw.githubusercontent.com/Abiey2579/designgriddata/master/learnpath/assets/images/audio-video-code-preview-2.jpg)

### Code Hint

While you can use the above method, there is another method which seems more simpler:

**Simpler way of adding a video**

```html
<video src="my-video.mp4" controls></video>
```

**Simpler way of adding an audio**

```html
<audio src="my-audio.mp3" controls></audio>
```

Both coding practice are good, so choose wisely.

### Resource Recommendation

1. <a href="https://youtu.be/zE0ptSTAPmU" target="_blank">Insert Video and Audio into Website using HTML5 | HTML Tutorial for Beginners
   </a>
