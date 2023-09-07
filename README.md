# Person-Recognition-using-Periocular-Region

The periocular region refers to the area around the eye that may include eyebrows, eyelashes, eyelids, shape of the eye, height, texture of the skin, eye width, etc. It is considered that only these features are accessible due to occlusions in the input image. The model aims to work with and provide optimum results with the minimal feature information available and perform recognition.

1.Download the Code and uplopad to google drive
2.Add photos of each subject in respective folders and add it to trainset and similarly validation photos of each subject in their respective folders in the valset.
3.In UI.ipynb, change the people_in_db dictionary on line 49 2nd cell, to "foldername: subject name" key-value pairs in the same fashion as existing.
4.Create empty folders with respective subject folder names for all subjects in augment set, if augmentation needed. In this case also run the augmentation function.
5.Create empty folder with respective subject folder names for all subjects consisting of two other empty folders called left and right respectively for each and every subject. This must be added to clahe set and roi set.
6.Then open the UI.ipynb in the google colab and run similar to the previous case.
7.Test images must be added to the testset folder within the dataset1 folder.

![Screenshot_2023-09-07-16-53-05-70_e2d5b3f32b79de1d45acd1fad96fbb0f](https://github.com/rutujabhutaki/Person-Recognition-using-Periocular-Region/assets/97386325/2cdd0db0-6736-48a9-8e28-c8c8c73f540c)

OUTPUT:

![2](https://github.com/rutujabhutaki/Person-Recognition-using-Periocular-Region/assets/97386325/9827e99c-5a3c-464b-82cb-6f2b563ed064)

![3](https://github.com/rutujabhutaki/Person-Recognition-using-Periocular-Region/assets/97386325/c6e15f0a-2995-4170-9bd7-f44249486d9e)

![WhatsApp Image 2023-05-04 at 19 49 39](https://github.com/rutujabhutaki/Person-Recognition-using-Periocular-Region/assets/97386325/1508470b-1638-4a7c-a1ff-6287f1d1211b)
