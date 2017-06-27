# Instrumentation-Amp

Breakout board for the AD623 instrumentation amplifier.

It is set up to work in either single-supply or dual-supply mode

## Single-supply mode

* Connect VC- (negative supply voltage) to GND using JP_VC- or the screw terminals

For sensors that require a simple common ground (including the reference), you will close the circuit across all of the solder jumpers:
* Connect VS- (negative voltage from device with signal to be amplified) to GND using JP_VS- or the screw terminals
* Connect Vref (reference voltage for the input signal) to GND using JP_VREF or the screw terminals

We use connect all of the jumpers to use a pyranometer.

### Dual-supply mode

We haven't had to use the board this way, but set it up to work!

* Disconnect VC- (negative supply voltage) from GND: check JP_VC- and the screw terminals
* Disconnect VS- (negative voltage from device with signal to be amplified) from GND: check JP_VS- and the screw terminals
