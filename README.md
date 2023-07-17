# Fourier-Transform
This assignment involves generating a signal of the given form, and visualizing it in the time and frequency domain. I will be computing the Fourier Transform of the signal and observing the retrieved frequencies. Additionally, I will be applying the inverse Fourier Transform to the signal and comparing it with the original signal. 


## Introduction
Fourier Transform is a mathematical technique used to decompose a signal into its individual frequency components. It is widely used in various fields such as signal processing, communication systems, and image processing. In this assignment, we will be working with regularly sampled data and using the Fourier Transform to retrieve the signal characteristics.

## Task
I decided to make a signal of:


$y = \sin(a \pi t)+B \sin(b \pi t)$

with $a < 1$, $b>1$ and $B > 1$.

## Methods
First I define all the necessary functions. These are the signal function y, Descrete Fourier Transform (DFT), DFT_plot, reconstruction, and k_array. The last one is used for the analysis of changing the behaviour of the sampled data with varying k value.

1) Visualizing signal:

   
![image](https://github.com/leilaakisheva/Fourier-Transform/assets/128895782/292ce9f8-0ebe-414e-be86-95fb688b8146)


2) Computing the Fourier Transform and visualizing the result in the frequency domain.

   
![image](https://github.com/leilaakisheva/Fourier-Transform/assets/128895782/eab8f560-bad0-461f-981d-66aaff89a737)


3) Applying the inverse Fourier Transforming and visualizing the result. Comparing to the original signal $y$.


![image](https://github.com/leilaakisheva/Fourier-Transform/assets/128895782/26e90020-0b36-49e9-895a-dce76aacc3f7)


4) Regularly sampling original signal by taking each $k$-th element. Performing tasks 1)-3) and vary $k$ starting from k = 2.

    
![image](https://github.com/leilaakisheva/Fourier-Transform/assets/128895782/2862f3c1-cc14-45e7-a539-6e3c1b57bbaf)
![image](https://github.com/leilaakisheva/Fourier-Transform/assets/128895782/7d276e49-9e29-487c-979a-d834c86b426d)
![image](https://github.com/leilaakisheva/Fourier-Transform/assets/128895782/597073a0-3850-4388-b8bc-70274df38ce7)
![image](https://github.com/leilaakisheva/Fourier-Transform/assets/128895782/94cdbedc-d7d5-4c8d-a1d7-9da8135fef5c)


## Results
As it can be seen reconstruction of the signal from the Inverse Fourier Transform and the original signal are the same. In the D part it can be seen that as k value increases number of sampled data decreases and so accuracy is also decreasing.

## Conclusion
In this assignment, I generated a signal of the form y = sin(aπt) + Bsin(bπt) with a<1, b>1, and B>1, and visualized it in the time and frequency domain. I computed the Fourier Transform of the signal and observed the retrieved frequencies, and applied the inverse Fourier Transform to the signal and compared it with the original signal. I also regularly sampled the original signal and varied k to observe its effects on the retrieved frequencies.

From the results, I observed that the reconstruction of the signal from the inverse Fourier Transform and the original signal were the same, indicating the effectiveness of the Fourier Transform in retrieving signal characteristics. I also observed that as k value increased in the regularly sampled data, the number of sampled data decreased, and the accuracy of the retrieved frequencies decreased accordingly.

Overall, this assignment provided valuable insights into the application of the Fourier Transform in signal processing and its limitations in regularly sampled data.
