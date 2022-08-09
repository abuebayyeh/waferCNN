# waferCNN
In this notebook, we will build a simple CNN (shown in Figure below) to classify images of the WM-811k dataset. The images used are a mix of the original WM-811k and synthetic ones based on DCGAN ([see the link for the DCGAN code](https://github.com/abuebayyeh/waferDCGAN)).

![alt text](https://github.com/abuebayyeh/waferCNN/blob/main/images/cnnwm.PNG)

WM-811K is an open source dataset that include semiconductor wafer bin maps (WBM) collected from 46,393 lots in real-world semiconductor industries. These WBM contain multiple dies such that defective dies have logic 1 and normal dies are represented by logic 0. The properties included in the WM-811K dataset are waferMap, dieSize, lotName, waferIndex, trainTestLabel, and failureType. In total the data consists of 811,475 WBMs, 21.3% of the WBMs in the dataset have labels. Among labeled WBMs, 3.1% have failure patterns while 18.2\% do not have patterns. The failure patters are eight in total namely Centre, Donut, Edge-Loc, Edge-Ring, Loc, Near-Full, Random, and Scratch as shown in figure below. 

![alt text](https://github.com/abuebayyeh/waferCNN/blob/main/images/wm811k.PNG)

