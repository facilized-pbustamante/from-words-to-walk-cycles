# From Words to Walk Cycles

Learned 2D generation versus disposable 3D proxies for eight-direction pixel-art sprites.

Project page: https://facilized-pbustamante.github.io/from-words-to-walk-cycles/
Paper (preprint draft, not peer reviewed): [paper.pdf](paper.pdf)

Top-down pixel-art games and RPGs need every character drawn from eight directions with a walk cycle. No single model we tried does this consistently; a pipeline does. Route A trained a sprite-sheet generator on an NVIDIA RTX 3090; Route B routes a one-line idea through a disposable 3D proxy on an Apple M5 (local LLM prompt writer, FLUX.2 [klein], Pixal3D, Blender, 3D-aware pixelization). Route B won.

Pablo Bustamante, 2026. Developed with the assistance of Claude (Anthropic). Code will be published separately.
