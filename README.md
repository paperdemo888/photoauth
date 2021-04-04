# Zoom Privacy Demo
## Video conference demo 1
#### This is a multi-participant online video conference with a host and multiple participants. The video includes scenarios such as switching back and forth between grid view and speaker view, virtual backgrounds, and shared desktops.
#### The goal is that except for the host user, all others are privacy-sensitive users, we need to protect their faces and voices, the system uses the white list model, that is, the white list has only the host user‘s face information and voice information.
#### [Original video download](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo1/original.mp4 "Original video")
#### The result after processing by our system.
#### [Result video](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo1/one_white_list_protection_result.mp4 "Result video")
#### At the 25th second, due to the privacy-sensitive user's head twisting at too large an angle to recognize the face, we execute the patch system to protect the missed face.
#### [After patching](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo1/face_patch_at_25s.mp4 "After patching")
## Video conference demo 2
#### This is another online video conference with multiple participants, but the difference is that this video records the name tags of all participants in the conference.
#### The goal is to protect the name tag from leaking user privacy, we also use the white list model, and this time we will test the performance of the white list with different number of users.
#### [Original video download](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo2/original.mp4 "Original video")
#### The result after processing by our system (One user in the white list).
#### [Result video](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo2/one_white_list_protection_result.mp4 "Result video")
#### The result after processing by our system (Two users in the white list).
#### [Result video](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo2/two_white_list_protection_result.mp4 "Result video")
