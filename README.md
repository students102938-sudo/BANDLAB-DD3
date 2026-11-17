# BandLab Studio Rack & BOSS DD-3 Digital Delay (Zero-Artifact Edition)

## What Was Fixed & Built
1. **100% Zero Khar-Khar Delay Engine:**
   - **Pre-Muted Dual-Buffer Crossfade:** `DelayNode.delayTime` is NEVER modified while a delay bank is audible. New delay times are set on a completely muted buffer first, then smoothly crossfaded over 50ms.
   - **Debounced Manual Slider:** Dragging `D.TIME` waits 80ms before switching buffers so slider movement produces zero zipper noise.
2. **BandLab Delay Modes:** Switch instantly between **DD-3 Digital**, **Ping-Pong Stereo** (`L -> R -> L` cross-feedback panning), and **Warm Tape Echo**.
3. **BandLab Auto Voice EQ, Smooth Noise Gate, Manual Studio Reverb, PWA Install & Offline WAV Export.**
