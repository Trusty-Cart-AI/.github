# 🛒 Trusty Cart AI: Enhancing Online Shopping Security

## 📌 Overview  
**Trusty Cart AI** is a lightweight Chrome extension that empowers users to verify the authenticity of product reviews on e-commerce platforms. By combining image similarity detection and advanced natural language processing, the extension flags misleading or fake reviews in real-time—enhancing user trust and shopping safety.

---

## 🚀 Key Features  
- 🖼️ **Image Similarity Model**: Compares uploaded product images with user-shared images in reviews.  
- 💬 **Sentiment & AI Text Analysis**: Analyzes review tone and detects AI-generated or misleading comments.  
- 🧾 **Spam Review Detection**: Flags untrustworthy reviews in **RED**, and highlights genuine reviews in **GREEN**.  
- 🎯 **Fixed Similarity Threshold**: Uses a 60% image similarity score to validate visual authenticity.  
- 🎨 **CSS Injection**: Alters review styling on the e-commerce page using temporary DOM/CSS changes for clarity.  

---

## 💡 Motivation  
The growing prevalence of fake reviews on online shopping platforms misleads users and distorts product reputations. Trusty Cart AI was created to address this problem by giving shoppers a simple, automated way to verify reviews, ultimately promoting transparency and helping people make smarter buying decisions.

---

## ⚠️ Challenges  
- Efficiently performing resource-heavy tasks like image and text analysis in a browser environment.  
- Adapting to dynamic structures of modern e-commerce websites.  
- Ensuring fast and accurate results while minimizing resource usage.

---

## 🎯 Project Goals  
- ✅ Enhance the security and transparency of online shopping  
- ✅ Improve user confidence in product reviews  
- ✅ Seamless integration with major e-commerce sites  
- ✅ Detect misleading, AI-generated, or spammy reviews with high accuracy

---

## 🧰 Technology Stack  
- **Frontend**: Chrome Extension (HTML, CSS, JavaScript)  
- **Image Processing**: CNN-based model for similarity scoring  
- **Text Analysis**: Bi-LSTM or transformer models for sentiment and AI text detection  
- **Other**:  
  - Browser APIs  
  - CSS Injection  
  - Optional future backend for cloud-based processing

---

## 🛠️ Installation

Follow the steps below to install and run Trusty Cart AI locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/trusty-cart-ai.git
   cd trusty-cart-ai



Thank you for contributing to **Trusty Cart AI** and helping us make online shopping safer for everyone!
