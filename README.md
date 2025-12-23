Problem statement:
On kaggle competition, cidaut-ai-fake-scene-classification-2024. The images are downloaded and its data is shown at the excel, during image idetification between fake and real image, some are mislabbelled. This is projected to affect the accuracy of the machine learning model produce.


To solve this problem, a python program is produced to find the closest image so a pair of images can be use for qualitative analysis.

The process in the jupyter notebook are as:
1. Names of the images are listed using OS Module library.
2. Use SSIM to find the closest similarity between 2 images.
3. Create a dataframe on the similarity result between the 2 images.
4. Separate the images in its own folder for qualitative analysis, as shown in image_separated folder.
