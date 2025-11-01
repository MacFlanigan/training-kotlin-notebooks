# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Kotlin learning repository focused on Jupyter notebook tutorials. The repository contains educational content demonstrating Kotlin language features through interactive notebooks.

## Repository Structure

The repository uses Jupyter notebooks (.ipynb files) with Kotlin kernels to provide interactive Kotlin programming examples. Currently contains:

- `generiques-obj-ext.ipynb` - Tutorial covering Kotlin generics, singleton objects, and companion objects

## Working with Kotlin Notebooks

### Notebook Format

Notebooks contain a mix of:
- Markdown cells for explanatory text (in French)
- Kotlin code cells with executable examples
- Output cells showing execution results

### Key Kotlin Concepts Demonstrated

**Generics**: The notebooks show type-parameterized classes using syntax like `Question<T>` where `T` can be `String`, `Boolean`, `Int`, or other types.

**Singleton Objects**: Uses `object` keyword to create singleton instances (e.g., `object StudentProgress`).

**Companion Objects**: Demonstrates companion objects within classes for static-like members accessible via class name (e.g., `Quiz.answered`).

## Development Notes

- This is a notebook-based learning repository with no build system or test framework
- Content is in French
- Notebooks can be opened and executed in Jupyter environments with Kotlin kernel support
- No compilation or build commands are needed as notebooks are executed cell-by-cell interactively