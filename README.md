# Team Desidecibels - Indian Sign Language Translator

## **Overview**

Team **Desidecibels** presents an innovative **Machine Learning (ML) model** that provides **real-time, bidirectional translation** between multiple **Indian dialects** and **Indian Sign Language (ISL)**. Our solution bridges the communication gap for people with speech and hearing impairments across India, enabling seamless interaction regardless of their spoken language.

While similar solutions exist for **American Sign Language (ASL)**, our platform is designed exclusively for **Indian Sign Language**, incorporating the nuances of multiple Indian languages. Special care has been taken to ensure that **context is preserved** during communication.

---

## **Features**

* **Bidirectional Translation**:

  * Converts spoken or textual input in multiple Indian languages to Indian Sign Language.
  * Translates Indian Sign Language gestures into textual output in Indian languages.

* **Real-Time Processing**:

  * Ensures fast and efficient translation for seamless communication.

* **Indian-Centric Dataset**:

  * Built on a dataset exclusive to Indian Sign Language.
  * Accommodates linguistic and cultural diversity in India.

* **Context-Aware Translation**:

  * Designed to maintain context and meaning during the translation process.

---

## **Technologies Used**

* **Machine Learning**:

  * Real-time gesture recognition and language translation.
* **Dataset**:

  * Custom-built dataset tailored for Indian Sign Language and multiple Indian dialects.
* **Programming Languages and Frameworks**:

  * Python, TensorFlow/Keras, OpenCV, Streamlit.
* **Audio and Video Processing**:

  * Pyaudio, Mediapipe, ImageIO.

---

## **How It Works**

1. **Input**:

   * **Voice/Text to ISL**:

     * Input text or speech in an Indian language.
     * The system converts it into Indian Sign Language gestures.
   * **ISL to Voice/Text**:

     * Capture Indian Sign Language gestures via webcam.
     * The system translates them into textual output in the selected Indian language.

2. **Processing**:

   * The ML model identifies and processes the input using the custom Indian Sign Language dataset.

3. **Output**:

   * Display or playback of translated gestures or text.

---

## **Installation**

### **Prerequisites**

* Python 3.8 installed on your Windows system.
* Required dependencies listed in `requirements.txt`.

### **Steps**

1. **Clone the Repository**:

   ```cmd
   git clone https://github.com/your-repo-name/desidecibels-isl-translator.git
   cd desidecibels-isl-translator
   ```

2. **Set Up a Virtual Environment**:

   ```cmd
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install Dependencies**:

   ```cmd
   pip install -r requirements.txt
   ```

4. **Run the Application**:

   ```cmd
   streamlit run homepage.py
   ```
