# LNFormer
EGA-Net
EGA-Net: Edge Feature Enhancement and Global Information Attention Network for RGB-D Salient Object Detection

Attention!!!
It is recommended to reproduce our code in the Linux system.

If you want to run the test.py in Windows, please make sure that the path where you save the test results exists.

Experimental environment
python==3.7.0

pytorch==1.8.0

torchvision==0.9.0

tensorboardX==2.5

opencv-python==4.5.5.64

Training
If you want to retrain our network, we recommend that you follow these steps.

Complete the experimental environment setup as described above.

Modify the parameters in train.py according to your computer configuration, such as gpu, batchsize.

Download the dataset and place it in the data folder [code:0617]https://pan.baidu.com/s/10g1can5GKMoO5Vm238aFEw.

Download the pre-trained model of Resnet-50 and place it in the model_zoo folder [code:0617]https://pan.baidu.com/s/1QMhpxyenTbiBFIhPbezU4g.

Open terminal. run：python3 train.py

Testing
If you would like to reproduce our results, please follow these steps.

We provide a link to download the parameters of the trained model [code:0617]https://pan.baidu.com/s/1ZsddhG5dm6PHByvzaUSS0w.

Place the parametric model under the './best/modal/' path.

Open terminal. run：python3 test.py

We also provide links to download the results of our experiments [code:0617]https://pan.baidu.com/s/1RnS6BDDAg4tGOxEnNGXLrQ.

Evaluation
If you would like to evaluate our entire model parameters through quantitative metrics, please follow these steps.

Download the results of our experiments and place them in any path.

The evaluation metric code has been placed in the eval_code folder, please use MATLAB to open it.

Modify the path to the dataset in main.m.

run main.m.
