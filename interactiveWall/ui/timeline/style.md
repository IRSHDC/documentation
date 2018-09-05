# Map Stylesheet
Here is a copy of the most current stylesheet for the map explorer.

```
Map {
  background-color: #222;
}

.shoreline {
  line-color:#46555D;
}

.shoreline [zoom=5] {
  line-width: 0.25;
}

.shoreline [zoom=6] {
  line-width: 0.34375;
}

.shoreline [zoom=7] {
  line-width: 0.4375;
}

.shoreline [zoom=8] {
  line-width: 0.53125;
}

.shoreline [zoom=9] {
  line-width: 0.625;
}

.shoreline [zoom=10] {
  line-width: 0.71875;
}

.shoreline [zoom=11] {
  line-width: 0.8125;
}

.shoreline [zoom=12] {
  line-width: 0.90625;
}

.shoreline [zoom=13] {
  line-width: 1.0;
}

.snowice {
  polygon-fill:#6F818A;
}

#NUSnowIce {
  line-color: #6F818A;
}  

#NUSnowIce [zoom<=7] {
  line-opacity: 0.5;
}

#NUSnowIce [zoom>7] {
  line-opacity: 0.2;
}

#NUSnowIce [zoom>10] {
  line-opacity: 0.1;
}

.snowice [zoom=5] {
  polygon-opacity: 1.0;
}

.snowice [zoom=6] {
  polygon-opacity: 0.95;
}

.snowice [zoom=7] {
  polygon-opacity: 0.9;
}

.snowice [zoom=8] {
  polygon-opacity: 0.85;
}

.snowice [zoom=9] {
  polygon-opacity: 0.8;
}

.snowice [zoom=10] {
  polygon-opacity: 0.75;
}

.snowice [zoom=11] {
  polygon-opacity: 0.7;
}

.snowice [zoom=12] {
  polygon-opacity: 0.65;
}

.snowice [zoom=13] {
  polygon-opacity: 0.6;
}

.road {
  line-color:#fff;
  line-opacity: 0.25
}

.road [zoom=5] {
  line-width: 0.1;
  line-opacity: 0.0625;
}

.road [zoom=6] {
  line-width: 0.11875;
  line-opacity: 0.125;
}

.road [zoom=7] {
  line-width: 0.1375;
  line-opacity: 0.1875;
}

.road [zoom=8] {
  line-width: 0.15625;
}

.road [zoom=9] {
  line-width: 0.175;
}

.road [zoom=10] {
  line-width: 0.19375;
}

.road [zoom=11] {
  line-width: 0.2125;
}

.road [zoom=12] {
  line-width: 0.23125;
}

.road [zoom>=13] {
  line-width: 0.25;
}
```