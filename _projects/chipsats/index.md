---
layout: post
title: ChipSat
description: Designed under Cornell's Space Systems Design Studio, this "satellite on a   chip" carries a complete spacecraft on a single 5x5cm square, including a LoRa radio, GPS module, power system, and various sensors. These were featured in two key missions. Alpha CubeSat, where they were deployed as part of a free flying lightsail, and DeSCENT, which sets out to deploy a swarm of 100 networked ChipSats.
skills: 
  - Power System Design
  - Microcontrollers
  - GPS
  - LoRa
  - Antenna Design/Tuning
  - PCB Design
  - PCB Assembly and Verification

main-image: /project2.jpg
---

---
## Alpha ChipSat 
Publication - Umansky-Castro, J., et al. (Including Tang, G.). (2025). Gram-Scale ChipSat Spacecraft for Light Sailing in LEO. 39th Annual Small Satellite Conference. <br>
Publication Link - <br><br>
### Dipole Antenna Design
VNA Tuning, matching network, helical antenna <br>
Poster <br><br>
### Antenna Testing
Long range weather balloon tests, proof of concept with umd nearspace, <br>
testing on different surfaces to simulate lightsail (glass, cardboard, actual lightsail)
### PCB Assembly
Prototype versions cheaper to assemble ourselves rather than purchase already manufactured <br>
Stenciling, placing components, reflow process, some rework done by hand, working with bom <br>
Didn't design PCB but need to understand schematics + layout files <br>
validation - continuity testing, power testing, with benchtop supply --> with solar panel <br>

## DeSCENT ChipSat  
Publication: <br>
Publication Link: <br>
### Power Budget 
deciding between using solar vs. using battery, bat is shorter path to flight ready + shorter duration flight <br>
Need power budget to spec battery (ultrathin lipos), comparing power consumption between STM combined microcontroller (also saves space) vs. Alpha Chipsat setup <br>
Startup current spike issue (also present on alpha ver), when using battery there was issue where this would cause chipsat to get stuck in a low voltage mode, testing by setting power supply current limit <br>
### PCB Design
Update PCB to match breadboard prototype (for Alpha Setup version/V1), layout challenges <br>

## Embedding images 
### External images
{% include image-gallery.html images="https://live.staticflickr.com/65535/52821641477_d397e56bc4_k.jpg, https://live.staticflickr.com/65535/52822650673_f074b20d90_k.jpg" height="400"%}
<span style="font-size: 10px">"Starship Test Flight Mission" from https://www.flickr.com/photos/spacex/52821641477/</span>  
You can put in multiple entries. All images will be at a fixed height in the same row. With smaller window, they will switch to columns.  

### Embeed images
{% include image-gallery.html images="project2.jpg" height="400" %} 
place the images in project folder/images then update the file path.   


## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}
{% include youtube-video.html id="XGC31lmdS6s" autoplay = "true" %}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header


