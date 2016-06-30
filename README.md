# Video Login Screen Fuse Example
Example project to accompany the "[Video Login Screen Example](https://youtu.be/zfiz-yI4VWY)" Fuse tutorial video. This is a very basic example made to show how easy it is to build a classic login screen with a video background. All relevant code is in the `MainView.ux` file.

## Setup
_NOTE: this is covered in the tutorial video._

You'll need to supply your own video file to use with this example. Insert the file path to your video file on line 36 in `MainView.ux` where it says `YOUR_VIDEO_HERE`:

```xml
		<Video Layer="Background" File="YOUR_VIDEO_HERE" ...
```

Once that's done, you're all set!

## Fuse version
This example was produced with Fuse (beta) v0.9.2. It was tested on Mac OS X 10.10.5. It was later updated to be compatible with Fuse 0.20 and onwards.

## Branches
The "finished product" is on the `master` branch, and the template I started with in the video is on the `starting-template` branch.

## License
This code is licensed under the BSD2 license (see LICENSE).

The provided video file (`assets/nature.mp4`) is a modified version of [Graham Uhelski](https://vimeo.com/mankindfilms)'s ["The Valley"](http://mazwai.com/#/videos/220). It is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
