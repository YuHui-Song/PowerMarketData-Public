# DS-0024: RTS-GMLC v0.2.3, SourceData subset

These 17 files are an unedited copy of part of the NREL/GridMod RTS-GMLC repository. They are republished here under the data-use notice in the upstream README.

| Item | Value |
| --- | --- |
| Upstream | https://github.com/GridMod/RTS-GMLC, release v0.2.3, commit `3ece0d37` |
| Contents | `README.md`, `RTS-GMLC_updates.md`, `RTS_Data/README.md`, and the 14 data files under `RTS_Data/SourceData/` (R scripts not included) |
| Size | 17 files, 1,075,026 bytes |
| Approval | `PA-20261029-01` (file-by-file publication approval) |

## Licence notice

The upstream README grants the right "to use, copy, and distribute these Data for any purpose whatsoever, provided that this entire notice appears in all copies of the Data." The notice is reproduced in `v0.2.3/README.md`. If you redistribute these files:

1. Keep the entire notice with every copy. In the simplest case, copy `v0.2.3/README.md` along with the data.
2. Credit DOE/NREL/ALLIANCE when you publish results that use the data.
3. Do not use the names DOE, NREL or ALLIANCE to endorse or promote anything.

The notice is incomplete upstream. It stops at "…ARISES OUT OF OR IN". We have reproduced it exactly as published upstream and have not completed or altered it.

## Integrity

None of the files under `v0.2.3/` has been changed. `.gitattributes` turns off line-ending conversion for `datasets/`, so a fresh clone gives the same bytes. To check them:

```
cd datasets/DS-0024/v0.2.3
sha256sum -c ../SHA256SUMS
```

`files.json` lists each file's ID, path, size and SHA-256.
