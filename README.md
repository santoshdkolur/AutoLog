# AutoLog

Project for automatically reading people's faces and to recognise them the next time they walk in.

We have used the face_recognition python library created by Adam Geitgey. The library helps us to create face encoding and to find or recognise a person using images.

OpenCV is used to read the frames from the video camera which is then taken as an input for creating face encoding to new faces.
The created encodings are added to a list of know_faces. Known_faces list is used to check if the face details obtained from the frame is already store or not. The name given to the face is directly shown here.

Our implementation also involves mechanisms to make sure the face reading is read for a person once within a particular time. This is done to make sure that it is not considered as logout if at the face is detected twice.

##### More to be included.

