# Aurelis

<p align="center">
  <img src="assets/aurelis2.webp" width="180" alt="Aurelis">
</p>

<p align="center">
  Professional mobile audio processing and music editing.
</p>

---

## Overview

Aurelis is a mobile audio processing platform designed for musicians,
vocalists, producers, and creators who want detailed control over their
sound.

The project combines a dedicated DSP engine with a modern mobile interface,
allowing audio to be recorded, edited, processed, previewed, and exported
without relying on external audio applications.

Aurelis is designed to grow beyond basic audio manipulation into a complete
mobile audio workstation.

## Core Processing

### Pitch & Time
- Independent pitch shifting
- Independent tempo adjustment
- Time stretching
- Formant shifting
- Pitch/formant separation

### Dynamics
- Compressor
- Limiter
- Input/output gain
- Threshold, ratio, attack, and release controls
- Ceiling control

### Spatial & Modulation
- Echo / delay
- Reverb
- Flanger
- Stereo width
- Pre-delay
- High-frequency damping
- Room-size control

### Stereo & Vocal Processing
- Vocal reduction
- Low/high frequency filtering
- Mono processing
- Independent left/right input gain
- Stereo inversion

## Audio Engine

Aurelis is built around an independent DSP architecture rather than
implementing effects as UI-only controls.

Processing parameters are validated before reaching the audio engine, and
rendered audio is processed as PCM data before being written to the output
format.

The architecture is designed so individual processors can be improved or
replaced without requiring the entire application to be rewritten.

## Processing Philosophy

Aurelis aims to provide:

- High-quality audio processing
- Stable parameter handling
- Non-destructive editing
- Independent effect controls
- Consistent processing between preview and export
- Expandable DSP architecture
- Reliable offline rendering
- Low-latency audio capabilities where supported

## Development

The repository contains the Aurelis application, audio-processing engine,
DSP components, Android integration, and supporting development tools.

The project is actively developed and features may change as the processing
engine evolves.

## Contributing

Aurelis is open to development contributions and improvements.

Contributors may inspect and modify the source for development purposes.
However, redistribution, publication of modified versions, commercial use,
or distribution of derivative versions requires permission from the project
owner.

Please contact the project owner before publicly redistributing Aurelis or
creating an independent release.

## Releases

Official builds are published through GitHub Releases.

Each release may include:

- Android APK
- Version information
- Release notes
- Bug fixes
- DSP improvements
- New processing features

## License

Aurelis Personal Development License

Copyright Â© 2026 Aurelis. All rights reserved.

See `LICENSE` for the complete terms.
