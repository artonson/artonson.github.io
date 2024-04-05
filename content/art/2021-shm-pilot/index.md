---
title: 'Conservation of Cultural Heritage Artifacts for State Historical Museum'
date: '2022-11-23'
draft: false
publishDate: '2021-08-04T13:25:02.626580Z'
authors:
- Tatyana Saracheva
- Alexey Artemov
- Evgeny Burnaev
- Oleg Voynov
- Saveliy Galochkin
- Arseniy Bozhenko
- Pavel Karpyshev
- Timofey Glukhikh
featured: false
abstract: 'The preservation of historical and cultural heritage is an important task for modern society as multiple modern historical and cultural world heritage sites are endangered and require significant efforts for their conservation. In Russia, roughly 30 thousand cultural heritage sites are present in Central Federal district alone. Digital models help preserve what time and circumstances may otherwise destroy. This work is a pilot collaboration project between Skoltech and State Historical Museum aimed at designing a 3D scanning and reconstruction pipelines for cultural and historical artefacts and creating 3D replicas of museum exhibits and buildings.'
url_video: https://www.youtube.com/watch?v=yYbY_0LI2CE&t=2991s

---

## Task

> [State Historical Museum](https://shm.ru) seeks to develop a sustainable methodology 
> for digitizing its collection of unique historical artefacts and surveying its buildings.
> This pilot project includes creating of digital replicas of two unique objects from SHM collection
> and 3D models of separate spaces in the Pokrovsky Cathedral.



## 3D Scanning and Image Capture Process

We have found that using only photo camera or only a 3D scanner does not lead to satisfactory results and decided to combine accurate 3D geometry captured by the laser scanner and high-quality, high-resolution images acquired by a DSLR camera.

Photo capture process was implemented by configuring Canon EOS 60D DSLR for stationary capture.
<img src="images/photo_capture.jpg" alt="Photo capture process by Canon EOS 60D." style="width:800px;"/>


The photos acquired by Canon EOS 60D DSLR were used to reconstruct a 3D model of the Western Gallery in the Pokrovsky Cathedral (click to enlarge).

<a href="images/1_real.jpg"><img src="images/1_real.jpg" alt="Real images of the Western Gallery captured by our DSLR." style="width:250px;"/></a>
<a href="images/2_real.jpg"><img src="images/2_real.jpg" alt="Real images of the Western Gallery captured by our DSLR." style="width:250px;"/></a>
<a href="images/3_real.jpg"><img src="images/3_real.jpg" alt="Real images of the Western Gallery captured by our DSLR." style="width:250px;"/></a>
<a href="images/4_real.jpg"><img src="images/4_real.jpg" alt="Real images of the Western Gallery captured by our DSLR." style="width:250px;"/></a>
<a href="images/5_real.jpg"><img src="images/5_real.jpg" alt="Real images of the Western Gallery captured by our DSLR." style="width:250px;"/></a>


A different gallery in the cathedral was acquired by Sony A7IV camera mounted on an automatic turning device.

{{< video id="photo_acquisition" src="videos/photo_acquisition_800x450.mp4" width="800" height="400" mute="true" autoplay="false" loop="false" >}}



3D scanning of room-size spaces was performed by Leica BLK360 laser scanner. 
<img src="images/scan_capture.jpg" alt="3D scanning by Leica BLK360 laser scanner." style="width:800px;"/>

{{< video id="scan_acquisition" src="videos/scan_acquisition_800x450.mp4" width="800" height="400" mute="true" autoplay="false" loop="false" >}}


For smaller objects, we have also used a hand-held Artek Space Spider structured-light 3D scanner.

{{< video id="handheld_scan_acquisition" src="videos/handheld_scan_acquisition_800x450.mp4" width="800" height="400" mute="true" autoplay="false" loop="false" >}}


## 3D Models of Museum Spaces

The resulting reconstructions of the Western Gallery of the Pokrovsky Cathedral come in the form of textured meshes.
We perform post-reconstruction optimization to refine texture of the 3D models. 

**Left:** no optimization; **Right:** with optimization.

{{< video id="wg_reconstruction" src="videos/western_gallery_3d_1000x334.mp4" width="800" height="400" mute="true" autoplay="false" loop="false" >}}


We separately present textured visualizations and geometry renders.

| Textured 3D model | Geometry render |
|-|-|
| {{< video id="western_gallery_3d_col" src="videos/western_gallery_3d_col.mp4" width="400" height="225" mute="true" autoplay="true" loop="true" >}} | {{< video id="western_gallery_3d_geo" src="videos/western_gallery_3d_geo.mp4" width="400" height="225" mute="true" autoplay="true" loop="true" >}} |
{.video-gallery}


For comparison with real images captured by our DSLR, we present high-res renders taken from the textured 3D models (click to enlarge).

<a href="images/1_render.jpg"><img src="images/1_render.jpg" alt="Renders of the Western Gallery made using our 3D reconstruction." style="width:250px;"/></a>
<a href="images/2_render.jpg"><img src="images/2_render.jpg" alt="Renders of the Western Gallery made using our 3D reconstruction." style="width:250px;"/></a>
<a href="images/3_render.jpg"><img src="images/3_render.jpg" alt="Renders of the Western Gallery made using our 3D reconstruction." style="width:250px;"/></a>
<a href="images/4_render.jpg"><img src="images/4_render.jpg" alt="Renders of the Western Gallery made using our 3D reconstruction." style="width:250px;"/></a>
<a href="images/5_render.jpg"><img src="images/5_render.jpg" alt="Renders of the Western Gallery made using our 3D reconstruction." style="width:250px;"/></a>



## 3D Replicas of Museum Exhibits

We present 3D recontructions of important museum exhibits. 



The Book of Gospels (1692) ([click here for high-res video](https://www.dropbox.com/scl/fi/y755tali4ahn5w1e4cf4c/book.mp4?rlkey=vp5o9vqrwm32fyz1zj6si2g0t&dl=0)).

{{< video id="gospel_book" src="videos/gospel_book_800x800.mp4" width="800" height="800" mute="true" autoplay="false" loop="false" >}}



The ceramic voice resonator jug (Russian: голосник) from the Church of the Three Patriarchs (mid-17th century) ([click here for high-res video](https://www.dropbox.com/scl/fi/yi90y037nob4lwbglcwme/golosnik.mp4?rlkey=0t7pls67ne8hmmdldqmwmkc9v&dl=0)).

{{< video id="golosnik" src="videos/golosnik_800x800.mp4" width="800" height="800" mute="true" autoplay="false" loop="false" >}}



## Video Report (in Russian)

{{< youtube id="yYbY_0LI2CE?start=2991" autoplay="false" >}}



## The Team

 * **Museum manager (SHM):** Tatyana Saracheva
 * **Data acquisition (Skoltech):** Saveliy Galochkin, Arseniy Bozhenko, Pavel Karpyshev, Timofey Glukhikh
 * **Data processing and 3D reconstruction (Skoltech):** Oleg Voynov, Saveliy Galochkin
 * **Project managers (Skoltech):** Alexey Artemov, Evgeny Burnaev

