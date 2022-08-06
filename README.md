# Coronamap

Coronamap is an interactive thematic map that animates the spread of the coronavirus.

Check out the [deployment](../../deployments "Deployment").

<p align="center">
  <img src="docs/assets/img/desktop.png" width=55% alt="Coronmap on laptop">
  <img src="docs/assets/img/mobile.png" width=20% alt="Coronamap on phone"/>
</p>

## Preview

<p align="center">
  <img src="docs/assets/img/animation.gif" width="75%" alt="Coronamap preview"/>
</p>
Disease data: <a href="https://github.com/CSSEGISandData/COVID-19">Johns Hopkins CSSE</a> (https://github.com/CSSEGISandData/COVID-19)

### Date Slider

<img src="docs/assets/img/timecontrol.png" height="32px" alt="The date slider consisting of several form controls, as follows">

- <img src="docs/assets/img/timecontrol-play.png" height="28px" alt="Right-pointing triangle button">: Play
- <img src="docs/assets/img/timecontrol-reverse.png" height="28px" alt="Left-pointing triangle button">: Reverse
- <img src="docs/assets/img/timecontrol-forward.png" height="28px" alt="Right-pointing double triangle button">: Move to the next day
- <img src="docs/assets/img/timecontrol-backward.png" height="28px" alt="Left-pointing double triangle button">: Move to the previous day
- <img src="docs/assets/img/timecontrol-loop.png" height="28px" alt="Button with circular arrow pointing in a clockwise direction">: Loop
- <img src="docs/assets/img/timecontrol-dateslider.png" height="28px" alt="Range input type positioned to the middle">: Date progress bar
- <img src="docs/assets/img/timecontrol-fps.png" height="28px" alt="Range input type labeled with fps value and a clock icon to the left">: Playback speed

### Colored Geographical Areas

<img src="docs/assets/img/choropleth-legend.png" alt="A yellow to red gradient color ramp legend labeled with the range of infected cases" height="32px">

The yellow-orange-red sequential color scheme shows the *number of infected cases*.

### Circle Markers

<img src="docs/assets/img/circlemarker.png" alt="" width=10> <img src="docs/assets/img/circlemarker.png" alt="" width=15> <img src="docs/assets/img/circlemarker.png" alt="" width=20> <img src="docs/assets/img/circlemarker.png" alt="" width=25> <img src="docs/assets/img/circlemarker.png" alt="" width=30>

The size of a circle marker scales to the *number of deaths*.

## Getting Started

### Prerequisites

* Node.js
```bash
$ yum install nodejs
$ yum install npm
```

* Install npm packages
```bash
$ npm install
```

### Development
* Watch for updates to code and compile automatically: `npm run develop`
* Build the optimized production: `npm run build`
* Run all unit tests: `npm run test`
