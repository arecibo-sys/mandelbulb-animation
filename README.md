# ◉ Mandelbulb — obfuscated WebGL animation

**▶ Live demo: https://arecibo-sys.github.io/mandelbulb-animation/**

Works on desktop, iPhone, and iPad.

A real-time, GPU-raymarched 8th-power Mandelbulb fractal with a morphing power,
dual-axis rotation, rim glow, and a shifting cosmic palette. Runs in any modern
browser — just open `index.html`.

Tap/click once to add a non-intrusive generative soundtrack: a slow cosmic drone
(detuned oscillators + a gentle filter sweep) with sparse, softly-panned bell
shimmers. All audio is synthesized live via the Web Audio API — no sound files,
still a single self-contained page.

The source is deliberately obfuscated: the entire program is XOR-encrypted,
base64-encoded, split into shuffled chunks, and reassembled + decrypted at
runtime by a bootstrap written with single-glyph Unicode identifiers. Not meant
to be read — meant to be watched.

Live: https://arecibo-sys.github.io/mandelbulb-animation/ — or open `index.html` locally.
