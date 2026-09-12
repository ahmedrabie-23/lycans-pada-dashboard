# Lycans PADA Electrical and Avionics Dashboard

Interactive single-page engineering dashboard for the Lycans AeroDesign PADA fixed-wing UAV electrical system.

## Contents

- Live battery-side power budget
- Mission-mode presets and load sliders
- Interactive electrical architecture diagram
- Component inspector for propulsion, avionics, radio, GPS, and servos
- ESC utilization, battery energy compliance, and validation checklist

## Configuration Modeled

- Motor: SunnySky X2212 V3 1400KV
- Propeller: APC 8 x 6
- Battery: 3S 1300 mAh LiPo, 14.43 Wh nominal
- ESC: 30 A
- Flight controller: Matek F405-WMN
- Navigation: M10 GPS
- Telemetry: ExpressLRS 2.4 GHz
- Servos: 4 x KST X08

## Notes

This is a preliminary design dashboard. The propulsion reference is treated as 25.6 A / 284.2 W at the supplied maximum point, with avionics and servo loads converted to battery-side power using a 90% regulator efficiency assumption. Final acceptance still requires measured current, voltage sag, ESC temperature, motor temperature, wiring temperature, and exact propeller validation.
