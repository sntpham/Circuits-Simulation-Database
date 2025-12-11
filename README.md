Continue building more circuit based on [mick001 (Michy)](https://github.com/mick001) repo ([Circuits-LTSpice](https://github.com/mick001/Circuits-LTSpice))

> [!NOTE]
> For all the curious kids out there who open their toys to see what inside. Who asking questions at the right time.

Below are the circuits with simulation. Additionally, more notes can be found in [Misc](Misc/LTSpice-for-beginner.md)

- [Amplifiers](#amplifiers)
- [Basics](#basics)
- [Comparator circuits](#comparator-circuits)
  - [Other circuits with hysteresis](#other-circuits-with-hysteresis)
- [Controller-control-systems](#controller-control-systems)
- [Filters](#filters)
  - [RC](#rc)
  - [RL](#rl)
  - [RLC](#rlc)
- [Input stages](#input-stages)
- [Loads](#loads)
- [Logic-circuits](#logic-circuits)
- [Oscillators-and-Timers](#oscillators-and-timers)
- [Power-Electronics](#power-electronics)
- [Power-Sources](#power-sources)
- [Protection Circuit](#protection-circuit)
  - [Current limiting circuits](#current-limiting-circuits)
  - [Overvoltage protection circuits](#overvoltage-protection-circuits)
- [Signal-Processing-and-Modulation](#signal-processing-and-modulation)
- [Simulation-Techniques](#simulation-techniques)
- [Transformer](#transformer)
  - [Transmission-and-Power-Lines](#transmission-and-power-lines)

---

### Amplifiers

| Name                                            | Img                                            |
| ----------------------------------------------- | ---------------------------------------------- |
| A-class-amplifier-bjt.asc                       | ![1764299557576](image/README/1764299557576.png) |
| BJT-emitter-follower-configuration.asc-         | ![1764299639299](image/README/1764299639299.png) |
| Common-collector-emitter-follower-amplifier.asc | ![1764300449384](image/README/1764300449384.png) |
| Common-emitter-amplifier-design.asc             | ![1764300471164](image/README/1764300471164.png) |
| Common-emitter-BJT.asc                          | ![1764300490334](image/README/1764300490334.png) |
| Differences-amplifier.asc                       | ![1764300599935](image/README/1764300599935.png) |
| Differential-pair.asc                           | ![1764300620956](image/README/1764300620956.png) |
| Double-stage-common-emitter-amplifier.asc       | ![1764300650553](image/README/1764300650553.png) |
| Instrumentation-amplifier.asc                   | ![1764300691298](image/README/1764300691298.png) |
| Push-pull-amplifier-AB-BJT.asc                  | ![1764300723590](image/README/1764300723590.png) |
| Push-pull-amplifier-operational-amplifier.asc   | ![1764300757494](image/README/1764300757494.png) |
| Push-pull-amplifier.asc                         | ![1764300776960](image/README/1764300776960.png) |

### Basics

| Name                                  | Img                                                                                                                                             |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| DC-transfer-function-analysis.asc     | ![1764300878358](image/README/1764300878358.png)                                                                                                  |
| Example-of-DC-sweep.asc               | ![1764363611972](image/README/1764363611972.png)                                                                                                  |
|                                       | In this example, voltage is swept from -10 to 10V, as voltage source greater than 0V,<br />the voltage drop is about 0.7V from the diode side  |
| How-to-set-initial-conditions.asc     | ![1764363776868](image/README/1764363776868.png)                                                                                                  |
| Parallel-resistor-when-negligible.asc | ![1764363998463](image/README/1764363998463.png)                                                                                                  |
| PNP-transistor-biasing.asc            | ![1764364712101](image/README/1764364712101.png)                                                                                                  |
| Transistor-beta.asc                   | ![1764364888680](image/README/1764364888680.png)                                                                                                  |
| RC-with-switch.asc                    | ![1765086382154](image/README/1765086382154.png)                                                                                                  |

### Comparator circuits

| Name                                                      | Img                                            |
| --------------------------------------------------------- | ---------------------------------------------- |
| Comparator-with-hysteresis-asymmetrical-window.asc        | ![1764365421687](image/README/1764365421687.png) |
| Comparator-with-hysteresis-symmetrical-window.asc         | ![1764365481305](image/README/1764365481305.png) |
| Comparator-with-hysteresis-window-shifted-from-origin.asc | ![1764365526306](image/README/1764365526306.png) |
| comparatore-con-isteresi-finestra-shifted-calculations.py |                                                |
| Window-comparator.asc                                     | ![1764365619767](image/README/1764365619767.png) |
| zero-crossing-detector-2.asc                              | ![1764365900676](image/README/1764365900676.png) |
| zero-crossing-detector.asc                                | ![1764365857128](image/README/1764365857128.png) |

#### Other circuits with hysteresis

| Name                       | Img                                            |
| -------------------------- | ---------------------------------------------- |
| schmitt_trigger_bjts.asc   | ![1764366235239](image/README/1764366235239.png) |
| schmitt_trigger_bjts_2.asc | ![1764366372143](image/README/1764366372143.png) |

### Controller-control-systems

| Name                                   | Img                                            |
| -------------------------------------- | ---------------------------------------------- |
| Bang-bang-control.asc                  | ![1764366468147](image/README/1764366468147.png) |
| Buck-converter-closed-loop-control.asc | ![1764366541144](image/README/1764366541144.png) |
| PD-controller.asc                      | ![1764366581506](image/README/1764366581506.png) |

### Filters

#### RC

| Name                                    | Img                                                                                                            |
| --------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| RC-bandpass-filter-frequency-domain.asc | ![1764465693109](image/README/1764465693109.png)                                                                 |
| RC-highpass-frequency-domain.asc        | ![1764521426390](image/README/1764521426390.png)                                                                 |
| RC-lowpass-frequency-domain.asc         | ![1764521477269](image/README/1764521477269.png)                                                                 |
| RC-lowpass-cascaded.asc                 | ![1764521549155](image/README/1764521549155.png)<br /><br />Output of lowpass number two as stronger attenuation |
| RC-lowpass-step-response.asc            | ![1764521936799](image/README/1764521936799.png)                                                                 |
| RC-lowpass.asc                          | ![1764465389586](image/README/1764465389586.png)                                                                 |
| RC-sawtooth-response.asc                | ![1764522030919](image/README/1764522030919.png)                                                                 |
| RC-square-wave-response.asc             | ![1764522070018](image/README/1764522070018.png)                                                                 |
| RC.py                                   |                                                                                                                |

#### RL

| Name            | Img                                            |
| --------------- | ---------------------------------------------- |
| RL-highpass.asc |                                                |
| RL-lowpass.asc  | ![1764465823388](image/README/1764465823388.png) |
| RL.py           |                                                |

#### RLC

| Name                                                      | Img |
| --------------------------------------------------------- | --- |
| LC-and-RC-series-bandpass-filter.asc                      |     |
| Notch-and-band-suppress-filters.asc                       |     |
| RLC-critically-damped-series-parallel.py                  |     |
| RLC-overdamped-series-parallel.py                         |     |
| RLC-step-response-example.asc                             |     |
| RLC-step-response-resonance-frequency-series-parallel.asc |     |
| RLC-underdamped-series-parallel.py                        |     |

### Input stages

| Name                         | Img/Des |
| ---------------------------- | ------- |
| professional-input-stage.asc |         |

### Loads

| Name                     | Img/Des |
| ------------------------ | ------- |
| constant-P-R-I-loads.asc |         |

### Logic-circuits

| Name                               | Img                                            |
| ---------------------------------- | ---------------------------------------------- |
| Logic-gates-diodes-transistors.asc | ![1764366907357](image/README/1764366907357.png) |
| Logic-gates-transistors-BJTs.asc   | ![1764366806898](image/README/1764366806898.png) |

### Oscillators-and-Timers

| Name                                                 | Img |
| ---------------------------------------------------- | --- |
| 555 - Astable mode.asc                               |     |
| 555 - Monostable mode.asc                            |     |
| 555-astable-mode.asc                                 |     |
| 555-bistable-mode.asc                                |     |
| 555-monostable-mode.asc                              |     |
| 555-raw-astable-mode.asc                             |     |
| 555-raw-monostable-mode-temporizzatore.asc           |     |
| 555-timer.asc                                        |     |
| Adjustable-duty-cycle-555-square-wave-oscillator.asc |     |
| Astable-multivibrator.asc                            |     |
| LED-blinking-oscillator.asc                          |     |
| Peak-trigger-circuit.asc                             |     |
| Phase-shift-oscillator-RC.asc                        |     |
| Phase-shift-oscillator.asc                           |     |
| Royer-zvs.asc                                        |     |
| Sawtooth-oscillator.asc                              |     |
| Sensor-triggered-timer-temporizzatore-1.asc          |     |
| Sensor-triggered-timer-temporizzatore-2.asc          |     |
| Sensor-triggered-timer.asc                           |     |
| Variable-duty-cycle-square-wave.asc                  |     |
| Wien-oscillator.asc                                  |     |

### Power-Electronics

| Name                                                                             | Img                                                                                                                                                                                                                                                                                                                                                                                                                          |
| -------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Boost-converter](Misc/Basic-Electronic-Components/Boost-converter.md)-1.asc        | ![1764301078381](image/README/1764301078381.png)                                                                                                                                                                                                                                                                                                                                                                               |
|                                                                                  | Boost converter using the high voltage change during switch OFF<br />from the inductor to continue charge the capacitor.<br />The gain is define by duty cycle (D). D = 1 - Vin/Vout<br /><br />![1764427718609](image/README/1764427718609.png)<br />10u<br />Setup with Arduino is available here: <br />https://www.tinkercad.com/things/2v9zF7lDCHd-boost-converter?sharecode=GUI-prjcMQ9xBO0XAoe3_zGsIDaZpps5Eg2EJEY_V8A |
|                                                                                  | ![1764437149941](image/README/1764437149941.png)                                                                                                                                                                                                                                                                                                                                                                               |
|                                                                                  | I believe in learning or doing small but steady. I just submited my design, hopefully we can assemble<br />everything before 2026. I think this is the best way to learn electronics in general: Sim > Build > Test > Enjoy!                                                                                                                                                                                                 |
| Boost-converter-2.asc                                                            | ![1764301112994](image/README/1764301112994.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Buck-converter.asc                                                               | ![1764360664443](image/README/1764360664443.png)                                                                                                                                                                                                                                                                                                                                                                               |
|                                                                                  | Buck converter reduce voltage with PWM.<br />According to The Art of Electronic, we can consider LC <br />as a low pass filter to smooth out the output voltage                                                                                                                                                                                                                                                             |
| [Cockcroft-walton-multiplier](Power-Electronics\Cockcroft-walton-multiplier.md).asc | ![1764360864317](image/README/1764360864317.png)                                                                                                                                                                                                                                                                                                                                                                               |
| DCDC-full-bridge.asc                                                             | ![1764359423434](image/README/1764359423434.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Full-bridge-inverter.asc                                                         | ![1764360510198](image/README/1764360510198.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Full-bridge-rectifier.asc                                                        | ![1764301381640](image/README/1764301381640.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Half-bridge-inverter.asc                                                         | ![1764362019759](image/README/1764362019759.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Single-phase-rectifier-constant-current-load.asc                                 | ![1764357326623](image/README/1764357326623.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Single-phase-rectifier-constant-voltage-load.asc                                 | ![1764357475053](image/README/1764357475053.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Single-phase-rectifier-R-load-smoothing-capacitor.asc                            | ![1764359089291](image/README/1764359089291.png)                                                                                                                                                                                                                                                                                                                                                                               |
| soft-starter-12V.asc                                                             | ![1764349019772](image/README/1764349019772.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Three-phase-full-bridge-inverter.asc                                             | ![1764354429254](image/README/1764354429254.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Three-phase-naive-inverter.asc                                                   | ![1764348889523](image/README/1764348889523.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Three-phase-naive-supply-system.asc                                              | ![1764346979800](image/README/1764346979800.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Three-phase-rectifier.asc                                                        | ![1764345869685](image/README/1764345869685.png)                                                                                                                                                                                                                                                                                                                                                                               |
| Example-gain-symbols.asc                                                         | ![1764355634970](image/README/1764355634970.png)                                                                                                                                                                                                                                                                                                                                                                               |

### Power-Sources

| Name                                                                                                                  | Img                                                                                                                                                                                                                                                                                    |
| --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Current-mirrors.asc                                                                                                   | ![1764455394804](image/README/1764455394804.png)<br /><br />Mirror current from Q2 to Ic of Q1                                                                                                                                                                                           |
| Current-source-BJT.asc                                                                                                | ![1764455174977](image/README/1764455174977.png)<br /><br />Discussion can be checked here: [What is constant in a BJT contant current source? - Other Hardware / General Electronics - Arduino Forum](https://forum.arduino.cc/t/what-is-constant-in-a-bjt-contant-current-source/902500) |
| [Raw-voltage-regulator-with-zener-diode](Misc/Basic-Electronic-Components/Raw-voltage-regulator-with-zener-diode.md).asc | ![1764453925162](image/README/1764453925162.png)                                                                                                                                                                                                                                         |
| Voltage-regulator-npn.asc                                                                                             | ![1764439602290](image/README/1764439602290.png)<br />As you see in the figure above, Vref is linearly match with Vout.                                                                                                                                                                 |
| Voltage-doubler.asc                                                                                                   | ![1765464547499](image/README/1765464547499.png)                                                                                                                                                                                                                                         |
| [Voltage-doubler-villard](Power-Electronics/Voltage-doubler-villard.md).asc                                              |                                                                                                                                                                                                                                                                                        |

### Protection Circuit

| Name                       | Img/Des |
| -------------------------- | ------- |
| PTC_Fuse_Calculation.ipynb |         |

#### Current limiting circuits

| Name                                  | Img                                                                                                                                                                       |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BJT-for-simple-current-regulation.asc | ![1764459758090](image/README/1764459758090.png)<br /><br />Adjusting pot resulting in changes in base current. We dont have pot so we use two resistors to represent it.  |
| current-limiting-npn.asc              | ![1764456573595](image/README/1764456573595.png)                                                                                                                            |

#### Overvoltage protection circuits

| Name                                    | Img                                            |
| --------------------------------------- | ---------------------------------------------- |
| overvoltage-protection-zener-diodes.asc | ![1764463153288](image/README/1764463153288.png) |

### Signal-Processing-and-Modulation

| Name                                    | Img |
| --------------------------------------- | --- |
| AM-FM-signals-sources.asc               |     |
| AM-modulator-bjt.asc                    |     |
| AM-modulator-jfet.asc                   |     |
| Analog-multiplier.asc                   |     |
| ASK-modulation.asc                      |     |
| ASK-modulation2.asc                     |     |
| ASK-modulation3.asc                     |     |
| diode-ring-mixer.asc                    |     |
| Inverting-integrator-and-derivative.asc |     |
| Inverting-sum.asc                       |     |
| Non-inverting-derivative.asc            |     |
| Non-inverting-integrator.asc            |     |
| Non-inverting-sum.asc                   |     |
| PWM-modulation.asc                      |     |

### Simulation-Techniques

| Name                                             | Img |
| ------------------------------------------------ | --- |
| Monte-Carlo-Simulation-LTSpice.asc               |     |
| Noise-simulation-example.asc                     |     |
| Temperature-sweep-simulation.asc                 |     |
| Temperature-Variation-and-Worst-case-LTSpice.asc |     |
| Temperature-Variation-LTSpice.asc                |     |
| Worst-Case-Scenario-2-Simulation-LTSpice.asc     |     |
| Worst-Case-Scenario-Simulation-LTSpice.asc       |     |

### [Transformer](Misc/Basic-Electronic-Components/Transformer.md)

| Name                                                                       | Img                                            |
| -------------------------------------------------------------------------- | ---------------------------------------------- |
| Example-of-mutually-coupled-inductors.asc                                  | ![1764367423848](image/README/1764367423848.png) |
| Transformer-step-down-2-1.asc                                              | ![1764686737704](image/README/1764686737704.png) |
| Transformer-step-down-5-1.asc                                              | ![1764686845480](image/README/1764686845480.png) |
| Transformer-step-down-up.asc                                               | ![1764686919433](image/README/1764686919433.png) |
| Transfomer-step-up-1-3-or-1-3-3-3.asc                                      | ![1764685195639](image/README/1764685195639.png) |
| LT8304_400V_Application.asc<br />LT8304 Application Example to output 400V | ![1764686457894](image/README/1764686457894.png) |

#### Transmission-and-Power-Lines

| Name                                            | Img |
| ----------------------------------------------- | --- |
| Ferranti-effect-calculations.xlsx               |     |
| Ferranti-effect-lines.asc                       |     |
| Lossless-transmission-line-DC-transient.asc     |     |
| Lossless-transmission-line-pulse.asc            |     |
| Power-line-power-transmission-calculations.xlsx |     |
| Power-line-power-transmission.asc               |     |



# Note

So what is the point of doing this? You may ask and probally saying chatGPT can perform it better. 

I used chatgpt to learn as well, but sometimes, I see it make mistake. 

For example, I attached a transfomer's circuit once and it parsed the wrong dot notation, then I needed to correct it.

Additionally, imagine one day there is an outage and you are an engineer without Chatgpt or AI access what would you do in this case?

"to be or not to be..." the choice is in our hand.
