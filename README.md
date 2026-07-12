# ◉ Mandelbulb — obfuscated WebGL animation

**▶ Live demo: https://arecibo-sys.github.io/mandelbulb-animation/**

Works on desktop, iPhone, and iPad.

A real-time, GPU-raymarched 8th-power Mandelbulb fractal with a morphing power,
dual-axis rotation, rim glow, and a shifting cosmic palette. Runs in any modern
browser — just open `index.html`.

The source is deliberately obfuscated: the entire program is XOR-encrypted,
base64-encoded, split into shuffled chunks, and reassembled + decrypted at
runtime by a bootstrap written with single-glyph Unicode identifiers. Not meant
to be read — meant to be watched.

Live: https://arecibo-sys.github.io/mandelbulb-animation/ — or open `index.html` locally.
