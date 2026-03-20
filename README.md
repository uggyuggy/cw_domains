# .cw domain names



## 🎯 Purpose

This repository purpose is to daily share the list of `.cw` domain names.

## 📰 Informations

- Data retrieved by DNSSEC zone walking.
- Extract does contains few SLD too (`.com.cw.`, `.net.cw.` `.edu.cw.`)
- Raw extract appears to also contains also some old glues of old domain names. Those glues are removed of the extract ( should not appear into the provided file).
- The file served here should be updated 1 time per day.
- The file contains an additional comment line at the top starting with `#` that contain an UTC date information.
- For now there is a single comment line, but in case I add more in the future, you may better remove everything that start with a `#`.
- The domain names are provided sorted ( `LC_ALL=C sort -u`).
- Background of why this repo, see https://github.com/monoidic/TLDR2/issues/3
- List is supposed to be available on https://www.uoc.cw/domain-registration/cw-registered-domains  but this does not look accurate (in addition to be monthly updated only). For example only 9 domains starting with a number on that web list, vs 273 found by zonewalking. (Even if those domains starting with `7` are strange).

