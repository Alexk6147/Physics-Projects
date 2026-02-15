# Comet Centroid Stacking Pipeline

First attempt at imaging and reducing a moving comet.

## Problem
Because the telescope tracked the star field, the comet moved relative to the background stars across frames. Traditional star-aligned stacking would smear the comet.

## Method
1. Identify comet centroid in each FITS frame
2. Shift frames so comet is aligned to a common reference
3. Median combine to reduce noise

## Current Improvements
- Automating centroid detection
- Handling smeared star background
- Refining alignment accuracy
