# Zoom Privacy Demo
## Video conference demo 1 (NBC SNL Video)
#### This is a multi-participant online video conference with a host and multiple participants. This video covers switching between grid view and speaker view, shared screen view, multiple people taking turns to speak and speaking at the same time, and using virtual backgrounds and real backgrounds. It also covers some unusual scenarios such as a participant turned off the camera to show predefined avatar photos, a participant hand-held the camera and kept walking, and multiple participants showed exaggerated facial expressions. 
#### Here we assume that except for the host user, all others are privacy-sensitive users, so we need to protect their faces and voice. Our system uses the white list mode.
#### [Original video download](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo1/original.mp4 "Original video")
#### The result after processing by our system.
#### [Result video](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo1/one_white_list_protection_result.mp4 "Result video") (Demo1-before-patching)
#### As can be seen in our resulted demo (Demo1-before-patching), our system protected almost all the sensitive faces perfectly except in a very short moment (in a few frames at the 24th second) one participant turned her face around 90 degree to the left, which caused the face detection algorithm to fail. We then used our semi-automated system to patch it (please see the result in Demo1-after-patching).
#### [After patching](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo1/face_patch_at_25s.mp4 "After patching") (Demo1-after-patching)
## Video conference demo 2
#### Here we assume that except for the host user, all others are privacy-sensitive users, so we need to protect their faces and voice. Our system uses the white list mode.
#### [Original video download](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo2/original.mp4 "Original video")
#### The result after processing by our system (One user in the white list).
#### [Result video](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo2/one_white_list_protection_result.mp4 "Result video")
#### The result after processing by our system (Two users in the white list).
#### [Result video](https://raw.githubusercontent.com/paperdemo888/zoom_privacy/master/demo2/two_white_list_protection_result.mp4 "Result video")
