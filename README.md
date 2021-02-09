# TensorFlow.js-Custom-Object-Detection
Create your own custom object detection model and deploy it on the browser using TensorFlow.js

## Steps:

1. Clone the repository on your local machine.
2. Upload your dataset on Google Drive in the following directory structure ONLY; to avoid any errors as the notebook is created which is compatible to this format.

   ```TFJS-Custom-Detection
   TFJS-Custom-Detection.zip
   |__ images (contains all training and validation *.jpg files)
   |__ annotations (contains all training and validation *.xml files)
   |__ train (contains only training *.jpg and *.xml files)
   |__ val (contains only validation *.jpg and *.xml files)
   ```
   
3. Sign in to your Google account and upload the `Custom_Object_Detection_using_TensorFlow_js.ipynb` notebook on Colab.
4. Run the notebook cells one-by-one by following the instructions.
5. Once the TFJS model is downloaded, copy the `model_web` folder inside `TensorFlow.js-Custom-Object-Detection/React_Web_App/public` directory.
6. Run the following commands:
   - `cd TensorFlow.js-Custom-Object-Detection/React_Web_App`
   - `npm install`
   - `npm start`
7. Open `localhost:3000` on your web browser and test the model for yourself.

![GitHub Logo](/images/output.png)
Format: ![Alt Text](url)


