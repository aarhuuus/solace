<div id="top"></div>

# solace
Solace is a Discord music bot made using the [Sapphire Framework](https://www.npmjs.com/package/@sapphire/framework) \
that uses [Lavalink](https://github.com/davidffa/lavalink) for its music functions and uses the wrapper [Vulkava](https://www.npmjs.com/package/vulkava) for its Lavalink functionality.

## Function roadmap
- [ ] Music
  - [ ] Queue
  - [ ] Filters
  - [ ] Controls
  - [ ] Multiple Sources
- [ ] Handlers
  - [ ] Server Config Caching (prefixes, for reliability)
  - [ ] Interactions (aka slash commands)
  - [ ] Client and Lavalink Events
  - [ ] Prefix Assignation
  - [ ] Error Reporting
- [ ] Preconditions
  - [ ] Database: (all connection related)
  - [ ] Common Errors: (permissions, channel and guild availability, interactions)
  - [ ] Lavalink Server: (disconnections, errors, track predicaments [e.g, stuck], load failed)

<!-- GETTING STARTED -->
## Getting started

### Prerequisites

This is a list of components you need to ensure an excellent experience.
- npm
- nodejs
- Optional: Git (and Git Bash) for cloning

### Installation

_Below is a step-by-step of how you can do the installing and setting up the app.._

1. Clone the repo
   ```sh
   git clone https://github.com/aarhuuus/solace.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Enter your TOKEN in `.env`
   ```env
   TOKEN=0TFpyEcMy6qSlJTdUGuO1cnn.N4uUrR.7.XiLMTcN27TJmbr9ONoTBJ-6Lp
   ```
4. Replace all the default settings in `config.js`

<p align="right">(<a href="#top">back to top</a>)</p>
