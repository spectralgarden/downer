down er — Chop / Screw / Melancholy Audio Processing System
Real‑time tape‑deceleration, stutter looping, formant shifting, and atmospheric rain‑space DSP.

Overview
down er is a real‑time audio effect inspired by chopped & screwed tape culture, corrupted save screens, and the slow decay of aging magnetic media.
It combines a latency‑free pitch decelerator, a sample‑accurate stutter engine, independent vocal formant processing, and a dynamic physical‑modeling rain generator that responds to the input signal’s envelope.

Designed for producers exploring slowed‑down memory, spectral ambience, and tape‑stop gravity.

Core Features
Dual‑tap pitch decelerator (1.0x → 0.25x) with wow & flutter modulation

Sample‑accurate stutter engine (30–300 ms capture windows)

3‑band vocal formant filter bank (F1/F2/F3 shifting ±12 st)

Dynamic rain generator gated by a 7 ms / 500 ms envelope follower

Gloom space engine (steep LPF → 180 Hz + dark feedback delay)

20 curated presets modeled after physical environments and tape artifacts

Zero‑latency architecture (no FFT, no phase vocoder)

Full dry/wet mix control

Preset Library
The plugin includes 20 profiles such as:

Classic Screw

Heavy Chop

Silent Hill Fog

Tape Stop Abyss

Ethereal Ghost

Static Rain

VHS Degrade

Graveyard Drift

Deep Void

See the full preset directory in the PDF manual.

Technical Architecture
Dual‑tap circular delay pitch engine with Hann‑window smoothing

Wow & flutter modulation at 1.4 Hz

Formant filter bank (600 Hz / 1600 Hz / 2500 Hz centers)

Envelope‑driven rain generator with high‑Q bandpass noise

Space delay + low‑pass damping

Linear dry/wet mix stage

Platform Support
Windows VST3 (v1.0.0)

Linux VST3/LV2 — planned

macOS VST3/AU — coming soon

Installation
Download the latest release from the Releases tab

Extract the ZIP

Place downer.vst3 into:
C:\Program Files\Common Files\VST3\

Restart your DAW and rescan plugins

Documentation
Full manual (PDF):
downer_manual.pdf  
(Uploaded in this repo)

Build Information
JUCE 8.0.14

C++20

Visual Studio 2026

VST3 format
spectralgarden.net
