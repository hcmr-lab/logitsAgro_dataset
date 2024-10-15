# logitsAgro_dataset

The [logitsAgro_dataset](https://github.com/wilgomoreira/logitsAgro_dataset) is a collection of logits specifically designed for training and testing deep learning models in the field of precision agriculture. It includes key parameters and configurations crucial for evaluating and deploying deep learning models in this domain.

What are included:

- **Model logits**: The data used in this study consists of logits obtained from the deep model (SegNet and DeepLabV3) during training and testing mode. These logits represent the unnormalized predictions (raw scores) before applying any activation function, such as sigmoid.
- **Original images**: The images originate from aerial multispectral imagery collected from three vineyards in central Portugal: Quinta de Baixo (QTA), ESAC, and Valdoeiro (VAL). Captured at a resolution of 240x240 pixels, these images were obtained using an unmanned aerial vehicle (UAV) equipped with an X7 RGB camera and a MicaSense Altum multispectral sensor. The dataset comprises RGB and near-infrared (NIR) bands, facilitating the calculation of vegetation indices such as NDVI and GNDVI. Ground-truth annotations for vine plants are included, enabling a thorough evaluation of the models. For more details, please refer to the dataset titled "DL Vineyard Segmentation Study," available at the following link: Cybonic, "DL Vineyard Segmentation Study," v1.0, GitHub, 2024. Available at: https://github.com/Cybonic/DL_vineyard_segmentation_study.
