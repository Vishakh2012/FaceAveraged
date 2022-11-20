# average-face
Algorithm for calculating average face from multiple images

To detect faces, face landmarks and save them to file run from https://github.com/tzutalin/dlib-android/blob/master/data/shape_predictor_68_face_landmarks.dat`

To run face averaging
- first run the face_landmark_detector.py after adding the path to the face predictor landmark and to the images folder
- then add the photos into the images folder, and delete the k.txt file from the images folder
- make sure that the photos are of the format jpg

- then run the face_average.py