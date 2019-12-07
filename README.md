# README
This file contains the function ```quality_measures```, which for a given segmented file and the true segmentation calculates a variety of statistics. Notably, 
    Number Fusions:     How many times are multiple true cells predicted as a single cell?
    Number Splits:      How many times is a single true cell split into multiple predicted cell?
    Av. Overshoot:      How many pixels are wrongly predicted to belong to the cell on average
    Av. Undershoot:     How many pixels are wrongly predicted to not belong to the cell on average
    Av. true area:      Average area of cells of truth that are neither split nor fused
    Av. pred area:      Average area of predicted cells that are neither split nor fused
    Nb considered cells:Number of cells that are neither split nor fused
