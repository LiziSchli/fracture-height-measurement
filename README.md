# Fracture Height Measurement from Sample Images

This project provides a semi-automated Python workflow for measuring fracture height from sample images.

## Motivation

In fatigue testing, fracture location is important for linking the fracture origin to CT and SEM observations. Manual measurement is slow and inconsistent, especially for large sample sets.

## What this workflow does

- Calibrates image scale using a known ruler length
- Corrects image rotation using a reference line
- Allows the user to mark sample regions
- Measures fracture height in pixels and millimetres
- Exports results to CSV
- Saves an annotated image for checking

## Tools used

Python, OpenCV, NumPy, pandas

## Example output

The workflow exports a CSV file containing sample ID, pixel height, and measured fracture height in mm.

## Status

This is an early research workflow developed for fatigue sample image analysis.
