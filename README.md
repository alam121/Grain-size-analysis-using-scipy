# Grain-size-analysis-using-scipy
This file includes image processing tasks required to generate grain analysis summary and to capture it in a csv file

This code performs grain size distribution analysis and dumps results into a csv file.

1. Read image and define pixel size (if needed to convert results into microns, not pixels) 
2. Denoising, if required and threshold image to separate grains from boundaries. 2
3. Clean up image, if needed (erode, etc.) and create a mask for grains
4. Label grains in the masked image
5. Measure the properties of each grain (object)
6. Output results into a csv file


## Orignal Image
![Orignal Image](https://github.com/alam121/Grain-size-analysis-using-scipy/blob/master/Orignal%20Image%20.png)

## Segmented Result
![Segmented Image](https://github.com/alam121/Grain-size-analysis-using-scipy/blob/master/Swgmented-Result.JPG)

