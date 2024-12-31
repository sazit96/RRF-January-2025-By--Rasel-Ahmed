# RRF-January-2025-By-Rasel-Ahmed

This repository contains the code and notes for the "RRF-January-2025-By-Rasel-Ahmed" YouTube course. The course is taught by Rasel Ahmed and provides foundational knowledge in web development. Below are the details and important notes from the second class.

## Class 02 Link

[Watch the course on YouTube](https://youtu.be/1PsWxUZNNzE)

## Class 02: Adding Links, Images, and Embedding Videos

### Overview

- **File Names:** `class2.html`, `about.html`
- **Topics Covered:**
  1. Adding links using the `<a>` tag
  2. Embedding images using the `<img>` tag
  3. Embedding videos using the `<iframe>` tag

### Key Points

#### Links

### Horizontal Line

- **Horizontal Rule (`<hr>`) Tag**:  
  The `<hr>` tag is used to create a thematic break or horizontal line. It's commonly used to separate content visually.  
  Example:
  ```html
  <hr />
  ```

---

### Formatting Text

- **Strong (`<strong>`) Tag**:  
  Adds importance to the text, which is often rendered in bold.  
  Example:

  ```html
  <strong>Lorem ipsum dolor sit amet.</strong>
  ```

- **Bold (`<b>`) Tag**:  
  Displays text in bold without adding semantic importance.  
  Example:

  ```html
  <b>Lorem ipsum dolor sit amet.</b>
  ```

- **Emphasized (`<em>`) Tag**:  
  Emphasizes text, which is typically rendered in italics.  
  Example:
  ```html
  <em>Lorem ipsum dolor sit amet consectetur adipisicing elit.</em>
  ```
- **Anchor (`<a>`) Tag**:  
  The `<a>` tag is used to create hyperlinks. You can use it to link to external websites or internal pages.  
  Example:

  ```html
  <a href="https://github.com/sazit96">My Github</a>
  ```

- **Internal Linking**:  
  Use the `<a>` tag to navigate between different pages of the project by referencing the file name in the `href` attribute.  
  Example:
  ```html
  <a href="about.html">This is about page</a>
  ```

---

#### Images

- **Image (`<img>`) Tag**:  
  The `<img>` tag is used to display images on a webpage. The `src` attribute specifies the image's URL, and the `alt` attribute provides alternate text if the image can't be loaded.  
  Example:

  ```html
  <img
    height="100"
    width="100"
    src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/800px-HTML5_logo_and_wordmark.svg.png"
    alt="this is html image"
  />
  ```

- **Attributes**:
  - `height` and `width`: Control the image size in pixels.
  - `src`: Specifies the source URL of the image.
  - `alt`: Provides descriptive text for the image, which is useful for accessibility.

---

#### Embedding Videos

- **Iframe (`<iframe>`) Tag**:  
  The `<iframe>` tag is used to embed content such as videos from external sources. The `src` attribute specifies the video URL.  
  Example:

  ```html
  <iframe
    width="1000"
    height="400"
    src="https://www.youtube.com/embed/1PsWxUZNNzE"
    title="RRF January 2025 Batch Class 2"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen
  ></iframe>
  ```

- **Attributes**:
  - `width` and `height`: Define the size of the embedded content.
  - `src`: Specifies the source URL of the embedded video.
  - `title`: Provides a title for the iframe, improving accessibility.
  - `frameborder`: Sets the border thickness around the iframe (commonly `0` for no border).
  - `allowfullscreen`: Enables full-screen playback for the embedded video.
  - `allow`: Specifies permissions like autoplay, clipboard-write, etc.

---

Happy learning and coding! 🚀
