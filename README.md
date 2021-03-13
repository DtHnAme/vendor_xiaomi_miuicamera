Copyright (C) 2020 Carlos Ayrton Lopez Arroyo (Official-Ayrton990)

Copyright (C) 2020 ANXCamera by AEonAX

MiuiCamera from ANXCamera
=========================================

## Currently supported devices:
* Redmi Note 9 Pro 5G (gauguinpro)
## Maybe working devices:
* Mi10i (gauguininpro)
* Mi10t Lite (gauguin)
## How to build?

- Simply on you device.mk inherit the repo by: `$(call inherit-product-if-exists, vendor/xiaomi/miuicamera/config.mk)`
- It's adviced to include sepolicy even if you are not running enforced system, include sepolicy on your BoardConfig.mk by: `-include vendor/xiaomi/miuicamera/BoardConfigVendor.mk`
- Clone this repo following the path: `rom-source/vendor/xiaomi/miuicamera`

## Bugs:
- 108MP Not Working (Only have 1920x1080)
- Front Camera mode crashing 
- Portrait mode crashing (if triggered, clean data and follow next step again)
- It needs to grant manually all permissions requiered to avoid force close
- Wide angle seems to be not working
