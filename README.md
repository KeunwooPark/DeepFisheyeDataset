# DeepFisheye Dataset
Access point for the datasets of DeepFisheye project (UIST 2020).
Our work, **'DeepFisheye: Near-Surface Multi-Finger Tracking Technology Using Fisheye Camera'**, will be presented in UIST 2020.
If you want to know more about the project, please see the links below.

## Related Links
- [Project page](http://kwpark.io/deepfisheye)
- [Deep learning model](https://github.com/KAIST-HCIL/DeepFisheyeNet)

## DeepFisheye Synthetic Dataset

![synth_image_sample](synth_image_sample.png)

Synthetic dataset comprises fisheye color, depth images and 3D joint data. The images were collected from virtual environment, which is Unity. There are approximately 233,000 pairs of images and joint data. 
If you are interested in creating a fisheye camera in Unity, please see this [project](https://github.com/KeunwooPark/fisheye_mesh_generator).



### Download Link
- [Download](https://drive.google.com/file/d/1_6ouKI9XOyDXLCAlGkvPwQO_5BMDQkDz/view?usp=sharing)

## DeepFisheye Real Dataset
Real dataset comprises fisheye color images and 3D joint data. The images were captured from a machine vision camera (FLIR CM3-U3-13Y3C-CS) and joint data were collected with a Leap Motion device. We collected 42,000 images from four participants.

This dataset is just for fine-tunning a network. You have to use the synthetic dataset for basic training.

### Request Access
Please fill out the form if you want to download this dataset. You are required to write your email (Gmail account if possible) in the form. Then, we will send you a Google Drive link of the dataset. However, your access will be expired in 48 hours.
- [Form Link](https://forms.gle/6MqTGu41TL5X2sU29)

## Terms and Conditions
The download and use of any of the two datasets is released for academic research only and it is free to researchers from educational or research institutes for non-commercial purposes. When downloading the dataset you agree to (unless with expressed permission of the authors): not redistribute, modificate, or commercial usage of this dataset in any way or form, either partially or entirely.

If you use any of the two datasets or parts of them in your research, you must cite this paper.
```
@inproceedings{Park2020DeepFisheye,
  title = {DeepFisheye: Near-Surface Multi-Finger Tracking Technology Using Fisheye Camera},
  author = {Park, Keunwoo and Kim, Sunbum and Yoon, Youngwoo and Kim, Tae-Kyun and Lee, Geehyuk},
  booktitle = {Proceedings of the 33rd Annual ACM Symposium on User Interface Software and Technology},
  year = {2020},
  publisher = {Association for Computing Machinery},
  numpages = {15},
  series = {UIST '20}
}
```
