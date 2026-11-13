# epistasis 0.0.1.1.9001

Renova release, based on CRAN epistasis 0.0.1-1 (archived on CRAN 2023-08-11).

- `R/model.selection.R`: two `class(result) == "epi"` tests became `class(result)[1L] == "epi"`.
- `man/CviCol.Rd`: the literal genotype codes `{0, 1, 2}` are written as `\code{\{0, 1, 2\}}`; `man/episim.Rd`: `code{con.dist = "Mt"}` became `\code{con.dist = "Mt"}`; `man/epistasis-internal.Rd`: added the missing `\alias{epistasis-internal}`.
- `DESCRIPTION`: `Author: Pariya Behrouzi, Danny Arends and Ernst C. Wit` became an `Author` with roles and an equivalent `Authors@R` entry; the stale optional `Date: 2016-11-23` field was removed (metadata only).
- `DESCRIPTION`: `Version` set to `0.0.1.1.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was added and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
