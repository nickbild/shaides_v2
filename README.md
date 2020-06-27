# ShAIdes 2.0

UpgrAIde your ShAIdes!

ShAIdes 2.0 is a much smaller, more practical, redesign of the [original ShAIdes](https://github.com/nickbild/shaides).  Effect change in your surroundings by wearing these AI-enabled glasses. ShAIdes is a transparent UI for the real world.

<p align="center">
<img src="https://raw.githubusercontent.com/nickbild/shaides_v2/master/media/teaser.gif">
</p>

My AI is *still* so bright, I gotta wear shades.

## How It Works

ShAIdes was initially designed as an all-in-one device; a camera attached to the glasses was hardwired to an NVIDIA Jetson Nano that the user hung around their neck in a small box.  ShAIdes 2.0 greatly reduces the size and power requirements of the device by mounting a tiny ESP32-CAM to a pair of glasses.

The Jetson Nano has been replaced by a Jetson Xavier NX, and rather than carrying it around, it has been repurposed as an edge AI device.  The ESP32-CAM remotely communicates with the NX over WiFi.  As such, the Jetson can now be located anywhere in the same building (or further, depending on network configuration) as the device, and no longer needs to draw on the device battery power.

The fundamentals of the project (model creation, training, and inference) are the same as the [original ShAIdes](https://github.com/nickbild/shaides) and can be referenced for anyone needing further details.

## Media

YouTube demonstration:  
[ShAIdes 2.0 video](https://www.youtube.com/watch?v=j2iDt1-StdU)

The ShAIdes:

![front](https://raw.githubusercontent.com/nickbild/shaides_v2/master/media/glasses_front_sm.jpg)

![side](https://raw.githubusercontent.com/nickbild/shaides_v2/master/media/glasses_side_sm.jpg)

![inside](https://raw.githubusercontent.com/nickbild/shaides_v2/master/media/glasses_inside_sm.jpg)

The brains of the operation, an NVIDIA Jetson Xavier NX:

![jetson_nx](https://raw.githubusercontent.com/nickbild/shaides_v2/master/media/jetson_nx_sm.jpg)

## Bill of Materials

- 1 x NVIDIA Jetson Xavier NX
- 1 x ESP32-CAM
- 1 x USB Battery Bank (500mAh or greater recommended)
- Miscellaneous wires
- Glasses/sunglasses

## About the Author

[Nick A. Bild, MS](https://nickbild79.firebaseapp.com/#!/)
