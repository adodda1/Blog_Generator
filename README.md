# 📝 Blog Generation App with LLaMA 2
This is a **Streamlit app** that generates blogs based on a topic, word count, and target audience. It uses a locally running **LLaMA 2 model** via `CTransformers` to create high-quality blog content tailored to your selected profile.

---

## 🚀 How It Works

1. Enter a blog topic.
2. Choose the number of words.
3. Select the intended audience (e.g., Researchers, Data Scientists, Common People).
4. Click **Generate** to create a blog post using the LLaMA 2 model.

---

## 🛠 Tech Stack

- [Streamlit](https://streamlit.io/)
- [LangChain](https://www.langchain.com/)
- [CTransformers](https://github.com/marella/ctransformers) (for running LLaMA 2 locally)

---

## 📦 Installation

### 1. Clone the Repository

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Add the LLaMA 2 Model
Download your llama-2-7b-chat.ggmlv3.q8_0.bin model file and place it in a folder named models in the project directory.

⚠️ You need to manually download the model from authorized sources (e.g., Hugging Face) after accepting Meta's license.

### 4. Run the App
```bash
streamlit run app.py
```
✨ Features
Generate blogs with custom word length

Choose between different audience styles

Uses LLaMA 2 locally for privacy and speed

🙌 Acknowledgments
Meta AI for LLaMA 2
