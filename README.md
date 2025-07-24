# Shipborne_data
This warehouse contains shipborne combined navigation experimental data and engineering files (4ANT/base/GNSSins/posmv), which support the verification of multi-source fusion algorithms and the analysis of positioning accuracy.
# Detail
This warehouse contains the original data and supporting engineering files required for the shipborne combined navigation experiments, covering core directories such as `4ANT` (antenna-related data/configuration), `base` (reference station/baseline data), `GNSSins` (original/processed data of GNSS and inertial navigation), and `posmv` (positioning solution or post-processing module), which can be used for scenarios such as verification of multi-source fusion navigation algorithms and analysis of shipborne positioning accuracy.
# Data process
Data processing requires the use of Inertial Explorer for data transformation. Usually, GNSS data is converted into O files, while IMU data is converted into IMR files or TXT files.
