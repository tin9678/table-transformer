# **Table Extraction Tool: OCR & Computer Vision for Structured Data**

## **Overview**
An advanced tool for extracting structured tabular data from images using computer vision and OCR techniques, specifically designed to enhance Large Language Model (LLM) data processing capabilities.

## **Features**
- 📊 Automatic table detection in images.
- 📝 OCR-based document processing.
- 🧠 Integration of OCR and table detection models to create a linked list.
- 💾 Export structured data as a DataFrame, HTML table, CSV, etc.

---

## **Tool Overview**

<div align="center">

<!-- First Row -->
<img src="images/image1.png" alt="Image upload" width="45%" style="margin: 10px;">
<img src="images/image2.png" alt="Table detection & extraction" width="45%" style="margin: 10px;">

<!-- Second Row -->
<img src="images/image3.png" alt="Table in HTML format" width="45%" style="margin: 10px;">
<img src="images/image4.png" alt="Table exported as CSV" width="45%" style="margin: 10px;">

</div>

---

## **Open-Source Tools Used**
- **[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)**: For text extraction.
- **[Hugging Face Table Detection](https://huggingface.co/foduucom/table-detection-and-extraction)**: For table structure detection.

---

## **Installation**

### **Prerequisites**
- Python 3.8+
- Conda

### **Setup**

1. **Clone the Repository**

   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Sudhanshu1304/table-transformer.git
   cd table-transformer
   ```

2. **Create and Activate Conda Environment**

   Create a new conda environment and activate it:

   ```bash
   conda create --name myenv python=3.12.7
   conda activate myenv
   ```

3. **Install PaddlePaddle**

   Install PaddlePaddle in the conda environment:

   ```bash
   python -m pip install paddlepaddle==3.0.0rc1 -i https://www.paddlepaddle.org.cn/packages/stable/cpu/
   ```

4. **Install PaddleOCR**

   Install PaddleOCR:

   ```bash
   pip install paddleocr
   ```

5. **Install Additional Dependencies**

   Install other required packages:

   ```bash
   pip install ultralytics==8.3.75 pandas==2.2.3
   pip install streamlit==1.41.1
   ```

### **Project Structure**
```
project/
├── src/
│   ├── streamlit_app.py       # Streamlit application
│   ├── table_creator/
│   │   └── processing.py      # Core processing logic
│   ├── models/
│   │   └── text.py            # table detection and text recognition
│
├── requirements.txt           # Dependencies
├── README.md                  # Project documentation
└── .gitignore                 # Git ignore configuration
```

### **Usage**
Run the Streamlit app to interact with the tool:

```bash
streamlit run src/streamlit_app.py
```

### **Contributions**
Contributions are welcome! Please fork the repository and submit a pull request with your improvements or new features.

### **License**
This project is licensed under the MIT License.
