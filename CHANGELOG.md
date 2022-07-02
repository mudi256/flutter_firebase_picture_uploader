## 1.3.2 - 3/July/2022
* Update image_cropper package, use ImageCropper().cropImage() instead of static ImageCropper.cropImage()
## 1.3.0
  * Refactor: update dependencies to most recent ones
  * Refactor: introduce null-sound-safety

## 1.2.3
  * Refactor: update dependencies to most recent ones

## 1.2.2
  * Refactor: update dependencies to most recent ones

## 1.2.1
  * Refactor: update dependencies to most recent ones

## 1.2.0
  * Feature: add option to disable cropping
  * Feature: add option to select an other firebase storage bucket for plugin
  * Refactor: add compatibility to old versions again
  * Refactor: replace const parameters where it makes sense
  * Refactor: update dependencies to most recent ones
  
## 1.1.2
  * Update dependencies to most recent ones

## 1.1.1
  * Feature: Close icon color (and background) can be configured

## 1.1.0
  * Feature: Add option to select image from gallery and/or camera
  * Feature: Add customization options (width and height) for PictureUploadButton
  * Fix: Fixed an issue with minImageCount / maxImageCount that minImageCount = 0 wasn't possible
  * Fix: Decreased image dependecy to ^2.1.4

## 1.0.0+6
  * Fixed a bug in image url caching which caused to return null if not cached instead of receiving the image url from firebase.

## 1.0.0+5
  * Fixed a bug that caused customUploadFunction not to work because of a forgotten await
  * Made parsing of file name more flexible.
  * The filename mist be like custom1_..._custom_x_id_customy.(jpg|png|...) now

## 1.0.0+4
  * Add reference to complete tutorial
  * Add documentation to code

## 1.0.0+3
  * Updated homepage to github reference.

## 1.0.0+2
  * Updated homepage to github reference.

## 1.0.0+1
  * Initial release.
