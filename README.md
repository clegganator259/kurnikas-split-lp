# kurnikas-split-lp
My attempt at designing my perfect split ergo keyboard

# Attribution

For the battery connector and led footprints @celolides fantastic [footprint library](https://github.com/ceoloide/ergogen-footprints)
For the choc v1 reversible footprints @ergogen + @infused-kim, @ceoloide, @grazfather, @nxtk improvements

For the videos that helped make this possible [Christian Sellig's wonderful video](https://www.youtube.com/watch?v=7UXsD7nSfDY)
# BOM
## PCB Components
|Component                            |                    Quantity|
|-------------------------------------|---------------------------:|
|kurnikas-split-lp PCB                |                           2|
|Nice nano v2 compatible board        |                           2|
|Choc v1 Key switches                 |                          64|
|SK6812 mini-e RGB                    |                          64|
|EC12/EC11 low profile encoder        |                           2|
|1N4148W SOD123 Diodes                | 64/66 if using EC11 Encoder|
|JST PH2 board connector              |                           2|
|3.7v Lipo battery thickness < 8mm    |                           2|
|JST PH2 male connectors for batteries|                           2|
|7 pin on/off toggle slide switch     |                           2|
|SKQGABE010 touch switch smd          |                           2|

## Case components
### Full case
|Component         | Quantity|
|------------------|--------:|
|8mm m2 standoffs  |       10|
|m2 flat top screws|       10|
|[Left hand faceplate](production/full-case-3dprint/face-plate-left.stl)| 1|
|[Right hand faceplate](production/full-case-3dprint/face-plate-right.stl)| 1|
|[Left hand Backplate](production/full-case-3dprint/base-plate-right.stl)| 1|
|[Right hand Backplate](production/full-case-3dprint/base-plate-left.stl)| 1|

### Sandwich Case
|Component                             | Quantity|
|--------------------------------------|--------:|
|m2x4mm chicago screws with max 3mm OD |       10|
|Faceplate ([laser cut](production/sandwich-case-laser-cut/faceplate.dxf)/[3d printed](production/sandwich-case-3dprint/faceplate.stl)) |2|
|Baseplate ([laser cut](production/sandwich-case-laser-cut/baseplate.dxf)/[3d printed](production/sandwich-case-3dprint/baseplate.stl)) |2|


## Making your own

For a more detailed tutorial please go to [the build tutorial](docs/tutorial.md)
