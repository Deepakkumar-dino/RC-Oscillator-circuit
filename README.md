# RC-Oscillator-circuit
This project showcases a classic RC phase shift oscillator built around an NPN bipolar junction transistor (BJT). Designed to generate a clean sine wave using only resistors, capacitors, and one active device, it’s a minimalist masterpiece for analog enthusiasts.
⚙️ Circuit Highlights
NPN BJT (e.g., BC547, 2N3904) as the active gain element

Three-stage RC network for 180° phase shift

Common-emitter amplifier adds another 180° phase shift

Single power rail operation (typically +12V)

🧠 How It Works
The RC network shifts the phase of the signal by 180°

The NPN BJT amplifies and inverts the signal, adding another 180°

Total phase shift = 360°, satisfying the Barkhausen criterion

If loop gain ≥ 1, the circuit oscillates naturally

🧪 Components Used
Component	Value
NPN BJT - BC547B
Resistors -	100kΩ ×3, 3k, 15k, 1k
Capacitors	100 µF ×3, 220 µF, 470 nF
Power Supply	+15V
📈 Output
Waveform: Sine wave

Frequency: ~100 kHz (tunable via RC values)

Amplitude: Depends on supply voltage and gain

🛠️ Applications
Signal generation

Audio tone creation

Analog waveform experiments

Educational demos

## 📚 References

- [Barkhausen Criterion](https://en.wikipedia.org/wiki/Barkhausen_stability_criterion)
- [RC Oscillator Theory](https://www.electronics-tutorials.ws/oscillator/rc_oscillator.html)

---
