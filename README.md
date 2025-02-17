NOTE: In case you are not able to view the ipynb files on github, then paste its link on nbviewer,
https://nbviewer.jupyter.org/

# Image-Denoising-using-Deep-Learning

In this repo I have implemented three different deep learning architectures for image denoising,<br>
REDNet; https://arxiv.org/pdf/1606.08921.pdf <br>
Multi-level Wavelet CNN (MWCNN); https://arxiv.org/pdf/1805.07071.pdf <br>
PRIDNet; https://arxiv.org/pdf/1908.00273.pdf <br>

I found that PRIDNet was giving the best results as compared to the other two, giving me the best PSNR and SSIM scores along with best visualizations which were very close to the ground truth images. <br>

![Screenshot](Results/Result_scores.png)

## PRIDNet Results

![Screenshot](Results/PRIDNet_Prediction_2.png)
![Screenshot](Results/PRIDNet_Prediction_1.png)
![Screenshot](Results/PRIDNet_Prediction_3.png)
Notice the level of detail in the eye ball.
