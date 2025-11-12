# Facial Controller


# facial_gba.py — Facial gestures -> Keyboard (used for: mGBA)
# Mappings:
- LEFT  = half-smile (left corner)   -> tap/hold
- RIGHT = half-smile (right corner)  -> tap/hold
- UP    = brows up (both)            -> hold
- DOWN  = big symmetric smile        -> hold
- A     = "teeth-frown"              -> tap (on release)
- B     = mouth/jaw open             -> tap (on release, with hysteresis)
- ENTER = both eyes closed (long blink)

Tips:
- In mGBA, map arrows to D-Pad and Z/X to A/B (or edit TAP_KEYS/HOLD_KEYS).
- Window is always-on-top so you can see the HUD while playing.

How to run:
- Run: python facial_gba.py
- Requires: MediaPipe face model file ace_landmarker_v2_with_blendshapes.task placed next to the script (not included in repo).
