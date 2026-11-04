# PrologHaskell

A Prolog interpreter in Haskell: a hand-written parser plus a solver with unification and backtracking. It loads a Prolog file and answers queries in a REPL (`;` for the next answer, `halt.` to quit).

## Run

```sh
runghc main.hs
```

Then enter a file name such as `math.pl` and a query such as `add(s(0), s(s(0)), X).`. On case-sensitive file systems, the module files must match their module names (e.g. `parser.hs` → `Parser.hs`).
