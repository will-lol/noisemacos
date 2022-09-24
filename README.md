# noise — an app for making customized white noise for literally any purpose
<img width="624" alt="Screen Shot 2022-09-24 at 11 15 38" src="https://user-images.githubusercontent.com/65345408/192073998-739a2192-b80f-413c-b6f6-d386c39a87d4.png">
White noise is super useful. You can use it to help you sleep, study or just fill a space with noise of some kind. 
I created this app for many creative and the aforementioned 'recreational' purposes.
The app is created with the [tauri](https://tauri.app/) framework.
I am using the WebAudioAPI in order to generate and control the noise. The code is fairly simple (?) but it's a bit of a mess in the single HTML file that I decided to write it all in (for some reason). 
## features
I may in the future refactor or add features to the app, but for now it is limit
ed to:
1. playing white noise
2. changing the EQ of the white noise using sliders
3. changing the gain of the white noise
4. recording and exporting sections of white noise
5. saving a default preset that loads when you launch the app
## building the app
If you don't use MacOS, then the app is entirely un-tested. I may distribute an AppImage for Linux at some point, for now, here are some instructions on how to build the app for your platform.
1. Follow the [tauri prerequesite instructions](https://tauri.app/v1/guides/getting-started/prerequisites)
2. Install the tauri CLI: 'cargo install tauri-cli'
3. git clone this project
4. Run 'cargo tauri build' from the project folder
5. The path to binaries is printed to the console :)
## please enjoy the app. 
Available to download currently for MacOS only, however the tauri CLI is stupid easy to use so compiling for your platform should be no issue. 
Please visit the [releases](https://github.com/will-lol/noise/releases) section.
