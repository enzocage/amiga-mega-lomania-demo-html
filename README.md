# Mega-Lomania Demo — The Sunriders (100% Pure HTML5 Clone)

A 100% self-contained, zero-dependency HTML5 Canvas + Web Audio recreation of the 1989 Amiga OCS demo **"Mega-Lomania Demo"** by **The Sunriders (Mic & Marvin)**, as featured on [scene.graphics/amiga/mega-lomania-demo](https://scene.graphics/amiga/mega-lomania-demo).

Reverse-engineered directly from the original Amiga executable (`Sunriders-MegaLomania`):
- **Part 0**: Authentic Amiga TV static precalc screen (`$000/$222/$666/$aaa/$fff`).
- **Part 1 (Logo Reveal)**: All 3 original `192×80` 3-bitplane chrome logos (`SUN`, `MEGA-LOMANIA`, `MIC MARVIN`) dissolving in/out in `16×16` blocks using the exact 48-entry permutation order, with the exact 16-frame animated 4-pointed pink sparkling star sprites (`$744/$c88/$fcc`) and 30-star 3D rotating blue-white starfield (`$447/$88c/$ccf`).
- **Part 2 (3D Perspective Wave + Mirror-Tube Scroller)**: Real-time 3D perspective-tilting/zooming/flag-waving chrome logo driven by the exact choreography script (`0x18de6`) with Z-buffer occlusion and dual traveling sine waves, plus the 64-line Dual-Playfield 3D rotating cylinder mirror-tube scroller with the original `32×32` 3-bitplane chrome font, spinning glowing blue copper bars, and Mic & Marvin's full 1,781-byte cyberpunk story scrolltext.
- **Audio**: 4-channel Amiga Paula chip-synth engine with L-R-R-L stereo and A500 low-pass filter.
