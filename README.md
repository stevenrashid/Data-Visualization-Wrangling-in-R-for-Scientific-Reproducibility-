# Data Wrangling & Scientific Reproducibility

A small collection of Data Carpentries practice files exploring command-line tools for reproducible data work.

The repository name reflects a broader R and data-visualization learning topic. The files currently checked in are Bash exercises; no R scripts, datasets, or completed visualization notebooks are included.

## Repository contents

| File | Purpose |
| --- | --- |
| [middle.sh](middle.sh) | Prints a selected block of lines using `head` and `tail`. |
| [sorted.sh](sorted.sh) | Draft pipeline for sorting file line counts. |
| [process.sh](process.sh) | Saved, numbered shell-history commands from the exercise. |
| [adder.txt](adder.txt) | Small text file used in the practice material. |

## Run the line-selection exercise

Use Bash with the standard `head` and `tail` utilities, available on Linux, macOS, or Windows through WSL/Git Bash.

```bash
bash middle.sh path/to/input.txt 20 5
```

This prints the last five lines of the first twenty input lines: lines 16–20 when the input has at least twenty lines.

## Exercise notes

- `sorted.sh` currently begins with a stray pipe character. Its intended operation can be run directly as `wc -l file1.txt file2.txt | sort -n`.
- `process.sh` contains shell-history line numbers and is a record of commands, not a ready-to-run script.
- The `.pdb` files referenced in the command history are not included.

## Skills practiced

Shell pipelines, positional arguments, text processing, and documenting the steps needed to reproduce an analysis.
