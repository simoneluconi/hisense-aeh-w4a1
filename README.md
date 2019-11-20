# Hisense AEH-W4A1
All the information about the Hisense AEH-W4A1 Wifi Controller
The app for this wifi controller is very bad and very slow, so i would like to collect as much
information as possible about this device so that someone can understand how it communicate and, maybe, use another device
with the air conditioner.

The only document i could find is this [teardown from the fccid](https://fccid.io/2AGCCAEH-W4B1/Internal-Photos/Internal-Photos-3120151), where i got the pinout, even if my device is different.
I tried to use ad Arduino with a RS485-Serial adapter but for now i got no results. I tried even directly to the rx/tx pin, the leds blink but no results.

# ANY HELP IS APPRECIATED

## Info

### Control che AC
- [This python library from @bannhead](https://github.com/bannhead/pyaehw4a1)
- Some discussions [here](https://github.com/deiger/AirCon/issues/1) or [here](https://community.home-assistant.io/t/working-on-integration-for-hisense-aeh-w4a1-module/146243)

### Idelan
- **Brand**: Idelan
- **Model**: DL3036A
- **Version**: 1.1
- **Baud Rate**: Unknown

### Topeast
- **Brand**: Topeast
- **Model**: TE-MM02-4004-1
- **Version**: 2.0
- **Baud Rate**: Unknown

### Pinout
+ Red: +5v
+ Yellow: Gnd
+ Blue: A+ (RS485??)
+ Black/White: B- (RS485??)

## Documents
- [AEH-W4B1 WiFi Module Teardown](https://fccid.io/2AGCCAEH-W4B1/Internal-Photos/Internal-Photos-3120151)

## Images
- [Topeast TE-MM02-4004-1 V2.0](https://github.com/simoneluconi/hisense-aeh-w4a1/tree/master/images)
- [Idelan DL3036A V1.1](https://fccid.io/2AGCCAEH-W4B1/Internal-Photos/Internal-Photos-3120151)
