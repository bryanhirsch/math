# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a plain-data repository containing arithmetic equations in text files. There is no code, build system, or test suite.

## Structure

- `sums/` — Addition equations (e.g., `0+1=1`). Files are numbered starting at 1.
- `differences/` — Subtraction equations (e.g., `2-1=1`). Files are numbered starting at 0.

Each text file contains one equation per line. Files within a directory share the same result value (e.g., `differences/0.txt` contains equations that all equal 0, `sums/2.txt` contains equations that all equal 2).

## Conventions

- File names are the result value of all equations in that file (e.g., `sums/2.txt` has sums equaling 2).
- Equations use the format `A+B=C` or `A-B=C` with no spaces.
- Each file ends with a trailing newline.
