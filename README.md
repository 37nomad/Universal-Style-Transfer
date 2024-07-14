# Universal Style Transfer
### Project Description
- Implemented Neural Style Transfer techniques to create visually compelling images by merging the content of one image with arbitrary artistic style of another. 
- Developed a Multi-level stylization approach using a pre-trained encoder-decoder architecture based on **VGG19**. 
- Incorporated feature transformation with alpha as the style weight parameter to precisely control the stylistic transfer effects. 
- Leveraged powerful techniques such as Adaptive Instance Normalization (**AdaIN**) and Whitening and Coloring transforms (**WCT**) within the feature transformation process for image reconstruction network.  
### Model Architecture   
![Model Architecture](https://github.com/37nomad/Universal-Style-Transfer/blob/main/multi%20level%20stylisation.png?raw=true)  
## Deployment

- To deploy this project run the following file : **3Adain-2WCT.ipynb**  
- Make sure the content Image , Style Image and Output Image paths are clearly mentioned in the notebook.

## Generated images 
- Example 1
<p align="center">
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Content%20Images/006.jpg?raw=true" alt="Content Image 1" width="300" />
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Style%20Images/sham-jallaludin-IPasTalwA4o-unsplash.jpg?raw=true" alt="Style Image 1" width="300" />
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Output%20Images/flower-3-AdaIn.png?raw=true" alt="Generated Image 1" width="300" />
</p>     

- Example 2
<p align="center">
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Content%20Images/05.jpg?raw=true" alt="Content Image 2" width="300" />
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Style%20Images/style_7.png?raw=true" alt="Style Image 2" width="300" />
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Output%20Images/bridge-3-AdaIn.png?raw=true" alt="Generated Image 2" width="300" />
</p>  
  
- Example 3  
<p align="center">
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Content%20Images/004.jpg?raw=true" alt="Content Image 3" width="300" />
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Style%20Images/in4.jpg?raw=true" alt="Style Image 3" width="300" height="300"/>
  <img src="https://github.com/37nomad/Universal-Style-Transfer/blob/main/Output%20Images/woman-3-AdaIn.png?raw=true" alt="Generated Image 3" width="300" />
</p>    
  
## Acknowledgements  
  
Below are some research papers which have been instrumental in doing this project :
 - [Neural Style Transfer: A Review](https://arxiv.org/pdf/1705.04058)
 - [Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization](https://arxiv.org/pdf/1703.06868)
 - [Universal Style Transfer via Feature Transforms](https://arxiv.org/pdf/1705.08086)
 - [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576)

   
## Support

If you found value in this project, please give it a star! Your support is greatly appreciated.



