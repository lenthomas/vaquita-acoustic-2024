# vaquita-acoustic-2024

R code to generate survey design for acoustic survey of vaquita outside the zero tolerance area.

Main file is a Quarto file, containig the code, vaquita_acoustic_design.qmd  Note it takes a long time to run this file as the chunk containing the sampling process takes quite some time.  I have not pushed the cache but can share this if time is a problem.  The compiled file is vaquita_acoustic_design.pdf.  Results (proposed sample locations) are also exported to sample_locations.csv.  First two colums of that file are x, y locations in UTM11N projected coordinate system, while the last two columns are longitude and latitude using WGS1984 geographic coordinate system.
