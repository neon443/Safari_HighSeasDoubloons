# High Seas Doubloons Safari Extension

## Why I ported this extension to Safari
I use Safari as my primary browser, and I wanted to use this extension without switching to Chrome.
pretty simple lol

## Build instructions
1. Requirements: macOS, Xcode, Safari, iOS Device (Optional)
2. `git clone https://github.com/neon443/Safari_HighSeas_Doubloons.git; cd Safari_HighSeas_Doubloons/Safari_HighSeas_Doubloons`
3. `open Xcode.app Safari_HighSeas_Doubloons.xcodeproj`
4. For each target, select your Team ID and change Bundle ID if necessary.
5. Product -> Destination -> Select Device/Simulator
6. Cmd + R to run
7. Enable the extension in Safari Preferences -> Extensions or iOS Settings -> Safari -> Extensions

This project is a browser extension that enhances the experience on the [Hack Club High Seas Shipyard](https://highseas.hackclub.com/shipyard) website by adding useful features and visual updates.


## Why I Made This Project

Each time I ship a project, I find myself wondering how much people voted for me and how many Doubloons I earned per hour.
This led me to manually calculate these values every time I ship a project,
which was time-consuming and repetitive.

To solve this problem, I created this extension to automate the calculations and provide the information at a glance. 
Now, I can focus more on building projects without the hassle of manual calculations.


## Features

1. **Doubloons Per Hour Calculation**
    - Displays how many Doubloons you earned per hour for each project.
    - Adds the total number of votes received (not 100% accurate! :'<).

2. **Average Calculations**
   - Calculates the average Doubloons earned per hour across all projects.
   - Calculates the average Doubloons and votes across all projects.

3. **Expected Doubloons To Earn**
   - While your project is pending, the extension estimates how many Doubloons you might earn.

4. **Prize Time Estimation** *(New Feature Coming Soon!)*
   - Select prizes, and the extension will calculate how much time you need to earn them based on your average Doubloons.


## Preview

![Extension Preview](./view.jpg)
*A perview image shows the added features.*


## Installation
1. Download this repository.
2. Open your browser and navigate to `chrome://extensions/` (or equivalent for your browser).
3. Enable **Developer Mode**.
4. Click **Load unpacked** and select the folder containing this extension.

## Usage

1. After installing, open the [Hack Club High Seas Shipyard](https://highseas.hackclub.com/shipyard).
2. The extension will automatically enhance the page, displaying the new features.

