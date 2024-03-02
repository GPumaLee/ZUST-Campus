# ZUST-Campus

All the sensor measurements in the two experiments and the LiDAR SLAM results are stored in two directories, Experiment No.1 and Experiment No.2, respectively. Both directories contain the same subdirectories, as shown in Figure 8. The specific contents of these subdirectories are summarized as follows:

(1)Velodyne: The point cloud data obtained from Velodyne VLP-16 are stored in two formats, the BAG file and the PCD file. When running point cloud data using ROS, the reader can use the BAG files. For visualizing point clouds using the MATLAB code provided, the PCD files are recommended.

(2)Ground Truth: According to the storage format used in [14], the ground truth data are stored in the TXT files in TUM format. We provide the trajectory sample file to facilitate readers to view the length of the ground truth and the position in the satellite map.

(3)IMU: The IMU measurements are stored in the BAG files. The calibration results are stored in the TXT file in the following format.

(4)EVO Result: The evaluation results of the three LiDAR SLAM algorithms. The JPG files display the outputted mapping results and the trajectories of SLAM methods. The APE/RPE result files hold the evaluation results of the LiDAR SLAM method.

(5)Video: The process of collecting data is recorded in an MP4 format video file.