# SpyderS-Firmware
Firmware for SpyderS Payload

## Gimbal working mode
- Follow mode
- Lock mode
- Mapping mode

## Reference frame
- Image frame. Keeping LoS in lock mode
  
## Control gimbal
- Speed control in follow mode
- Speed control in lock mode
- Support speed of movement 180 deg/s
  
## Adapting to decrease Pan's drift behavior
- Basic process for adapting: switch to lock mode --> waiting 30s --> return home

## Go to home position automatically when switching to follow mode 

## Detect errors when initialization.
- Gimbal will detect automatically when initialization and pop-up error on the new gTune with the troubleshooting guide.

## Start-up at a random position.
