# tictactoe

A simple tic tac toe written in Clojurescript. Using the Reagent library. 

This implementation is based on this youtube video: https://www.youtube.com/watch?v=pIiOgTwjbes 

## Setup

To get an interactive development environment run:

    lein figwheel

and open your browser at [localhost:3449](http://localhost:3449/).
This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. 


To clean all compiled files:

    lein clean

To create a production build run:

    lein do clean, cljsbuild once min

And open your browser in `resources/public/index.html`. You will not
get live reloading, nor a REPL. 

## License

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
