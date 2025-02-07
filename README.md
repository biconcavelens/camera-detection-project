# camera detection project
 multiple human detection in footage using opencv and yolo. working on stitching multiple camera inputs to estimate human position.
 single_mediapipe : using mediapipe, only one person was able to be detected in a frame, to overcome this we had to use yolov8.
 multi_tensor : using posenet to try and recognise multiple people. this was a very laggy process and to reduce this we had to use a tflite model which reduced accuracy.
 multi_yolo_stable : using yolo v8, we detected the poses of each person and used cv to draw skeleton overlapping the video.
 id-system : prototype id system to id people and re-identify them if they go unrecognised for a few frames (wip)