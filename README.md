# Monte-Carlo-Simulations-on-an-Exponentially-Distributed-Random-Variable
To use MATLAB and Monte Carlo simulations to demonstrate that the exponentially distributed random variable X with parameter lambda = 0.2 has a valid probability density function, and to find its mean.

For X to be a valid probability density function, the following property must be satisfied. The integration over all values in the sample space should be equal to one.

![formula_rst](https://user-images.githubusercontent.com/74524978/170092916-5668a072-bf10-41a0-86c5-f1f32427cbc6.jpg)

After running the MATLAB code, the waveform attained is as follows. Being an exponential function, the value of area under the PDF plot should be equal to one, as shown.
![1a](https://user-images.githubusercontent.com/74524978/170093047-4befe29a-e457-462a-b0fc-9f89b067578a.png)

To find the mean of the random variable X, the MATLAB code is executed and the waveform attained is given below. It increases to a stable value of y=5 which is approximately equal to 1/𝜆. Thus, the given integral can be used to find the mean.
![1b](https://user-images.githubusercontent.com/74524978/170093312-b9c928eb-0213-4bc1-87e8-9ec08aed1bb0.png)

