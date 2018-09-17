# fb2000_np_adp

A line length adaptive script for Now Playing plugin in Foobar2000.

The plugin exports metadata information in a text file, which you can use for text capture in OBS Studio.

This script displays artist-title and album-date in separate lines, ordering them by length.
Too short album name (under 6 chars) is added to artist-title line in brackets. Too long album name gets truncated.

## Preview
![alt text](https://raw.githubusercontent.com/syrtsevser/fb2000_np_adp/master/now_playing_demonstration.png)

<sub><sup>Was something I wanted to do long ago but managed to get working in under 20 minutes. You may use as a reference in your endeavours.</sub></sup>

## Requirements
1. [Foobar2000](https://www.foobar2000.org/)
2. [Now Playing Simple plugin](http://skipyrich.com/wiki/Foobar2000:Now_Playing_Simple)

## Usage
After installing Now Playing Simple, go in **Library->Configure** and nagivate to **Tools->Now Playing Simple**.
[![alt text](https://raw.githubusercontent.com/syrtsevser/fb2000_np_adp/master/installation_small.png)](https://raw.githubusercontent.com/syrtsevser/fb2000_np_adp/master/installation.png)

Check **Save to file** and choose **output file** path. Paste [this text](https://github.com/syrtsevser/fb2000_np_adp/blob/master/fb2000_np_adp.txt) in **Formatting string** textbox.

In OBS Studio sources section, add **Text (GDI+)**, check **Read from file** and navigate to plugin's output file.
