# Deep-learning-for-autonomouse-driving_Lane-segmentation-and-Steering-angle-prediction

1. lane_steering_angle_v2: Training SullyChen dataset after Lane Segmentation model of LaneNet and Cascaded CNNs
2. aug_lane_steering_angle_v2: Training SullyChen dataset with Cascaded CNNs instance segmentation with angle redistribution
3. part1_result_vis: visulisation of model loss, and sample prediction of image
4. part2_result_vis: visulisation of prediction of image according ot different division of angle range and comparison between model trained by original image, binary segmentation image from Cascaded CNNs, instance segmentaion image from Cascaded CNNs, binary segmentation image from LaneNet and instance segmentaion image from LaneNet
5. part3_result_vis: Visualisation of MSE and predicted angle of photo after angle redistribution, compare them with above five models.

Reference of model and dataset:
1. https://github.com/MaybeShewill-CV/lanenet-lane-detection
2. https://github.com/fabvio/Cascade-LD
3. https://developer.nvidia.com/blog/deep-learning-self-driving-cars/
4. https://github.com/SullyChen/driving-datasets
5. https://github.com/TuSimple/tusimple-benchmark/issues/3

