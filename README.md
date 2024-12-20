# Siamese-mViT-FaceRecognition
Siamese-mViT-FaceRecognition is a lightweight face verification model designed for edge devices with limited resources. The model integrates a MobileViT block within a Siamese architecture to efficiently perform face verification tasks. It achieves impressive accuracy (93.12%) while maintaining a small parameter count (1.3M), making it suitable for real-world applications such as security, wearables, and IoT devices, even under constrained data and computational conditions.

## Dataset: Cross-modal Face-Periocular Dataset
The model is trained and evaluated using the **Cross-modal Face-Periocular Dataset**, which contains images of faces and ocular regions (eyes) across 2,239 identities from seven geographic regions. The dataset is available on [Kaggle](https://www.kaggle.com/datasets/leslietiong/cmfpdb).

## Requirements
- Google Colab (for running the notebook)
- Kaggle API (for downloading the dataset)
- Python libraries: `tensorflow`, `numpy`, `matplotlib`, `kaggle`, etc.

## How to Run the Code

1. **Clone the repository**:
   To get started, clone the repository to your local machine or use it directly on Google Colab.

   ```bash
   git clone https://github.com/Kanchon-Gharami/Siamese-mViT-FaceRecognition.git
   ```

2. **Prepare Kaggle API Key:**
   The model requires the Cross-modal Face-Periocular Dataset, which can be downloaded from Kaggle. You need to provide your Kaggle API key (kaggle.json) for this.
   - Visit [Kaggle](https://www.kaggle.com) and log in to your account.
   - After logging in, go to your **Account** page by clicking on your profile icon at the top-right corner, then select **My Account**.
   - Scroll down to the **API** section and click on **Create New API Token**. This will automatically download a file called `kaggle.json` to your local machine.
   - Upload the kaggle.json file to your Google Colab environment.
     
3. **Run the Jupyter Notebook:**
   Open the `Siamese_mViT_Face_Recognition.ipynb` file in Google Colab or Jupyter Notebook and execute the cells to train and evaluate the model.
  
## Contact
For any questions or inquiries, feel free to reach out to me at:

**Email**: kanchon2199@gmail.com, ghramik@my.erau.edu

## Citation
If you use this code or dataset in your research, please cite this repository.



   
   
