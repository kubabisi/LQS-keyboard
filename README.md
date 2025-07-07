# LQS keyboard
**L**ow profile **Q**uiet **S**plit keyboard

## Why have I decided to build a keyboard?
A few years ago I received an 80% mechanical keyboard as a Christmas gift. It has been my daily driver since then.
But it has two issues:
1. It is too big and chunky to travel with or take it to school.
2. It is too loud. While it is quieter than some mechanical keyboards, you can easily hear it from the other side of my flat.

Since then Youtube algorithm has introduced me into the custom keyboard rabbit hole.
I've built a simple one using 3d printed parts and handwiring. It worked, but it was thick and after a few weeks it started to slowly break apart. First random solder joints started breaking, then the case cracked.

I wanted to build a proper keyboard, but I was too lazy to do it.
Highway gave me the motivation that I needed to finally do it.

## CAD model
![cad model](images/cad-model-final.png)
![exploded cad model](images/cad-model-final-2.png)
[this model in Onshape](https://cad.onshape.com/documents/f682215273ff2081de69d414/w/20c4360147d88d6d7c704790/e/f61e22c6f2ff044978f79a00?renderMode=0&uiState=686bf5d5abd8817fe4595698)

## Switch layout
Switch layout was inspired by two keyboards I like: ZSA Voyager and Sofle
![layout in ergogen](images/ergogen-layout.png)

## Schematic
![keyboard half schematic](images/schematic-final.png)

## PCB
![keyboard half pcb](images/pcb-final.png)

## Case
Case for this keyboard can be 3d printed. Stl files are located in [this folder](3d-models/case)


## BOM

| Part | Quantity | Cost(PLN) | Cost (USD) | Store | Link |
| --- | --- | --- | --- | --- | --- |
| Kailh Deep Sea Whale mini switches | 58 | 113.99 | 29.70 | Aliexpress | https://pl.aliexpress.com/item/1005008927866337.html |
| Pro Micro NRF52840 | 2 | 26.78 | 7.04 | Aliexpress | https://pl.aliexpress.com/item/1005006599766097.html |
| 301230 lipo battery | 2 | 45.25 | 11.70 | Allegro.pl | https://allegro.pl/oferta/akumulator-litowo-polimerowy-110mah-3-7v-phr-2-bk-301230-17500532114 |
| 1n4148 diodes | 58 | 5.55 | 1.47 | Aliexpress | https://pl.aliexpress.com/item/4000142272546.html |
| RGB common anode 5mm led | 2 | 3.99 | 1.05 | Aliexpress | https://pl.aliexpress.com/item/4000225253691.html |
| pin sockets | 52 pins - 2 rows | 7.10 | 1.87 | Aliexpress | https://pl.aliexpress.com/item/10000000838267.html |
| PCB | 5 | 41.80 | 11.60 | JLCPCB | https://jlcpcb.com/ |
| M2 4mm flat head screws | 8 | 3.62 | 0.96 | Aliexpress | https://pl.aliexpress.com/item/1005005270702287.html | 
| M2 3x3mm heat inserts | 8 | 5.6 | 1.47 | Aliexpress | https://pl.aliexpress.com/item/1005008295045821.html |
| resistors for leds | 6 | ~4 | ~1 | |  |
| keycap set | 1 | ~120 | ~35 | | |
| 3d printed case | 2 | | | | |

Total (excluding shipping): ~380 PLN / ~$105 USD

I already have keycaps and resistors. My brother has a 3d printer at home.

Total excluding parts I have, with shipping:
- $66.77 + $21.50 (JLCPCB shipping) + $0 (Aliexpress Choice free shipping) = $88.27
- 253,61zł + 77,63zł + 0zł = 331.24zł
