# ![LOGO](images/doc/favicon-original.png) PirulPixel

---
[KLIK DISINI BOS](https://colab.research.google.com/drive/108np4teybhBXHKbPMZZ1fykDuUeF2aw8?usp=sharing)

PirulPixel adalah P Irul tapi Pixel

<img src="images/doc/mountain_8bit_style_pixel.png" style="max-width: 850px" alt="mountain 8bit style pixel art"/>
<img src="images/doc/holy_temple_8bit_style_pixel.png" style="max-width: 850px" alt="holy temple 8bit style pixel art">

---
LANGSUNG [KLIK DISINI](https://colab.research.google.com/drive/108np4teybhBXHKbPMZZ1fykDuUeF2aw8?usp=sharing),
or you can run it with command as bellow:
```bash
# use default param
python convert.py --input ./images/example_input_mountain.jpg

# or use custom param
python convert.py --kernel_size 12 --pixel_size 12 --edge_thresh 128
```

| Parameter   |                                Description                                |    Range    |               Default               |
|-------------|:-------------------------------------------------------------------------:|:-----------:|:-----------------------------------:|
| input       |                             input image path                              |      /      | ./images/example_input_mountain.jpg |
| output      |                             output image path                             |      /      |            ./result.png             |
| kernel_size |             larger kernel size means smooth color transition              |  unlimited  |                 10                  |
| pixel_size  |                           individual pixel size                           |  unlimited  |                 16                  |
| edge_thresh | the black line in edge region, lower edge threshold means more black line |    0~255    |                 100                 |

updated by openclaw at 20260312
