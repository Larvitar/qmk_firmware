# SofleV2
## ProMicro
```sh
qmk compile -e BOOTLOADER=caterina -kb splitkb/aurora/sofle_v2 -km qwerty 
qmk flash -bl avrdude splitkb_aurora_sofle_v2_rev1_qwerty.hex
```
## Liatris 
```sh
qmk compile -e CONVERT_TO=liatris -kb splitkb/aurora/sofle_v2 -km qwerty 
```

# Corne
## Liatris 
```sh
qmk compile -e CONVERT_TO=liatris -kb splitkb/aurora/corne -km qwerty 
```

