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
- pip

### **Setup**
Clone the repository and install dependencies:
```bash
git clone https://github.com/Sudhanshu1304/table-transformer.git
cd table-transformer
pip install -r requirements.txt
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