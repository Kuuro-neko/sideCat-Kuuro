# sideCat-Kuuro

Based on [dule23's Rainmeter skin](https://www.deviantart.com/dule23/art/Catppuccin-Rainmeter-skin-914252677/) (which also has a top bar for unix systems, go check it, it looks cool).

Made these changes for myself, but made it public because why not.

It is not intended for easy setup, specially if you never used Rainmeter but i wrote something to help setup this.

## Preview

![Screenshot of my desktop](https://i.imgur.com/72w89yi.png)

## Basic installation

In case you want to try it and never have used Rainmeter before :

- Install [Rainmeter](https://www.rainmeter.net/)

- Clone this repo in Documents/Rainmeter/Skins

- From Rainmeter activate all the skin elements

- Drag the elements to the place of your choice (RMB > Parameters > Stick to edge to disable the sticking thing)

To customize the location, metrics and language edit @Resources/styles.inc<br>
More help about this in @Resources/WeatherData/MeasureNamesReference.txt

If you liked how I positioned the elements, you can copy Rainmeter.ini content into the rainmeter parameters (On rainmeter > Edit parameters, paste it here, this is the place where the positions are stored)

There are a lot of things you can easily change, just dig in the files !

## Temperature meter

This one requires a little more effort to setup since you need to use HWiNFO to get the values. After doing the basic install follow these steps :

- Go to the [official rainmeter's HWinfo guide](https://docs.rainmeter.net/tips/hwinfo/) and follow the steps starting at installing HWiNFO until you create your first gadget

- Create a gadget for your CPU and GPU temperature and remember their ID<br>
  If you forgot their ID, use the following command on a cmd to get them faster :
  ```
  reg query HKEY_CURRENT_USER\SOFTWARE\HWiNFO64\VSB
  ```

- Replace them in Temperature/sideCat_temperature.ini in the right meters (use RAW value for temperatures)

- Change the CPU and GPU name as you wish in @Resources/styles.inc

## Credits

Original rainmeter skin : [sideCat from dule23](https://www.deviantart.com/dule23/art/Catppuccin-Rainmeter-skin-914252677/)

[Image i am using as wallpaper from Namocchi Art](https://www.artstation.com/artwork/4XRwzY/)
