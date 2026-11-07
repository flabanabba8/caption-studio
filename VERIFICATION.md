# Verification

- Mixed-case protected-directory fixtures passed on Linux and native Windows; no real credentials were used. This is not a full platform or publication audit.

- Twelve Python tests passed in the Hermes-compatible overlay, including owner-only POSIX output permissions under a permissive umask, offset and drift correction, profile boundaries and Desktop API behavior. Hermes plugin validation passed without warnings.
- A synthetic SRT handoff from YouTube Video Studio was inspected, retimed and reinspected after the permission change. An earlier tutorial-caption offset integration and Desktop flow passed.
- A separate self-authored SRT was retimed from 1–2 seconds to 2–3 seconds and overlaid on a synthetic video cue. Frames sampled at 1.5, 2.5 and 3.5 seconds were inspected: the caption and visual cue appeared together only in the middle sample. No audio or real-media synchronization was reviewed.
- Native Windows Python 3.14 passed one synthetic SRT offset correction. Windows ACL behavior and the Desktop UI were not tested.
- Existing files are not retroactively chmodded. Real audiovisual synchronization, native visual review, full Windows coverage, reviewed demonstration and complete publication audit remain unverified.
