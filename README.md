# Bash Scripts

> #### *My collection of user bash scripts*

------

## Paths

- **Repo / USB:** `\OS\Windows\Settings\Installed\Apps\Cmder\bin`
- **Mac:** `~/Scripts` & ``

------

## Create a new bash script

### With Template

Copy `bin/template` to a new file without an extension in this directory. 

### Without Template

Simply add the following to the top of a blank extension-less file in this directory.

```bash
#!/bin/bash
```

> **Note:** *Windows apparently doesn’t need to `chmod` scripts and will run anything…*

------

## Scripts

### Timestamps

#### ISO Timestamps

**Aliases:** `dt`, `ts`, `timestamp`

Outputs timestamps in the format: `2023-06-05 14:36:12`

#### File Name Timestamps

`fndt` & `fnts`

Outputs File name timestamps in the format: `2023-06-05-14-38-08`

