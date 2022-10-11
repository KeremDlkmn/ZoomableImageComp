# Zoomable Image Composable
Allows to create zoomable image composable function.

## How To Use
Allows you to create zoomable images. Jetpack does not come with a ***zoom*** feature in the image composable function in compose. Using ZoomableImageComp you have an image composable function that you can zoom in.

## What Are The Features

- **bitmap:** Graphics object that represents a 2 dimensional array of pixel information represented as ARGB values (***required***)
- **modifier:** Structural property of composable function
- **backgroundColor:** Background color of ZoomableImageComp
- **imageAlign:** Alignment of photo
- **shape:** Shape of the image
- **maxScale:** Maximum photo scale value
- **minScale:** Minimum photo scale value
- **contentScale:** Photo content scale value
- **isRotation:** Rotation state of the photo
- **isZoomable:** Zoomable state of the photo
- **scrollState:** Scroll state of the photo

## Simple Example
It will be enough to give a bitmap type image. Other features have values assigned by default.

```kotlin
ZoomableImageComp(
  bitmap = image_item
)
```

> **image_item:** It must be of type ImageBitmap.
