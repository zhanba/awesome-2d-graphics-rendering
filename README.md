# Awesome 2D Graphics Rendering

## UI Framework

### Web
- [yew](https://github.com/yewstack/yew): Rust / Wasm framework for building client web apps
- [dioxus](https://github.com/DioxusLabs/dioxus): React-like GUI library for desktop, web, mobile, TUI, and more.
- [slint](https://github.com/slint-ui/slint): Slint is a toolkit to efficiently develop fluid graphical user interfaces for any display: embedded devices and desktop applications. We support multiple programming languages, such as Rust, C++, or JavaScript.
- [sycamore](https://github.com/sycamore-rs/sycamore): A library for creating reactive web apps in Rust and WebAssembly

### Native
- [leptos](https://github.com/leptos-rs/leptos): Build fast web applications with Rust.
- [xilem](https://github.com/linebender/xilem): An experimental Rust native UI framework
- [rui](https://github.com/audulus/rui): Experimental Rust UI library
- [blitz](https://github.com/DioxusLabs/blitz): High performance HTML and CSS renderer powered by WGPU
- [floem](https://github.com/lapce/floem): A native Rust UI library with fine-grained reactivity
- [masonry-rs](https://github.com/PoignardAzur/masonry-rs): Rust UI design toolkit.
- [async-ui](https://github.com/wishawa/async_ui): Lifetime-Friendly, Component-Based, Retained-Mode UI Powered by Async Rust
- [reclutch](https://github.com/jazzfool/reclutch): A strong foundation for building predictable and straight-forward Rust UI toolkits
- [vizia](https://github.com/vizia/vizia): A declarative GUI library written in Rust
- [Ribir](https://github.com/RibirX/Ribir): Non-intrusive GUI framework for Rust/WASM

## 2D Graphic editor
- [Graphite](https://github.com/GraphiteEditor/Graphite): Open source 2D node-based raster/vector graphics editor
- [Lapce](https://github.com/lapce/lapce): Lightning-fast and Powerful Code Editor written in Rust

## 2D renderer

- [skia](https://skia.org/): Skia is an open source 2D graphics library which provides common APIs that work across a variety of hardware and software platforms. It serves as the graphics engine for Google Chrome and Chrome OS, Android, Flutter, Mozilla Firefox and Firefox OS, and many other products.
- [cairo](https://www.cairographics.org/): Cairo is a 2D graphics library with support for multiple output devices. Currently supported output targets include the X Window System (via both Xlib and XCB), Quartz, Win32, image buffers, PostScript, PDF, and SVG file output. Experimental backends include OpenGL, BeOS, OS/2, and DirectFB.
- [Core Graphics](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Conceptual/drawingwithquartz2d/Introduction/Introduction.html): also known as Quartz 2D, is an advanced, two-dimensional drawing engine available for iOS, tvOS and macOS application development. Quartz 2D provides low-level, lightweight 2D rendering with unmatched output fidelity regardless of display or printing device. Quartz 2D is resolution- and device-independent.
- [Direct2D](https://learn.microsoft.com/en-us/windows/win32/direct2d/direct2d-portal): Direct2D is a hardware-accelerated, immediate-mode, 2-D graphics API that provides high performance and high-quality rendering for 2-D geometry, bitmaps, and text.
- [Blend2D](https://blend2d.com/): Blend2D is a high performance 2D vector graphics engine written in C++ and released under the Zlib license.
- [pixie](https://github.com/treeform/pixie): Full-featured 2d graphics library for Nim.
- [AmanithSVG](https://www.amanithsvg.com/): AmanithSVG is a high performance native software library that implements fast rendering of static SVG files on top of OpenVG API, developed by Mazatech
- [NanoVG](https://github.com/memononen/nanovg): Antialiased 2D vector drawing library on top of OpenGL for UI and visualizations. (not actively maintained)
- [plutovg](https://github.com/sammycage/plutovg): Tiny 2D vector graphics library in C.
- [ShivaVG](https://github.com/ileben/ShivaVG): OpenGL based ANSI C implementation of the OpenVG standard.
- [MonkVG](https://github.com/micahpearlman/MonkVG): MonkVG is an OpenVG 1.1 like vector graphics API implementation optimized for game use currently using an OpenGL ES backend that should be compatible with any HW that supports OpenGL ES 2.0 which includes most iOS and Android devices.

### Rust 2D renderer
- [vello](https://github.com/linebender/vello): An experimental GPU compute-centric 2D renderer.
- [forma](https://github.com/google/forma): An efficient vector-graphics renderer
- [vger-rs](https://github.com/audulus/vger-rs): 2D GPU renderer for dynamic UIs
- [lyon](https://github.com/nical/lyon): 2D graphics rendering on the GPU in rust using path tessellation.
- [pathfinder](https://github.com/servo/pathfinder): A fast, practical GPU rasterizer for fonts and vector graphics.

## 2D Graphics Standard

- [OpenVG](https://www.khronos.org/openvg/): The Standard For Vector Graphics Acceleration.
- [SVG](https://www.w3.org/TR/SVG2/): W3C Scalable Vector Graphics 2.

## Font/Text Library

- [harfbuzz](https://github.com/harfbuzz/harfbuzz): HarfBuzz text shaping engine
- [pango](https://pango.gnome.org/): Pango is a library for laying out and rendering of text, with an emphasis on internationalization.
- [Allsorts](https://github.com/yeslogic/allsorts): Font parser, shaping engine, and subsetter for OpenType, WOFF, and WOFF2 implemented in Rust.
- [rustybuzz](https://github.com/RazrFalcon/rustybuzz): A complete harfbuzz's shaping algorithm port to Rust
- [swash](https://github.com/dfrg/swash): Font introspection, complex text shaping and glyph rendering.
- [glyph-brush](https://github.com/alexheretic/glyph-brush): Fast GPU cached text rendering
- [parley](https://github.com/lapce/parley): WIP rich text layout library
- [wgpu-text](https://github.com/Blatko1/wgpu-text): A simple 2D text renderer for wgpu
- [glyphon](https://github.com/grovesNL/glyphon): 🦅🦁 Fast, simple 2D text renderer for wgpu

## Graphic Layout Engine
- [taffy](https://github.com/DioxusLabs/taffy): A high performance Rust-powered layout library
- [yoga](https://github.com/facebook/yoga): Yoga is a cross-platform layout engine which implements Flexbox.
- [stretch](https://github.com/vislyhq/stretch): High performance flexbox implementation written in rust
- [morphorm](https://github.com/vizia/morphorm): A UI layout engine written in Rust
- [elkjs](https://github.com/kieler/elkjs): ELK's layout algorithms for JavaScript
- [elk](https://github.com/eclipse-elk/elk): Eclipse Layout Kernel - Automatic layout for Java applications.
- [dagre](https://github.com/dagrejs/dagre): Directed graph layout for JavaScript
- [clay](https://github.com/nicbarker/clay): High performance UI layout library in C.

## Other
- [glazier](https://github.com/linebender/glazier): Glazier is an operating system integration layer infrastructure layer intended for high quality GUI toolkits in Rust. It is agnostic to the choice of drawing, so the client must provide that, but the goal is to abstract over most of the other integration points with the underlying operating system.
- [winit](https://github.com/rust-windowing/winit): Window handling library in pure Rust
- [accesskit](https://github.com/AccessKit/accesskit): UI accessibility infrastructure across platforms and programming languages

## Blog & Paper & Tutorial & Book & Discussion

- [Text Rendering Hates You](https://faultlore.com/blah/text-hates-you/)
- [GPU-accelerated Path Rendering](https://developer.download.nvidia.cn/devzone/devcenter/gamegraphics/files/opengl/gpupathrender.pdf)
- [NVIDIA Path Rendering: Accelerating Vector Graphics for the Mobile Web](https://on-demand.gputechconf.com/gtc/2014/presentations/S4810-accelerating-vector-graphics-mobile-web.pdf)
- [Massively-Parallel Vector Graphics](http://w3.impa.br/~diego/projects/GanEtAl14/)
- [2D Graphics on Modern GPU](https://raphlinus.github.io/rust/graphics/gpu/2019/05/08/modern-2d.html)
- [Why are 2D vector graphics so much harder than 3D?](https://blog.mecheye.net/2019/05/why-is-2d-graphics-is-harder-than-3d-graphics/)
- [Fast 2D rendering on GPU](https://raphlinus.github.io/rust/graphics/gpu/2020/06/13/fast-2d-rendering.html)
- [Blend2D – 2D Vector Graphics Engine](https://news.ycombinator.com/item?id=19580647)
- [Fonts & Encodings](https://www.oreilly.com/library/view/fonts-encodings/9780596102425/)
- [Modern text rendering with Linux: Overview](https://mrandri19.github.io/2019/07/24/modern-text-rendering-linux-overview.html)
- [Rust GUI Infrastructure](http://www.cmyr.net/blog/rust-gui-infra.html)
