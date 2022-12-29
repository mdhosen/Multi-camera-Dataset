# An Effective Multi-Camera Dataset and Hybrid Feature Matcher for Real-Time Video Stitching
This repository implement the code described in paper "An Effective Multi-Camera Dataset and Hybrid Feature Matcher for Real-Time Video Stitching"



Requirements:
you can create a virtual envionment and install the requirements.txt file. [Note: All of the packages are not necessary for this project]


# you can download multicamera dataset from here: https://drive.google.com/file/d/1cGhfrU9CPvjaGWFYQPggt4WNgwZlSox8/view

#Run code
To stitch multicamera videos (four), you just need to change your root directory and video file name.

For instance, if the folder name is videos and test1.avi, test2.avi, test3.avi and test4.avi are four video file.

rootDir ="videos/"     
stitcher = VideoStitcher(left_video_in_path= rootDir + "test1.avi",
                         right_video_in_path=rootDir + "test2.avi",
                         left_video_in_path2=rootDir + "test3.avi",
                         right_video_in_path2=rootDir + "test4.avi",
                         video_out_path=rootDir + "testResult.avi")

If you use the code or dataset, please cite our paper:
An Effective Multi-Camera Dataset and Hybrid Feature Matcher for Real-Time Video Stitching (https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9653352)

@inproceedings{hosen2021effective,
  title={An Effective Multi-Camera Dataset and Hybrid Feature Matcher for Real-Time Video Stitching},
  author={Hosen, Md Imran and Islam, Md Baharul and Sadeghzadeh, Arezoo},
  booktitle={2021 36th International Conference on Image and Vision Computing New Zealand (IVCNZ)},
  pages={1--6},
  year={2021},
  organization={IEEE}
}
