# CS153-Final

Code used to assess similarity of hand reconstructions using root mean square error (RMSE), normalized by the number of hand pixels. Sample images to run the code on are provided in the Cropped_results folder.

<img width="393" alt="Screen Shot 2024-12-11 at 3 53 45 PM" src="https://github.com/user-attachments/assets/51fb1da1-4353-407b-a986-f3485c5ae939" />


## How to Use

1. Open image_comparison.ipynb
2. Run the image_difference function on any two images in the Cropped_Results folder by inputting the file paths as the two arguments.

Note that this function requires the two images to be of the same dimensions. For the most meaningful results, users should compare an image from the baseline subfolder with an image from any of the other subfolder. The images themselves should match, e.g. 

```
image_difference("/Cropped_Results/baseline/5", "/Cropped_Results/desaturation/5").
```

## Acknowledgements

Hand poses generated from ACR. Model and instructions found at https://github.com/ZhengdiYu/Arbitrary-Hands-3D-Reconstruction. We thank the authors of this work!
