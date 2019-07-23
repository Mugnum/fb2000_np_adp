# fb2000_np_adp

A line length adaptive script for Skipy Rich's Now Playing Simple plugin in Foobar2000.

This script displays artist-title and album-date in separate lines, ordering them by length.

Too short album name is added to artist-title line in brackets; too long album name gets truncated.

## Preview
![alt text](https://raw.githubusercontent.com/syrtsevser/fb2000_np_adp/master/Presentation/demonstration.png)

<sub>Was something I wanted to have long ago but managed to get working in under 20 minutes. Feel free to use as a reference in your endeavours.</sub>

## Requirements
1. [Foobar2000](https://www.foobar2000.org)
2. [Now Playing Simple plugin](http://skipyrich.com/wiki/Foobar2000:Now_Playing_Simple)

## Usage
After installing Now Playing Simple, go in **Library->Configure** and nagivate to **Tools->Now Playing Simple**.
[![alt text](https://raw.githubusercontent.com/syrtsevser/fb2000_np_adp/master/Presentation/installation_small.png)](https://raw.githubusercontent.com/syrtsevser/fb2000_np_adp/master/Presentation/installation.png)

Check **Save to file** and choose **output file** path. Paste [this text](https://github.com/syrtsevser/fb2000_np_adp/blob/master/fb2000_np_adp.txt) in **Formatting string** textbox.

In OBS Studio sources section, add **Text (GDI+)**, check **Read from file** and navigate to plugin's output file.
