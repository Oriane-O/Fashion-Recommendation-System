# Fashion-Recommendation-System
This repository implements two fashion recommendation systems based on image features.

The first system uses deep visual features extracted with a pre-trained VGG16 model to find clothing items that are visually similar in terms of shapes, textures, and patterns.

The second system extends this approach by adding a weighted color histogram, allowing the model to prioritize items with similar color tones. This improves recommendation quality for fashion scenarios where color consistency is important.

This project is inspired by the article  
[“Fashion Recommendation System using Image Features”](https://amanxai.com/2024/02/05/fashion-recommendation-system-using-image-features/) by Aman Kharwal.

## Features
- System 1: VGG16-based visual similarity.  
- System 2: Combined features (VGG16 + color histogram) to emphasize color-matching recommendations.  
- Google Colab notebook implementation.

## How to use
1. Mount Google Drive and load your dataset of fashion images.  
2. Run the notebook to extract features for both systems.  
3. Provide the path of an input image to compare and retrieve top-N similar fashion items.

## License
Open-source under the MIT License.
