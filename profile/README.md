# <img src="https://github.com/Luctisity/.github/raw/main/luctisity-small.png" alt="L" height="32" /> Welcome to Luctisity!
This github org contains the source code for different parts of Luctisity's editor and website!

## 🗺️ Roadmap
### Luctisity Basic
- ⚙️ **[luctisity-core](https://github.com/Luctisity/luctisity-basic-core) <br/>**
Core engine for Luctisity Basic, which manages the internal state of the project, sprites and such. It communicates directly with luctisity-render.

- 📜 **[luctisity-evaluator](https://github.com/Luctisity/luctisity-evaluator) <br/>**
A module responsible for executing and evaluating scripts in Luctisity Basics. It uses iframes to evaluate in a safe and isolated way.

- 🎥 **[luctisity-render](https://github.com/Luctisity/luctisity-basic-render)** (TODO) <br/>
Does canvas rendering, audio playback and user input capturing. It communicates directly with luctisity-core.

- 🖌️ **luctisity-editor** (TODO) <br/>
A GUI wrapper for Luctisity Basic, combining luctisity-core, luctisity-evaluator and luctisity-render into one.

### Website
- 🌐 **luctisity-www** (private) <br/>
Luctisity's web platform and social network. This repo contains the front-end code, written in React.

- ☁️ **luctisity-server** (private) <br/>
Sever-side (back-end) code for Luctisity's website.
