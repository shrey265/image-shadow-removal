# Image Shadow Removal

<br>
This project was an effort to clean the dark regions present in an image.
<br><br>

  <img src="https://github.com/shrey265/image-shadow-removal/blob/05fa0ca79719e5695e1468db67d59fcfc326f81c/examples/bird.png" alt="bird with shadow" width="200" height="200">     <img src="https://github.com/shrey265/image-shadow-removal/blob/05fa0ca79719e5695e1468db67d59fcfc326f81c/examples/bird-cleaned.png" alt="bird without shadow" width="200" height="200">

   <img src="https://github.com/shrey265/image-shadow-removal/blob/05fa0ca79719e5695e1468db67d59fcfc326f81c/examples/cans.png" alt="cans with shadow" width="200" height="200">    <img src="https://github.com/shrey265/image-shadow-removal/blob/05fa0ca79719e5695e1468db67d59fcfc326f81c/examples/cans-cleaned.png" alt="cans without shadow" width="200" height="200">

This project uses -> [dataset](https://codalab.lisn.upsaclay.fr/competitions/17539) to train [ShadowFormer](https://github.com/GuoLanqing/ShadowFormer) as base shadow removal technology. However ShadowFormer feeds on shadowed image and an image mask.
To use ShadowFormer, another mask generator [SDCM](https://github.com/zhuyr97/SDCM) is used and the result is then fed to ShadowFormer along with the shadowed image. As represented below in flow.

Test data and Results
[here](https://drive.google.com/drive/folders/1vN8K7rVzFIrAPPabgO2tpMmjgLD7s8C0?usp=sharing)


![Flow Chart](https://github.com/shrey265/image-shadow-removal/blob/b86d83c0b12936148f04dc36d41b60d75a3afe97/examples/flow-chart.jpg)
