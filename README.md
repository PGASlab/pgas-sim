# PGAS simulation

**▶ Live: https://pgaslab.github.io/pgas-sim/**

Try PGAS without any hardware. PGAS is an AI nose on the Arduino UNO Q that
tells you when food has gone bad. Press **Test freshness**, then watch the
board's LED matrix count down while three simulated gas sensors smell the food.

- The UNO Q code path of the real sketch (`app/sketch/sketch.ino`) runs in your
  browser on an emulated UNO Q MCU API: 14-bit ADC, Bridge and LED matrix.
  The STM32 chip itself is not emulated.
- Food gas levels are simulation parameters, not measurements.
- Everything runs in the page. It makes no network calls except loading Google Fonts.

Source, hardware build and write-up: [PGASlab/app](https://github.com/PGASlab/app) ·
[demo video](https://youtu.be/n88pRiuib3U)

This page is built from `sim/web/pgas-unoq-sim.html` in PGASlab/app (MIT).
