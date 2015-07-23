# Exercise 2: Make is your Python (Ruby) Now
C requires you to compile your source files
    - manually stitch them together into a binary that can run onits own
    - this is a pain! use `make`

### GNU Make
we'll be using this to build all our C code, run tests, handle things Python interpreter did for you
There is a smarter way to use makefiles, but that'll be later on

### Using Make
First Stage: use it to build programs it already knows how to build
    - Make has decades of knowledge built in
    ```bash
    $ make ex1
    # or:
    $ CFLAGS="-Wall" make ex1
    ```
    - Does the file `ex1` exist?
        - No
    - OK, is there another file that STARTS with `ex1`?
        - yes: `ex1.c`
    - Do I know how to build `*.c` files?
        - Yes!
    - Run: `cc ex1.c -o ex1`
    - Summary: I shall make you one `ex1` by using `cc` to build it from `ex1.c`
re: CFLAGS - passing in an environment variable as a modifier on the make process
    `CFLAGS="-Wall" make ex1` passes the cmd line option `-Wall` to the `cc` cmd that `make` normally runs
    `-Wall` says 'report ALL warnings' (apparently that's not all of them though)

