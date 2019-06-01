# Philippine-connectivity

These files contain data on Philippine coral reef connectivity as part of Patrick Pata's Thesis.

The folder Connectivity_XYZ_array_lists contains connectivity data in comma-separated format with each column representing:
- (1) source reef ID
- (2) sink reef ID
- (3) probability of connection

Each of the 36 data files are named according to larval type, simulation year, and simulation months i.e., "xyzlist _ [larvaltype] _ [year] _ [months].csv".

The location of the reef IDs are stored in the files PH_reef_centroids_3776.csv for centroids and PH_reef_polygons_3776.wkt for polygons.

The file "Reef_clusters_per_minimum_cluster_size.csv" contain the cluster number at each minimum cluster size (MCS) computed using the dynamic tree cut algorithm. The rows are sorted according to the ReefID. A value of 0 indicates that the reef was not included in any cluster for a particular MCS value.

For inquiries regarding the dataset please contact p.pata@oceans.ubc.ca.

LICENSE:

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
