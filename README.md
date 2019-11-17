#### Building from source.

* Install ANTLR version 4.
    I used `brew install antlr@4`
* Install antlr4 runtime.
    `pip install antlr4-python3-runtime`
* The package is built using wheel.
    `pip install wheel`

#### Building

* Checkout the repository.
* Edit the Makefile to configure PATHs.
    The antlr paths at the top in particular may need to change.
* *Do not run make*. Instead run `make pydist`.
