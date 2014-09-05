## Software Libre Presentations -- Stockfish

Part of the *Software Libre* course given at [National University of Colombia](http://www.disi.unal.edu.co/) by [Jean Pierre Charalambos](http://otrolado.info). Watch it online [here](http://softwarelibre.github.io/stockfish.reveal) or go to the setup to watch it offline.

Powered by [reveal](https://github.com/hakimel/reveal.js).

## Setup

1. Clone the repo

 ```sh
 $ git clone https://github.com/SoftwareLibre/stockfish.reveal.git
 $ git checkout gh-pages
 ```
note that the it has the following folder structure (Refer to the [reveal folder structure](https://github.com/hakimel/reveal.js#folder-structure) for more details):

    |-- css/
    |-- js/
    |-- plugin/
    |-- lib/
    |-- fig/
    |-- source.md

The file `source.md` together with the folder `fig` hold the presentation contents.

External markdown and speaker notes, require that presentations run from a local web server. The remaining instructions will set up such a server as well as all of the development tasks needed to make edits to the slides source code.

2. Install [Node.js](http://nodejs.org/)

3. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Navigate to the presentation folder

 ```sh
 $ cd stockfish.reveal
 ```

5. Install dependencies

 ```sh
 $ npm install
 ```

6. Edit the presentation contents using [markdown](http://en.wikipedia.org/wiki/Markdown) in the `source.md` and adding figures as needed to the `fig/` folder.

7. Serve the presentation and monitor source files for changes

 ```sh
 $ grunt serve
 ```

8. Open <http://localhost:8000> to view your presentation

 You can change the port by using `grunt serve --port 8001`.
