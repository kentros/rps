# rps

Simple Rock Paper Scissors game written in Clojure

## Build / Usage

This is played on the terminal, so if you run it with Leiningen, use trampoline run:

    $ lein trampoline run

Or, alternatively, package it into a jar and run it with java:

    $ lein uberjar
    $ java -jar ./target/rps-*.jar

## Options

Use keys R, P, and S to pick your weapon.  Any other key will exit.

## Example Output

    (R)ock, (P)aper, (S)cissors?
    Your paper defeats computer's rock. YOU WIN!
    
    (R)ock, (P)aper, (S)cissors?
    Computer's paper defeats your rock. YOU LOSE!
    
    (R)ock, (P)aper, (S)cissors?
    We both picked scissors. DRAW!


