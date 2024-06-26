The aim of the project is to filter and stylise the global river network of a single country or an entire continent.

The visualisation of the river network can be based either on a single parameter or on a combination of them, e.g.:

1. An indicator of river order according to the Strahler ordering system: order 1 represents upstream streams; when two 1st order streams meet, they form a 2nd order river; when two 2nd order rivers meet, they form a 3rd order river; etc. 
2. A river order indicator according to the classical ordering system: order 1 represents the main river from source to source; order 2 represents all tributaries flowing into the 1st order river; order 3 represents all tributaries flowing into the 2nd order river; etc. This ordering system can be used to identify 'mainstem' rivers, i.e. the main stem of a river from source to discharge. 
3. A river order indicator using river discharge to distinguish dimensions: order 1 represents river sections with mean perennial discharge ≥ 100,000 m3/s; order 2 represents river sections with mean perennial discharge ≥ 10,000 m3/s and < 100,000 m3/s; .... order 9 represents river sections with mean perennial flow ≥ 0.001 m3/s and < 0.01 m3/s; and order 10 represents river sections with mean perennial flow < 0.001 m3/s (i.e. 0 in the reported data due to rounding to 3 digits).
4. An indication of the total area in the upstream reach, in square kilometres, calculated from the headwaters to the spill point (i.e. the lowest pixel) of the reach. The upstream area includes only the area directly associated with the catchment, i.e. it does not include endorectal regions that may be nested within the larger basin.

River line colours are the appropriate Matplotlib or Colorcet colour palette.
