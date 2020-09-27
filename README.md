# md2roff

This application converts markdown to Unix `man` pages.

Copied from [github/hub](https://github.com/github/hub/tree/31b6443687b3a0313000f8044bffbbed0a8a9b97)
because of this [Issue](https://github.com/github/hub/issues/2610).

The only changes were to how CLI flags get parsed in `main()` and bringing in the correct version of `blackfriday`.
