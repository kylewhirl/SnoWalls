# SnoWalls ❄️
## Create custom dynamic wallpapers with weather effects and more!
Solarized dark             |  Solarized Ocean
:-------------------------:|:-------------------------:
![](https://...Dark.png)  |  ![](<img src="/main.GIF?raw=true">)
<img src="/main.GIF?raw=true">

#### Quick Links
* [Installation](#Installation)
* [Guide](#Guide)
* [Tutorial](#Tutorial)
* [Extensions](#Extensions)

## This is an all-in-one Dynamic Wallpaper Shortcut designed for iOS and iPadOS devices.

### This shortcut will allow you to:
* Create custom Dynamic Wallpapers from the photos on your phone
* Choose pre-installed SnoWalls ❄️ Presets
* Download Dynamic Wallpapers from [Dynamic Wallpaper Club](https://dynamicwallpaperclub.com)
* Upload an HEIC file and convert into a Dynamic Wallpaper using CloudConvert API
* Calculate Automation Times for you SnoWalls ❄️ setup
* Run Custom Shortcut Extensions with native support for [WeatherWalls](https://routinehub.co/shortcut/8236/) by u/apoch8000 ([Reddit](http://reddit.com/u/apoch8000)), [SunMoonWeather](https://github.com/thewaytozion/widgets) by @thewaytozion ([Twitter](https://twitter.com/thewaytozion)), and Maui Snorkel Report 🤿

## Installation
1. Install the [Setup Shortcut](https://www.icloud.com/shortcuts/647a65ebe32c450aaf6b732f43e21d78)
2. Run it!
- This will download the main SnoWalls ❄️ Shortcut and create necessary files in iCloud Drive
3. Run it again!
- This will run the main SnoWalls ❄️ Shortcut and begin the creation process

#### When creating Automations, set them to run the main SnoWalls ❄️ Shortcut (or whatever name you have given it). A tutorial can be found [here](#Tutorial)
#### If you ever want to change or configure your SnoWalls ❄️ setup, run the Setup Shortcut.

## Guide
### Create custom SnoWall ❄️
This action will prompt you to select images, either from your files app or photos app, to setup as a dynamic wallpaper. You must order these photos manually, starting from nightfall and ending at sunset.
### Choose from Presets
This action will prompt you to select from presets installed within the shortcut. 
### Download from Dynamic Wallpaper Club
You can download dynamic wallpapers from the internet with this selection. You must order these photos manually from nightfall to sunset.
### Upload an HEIC file
If you have an HEIC file, you can upload it and order photos manually.
### Get Automation Times
This will give you the times to run automations for the SnoWalls ❄️ shortcut with the images you have set up. If you have not setup any images, it will not run. This also runs each time you set up new images. You can disable this in settings.
### Settings
Enable extensions. More info here
Disable automation times
### Donate
Donate some cash to help the cause, PayPal, Venmo, Zelle, Google Pay, Buy me a Coffee, and Cash App
### Quit
Exits the setup menu

## Tutorial
### This is a tutorial on how to setup automations to run the shortcut. It is very easy to do, but can take a few minutes if you have a lot of images.

Example Output:
"# You’re Almost Finished!

All you need to do now is setup automations to run this 
Shortcut in the Shortcuts App at the following times.

"## Automation Times:

1. Run at 45 minutes before Sunrise 🌄
2. Run at 15 minutes after Sunrise 🌄
3. Run at 1 hour after Sunrise 🌄 
4. Run at 12:00 PM ⏰
5. Run at 45 minutes before Sunset 🌅
6. Run at 15 minutes after Sunset 🌅
7. Run at 2 hours after Sunset 🌅  
<img src="/instructions.GIF?raw=true">

## Extensions
### WeatherWalls
WeatherWalls is a shortcut created by u/apoch8000 that allows you to set the weather as your wallpaper. I have recreated it to allow for native support with my shortcut, all you have to do is enable it in settings and it will set the weather as the lock screen and your SnoWall ❄️ as the homescreen. All images are property of their creators.
### SunMoonWeather
SunMoonWeather is a shortcut created by @thewaytozion sets your wallpaper as an informative UI with weather details and sunrise/sunset effect. I have adapted it to run natively with SnoWalls ❄️. By default, it will overlay the temperature and city on the lock screen. You can configure the settings within the shortcut section for SunMoonWeather.
### Maui Snorkel Report 🤿
This extension was created by me and overlays the snorkeling conditions in Maui, HI on your lock screen. It only runs if you are in Maui and if the time is between 6 am and 12 pm.
### Custom Extension
With a custom extension enabled, you will be propmted to input the name of the shortcut you are running as an extension. It will run after all other extensions. When creating this shortcut, create an action where it accepts an image as shortcut image. From here, you can overlay text or images onto it, or customize your wallpaper further in anyway you want. Just make sure to end the shortcut with the action "Exit Shortcut with [the final wallpaper image].
