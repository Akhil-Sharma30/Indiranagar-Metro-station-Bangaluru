# Indiranagar-Metro-station-Bangaluru
Recreating the Indiranagar Metro Station, Bengaluru in Unity3D. With the metro station at the center recreating a 2x2sq.km area.

Unity Project `Supported Version: 2022.3.11f1`

### So I tried recreating the area using 
1. Cesium
2. BingMap
3. Google Map Platformer
4. Blackshark.ai

**Note**: `Blackshark.ai` is a recent solution for tackling this issue, but it is not currently available for free.

## Analysis 
1. Cesium amd Google Map Platformer 
> When I attempted to use Cesium and the Google Maps Platform, it allowed me to generate a 2D representation of the area. However, since there was no photorealistic 3D model available for this location and no pre-existing model to import, creating a accurate 3D representation within the limited timeframe was not feasible.

> I attempted to include placeholder buildings on the Cesium map to gain a preliminary understanding of the level of detail required to create a 3D representation.

### With Cesium (Google Map Platformer) demo 
### Without Building 
[![Cesium Map Demo](https://img.youtube.com/vi/clcWNpJStY8/0.jpg)](https://youtu.be/clcWNpJStY8)

### Demo building placed on the 2D surface
[![Cesium Map Demo](https://img.youtube.com/vi/587E1N5nkgc/0.jpg)](https://youtu.be/587E1N5nkgc)

2. BingMap
> It is api provided by Microsoft in which you could visualize the area on the earth with its 3D representation on the unity, but the same case happened with it there was no 3D model pre-trained for the bengaluru City specific.

**In the below example I created a basic 2x2 square kilometer area in Unity, representing the vicinity of the Indiranagar Metro Station in Bengaluru.**
### With BingMap demo
[![Bing Map Demo](https://img.youtube.com/vi/bBd5wqDNdCE/0.jpg)](https://youtu.be/bBd5wqDNdCE)

### Constraints
We currently lack an accurate 3D model for Bengaluru city, preventing us from incorporating a 3D model at this moment. However, we intend to address this limitation in the future by either creating a model for the city or obtaining an existing 3D model for it.
> [Link to issue ppt](https://docs.google.com/presentation/d/1XHlq1IQLpiWZZtciBZc6Odj5BViFqH3_D1bKcpmzPZ8/edit?usp=sharing)
