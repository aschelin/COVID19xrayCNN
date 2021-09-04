# COVID-19 x-ray CNN

<p align="center"><img src="https://specials-images.forbesimg.com/imageserve/5fc3d7e77159da32978948e1/960x0.jpg?cropX1=629&cropX2=4901&cropY1=0&cropY2=3264" width="40%"></p>

The use of artificial intelligence to assist medical teams in diagnosing diseases is becoming more common. In the COVID-19 pandemics, exams such as chest x-rays and ct-scans, are typically used to distinguish between normal and SARS-COV-2 virus infections. Compared to healthy cases, covid affected lungs display the so-called ground-glass opacities: lighter-colored, gray patches, rather than black regions, that appear on the radiography. 

While it is always important to rely on medical expertise for any decision-making, machine learning tools can add fast and reliable means to improve the process. 

Our work aims to contribute to this scenario, providing machine learning gears to help with the diagnostic. 

To train the CNN model, we used a publicly available dataset from [1-2]. The balanced set contained 3616 samples of each category. About 70% of them were used for training the NN and 30% for validation. 

This script is inspired by the material available on [3].
