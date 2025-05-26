# 🌐 CodeCraft Studio & 🎨 LogoLab AI

[🔗 Visit the Website](https://bhaskar2603.github.io/SDP/)

This project is a dual-interface AI-powered platform that assists users in:
1. Generating **Full-Stack Website Code** from prompts (CodeCraft Studio)
2. Creating **High-Quality Logo Designs** using generative AI (LogoLab AI)

The project leverages two powerful AI models integrated into user-friendly interfaces with the goal of helping developers and startups build websites and brand identities from scratch with minimal effort.

---

## ⚙️ CodeCraft Studio – AI Full-Stack Website Generator

**CodeCraft Studio** is built using the open-source [Qwen 2.5 Coding Instruct](https://huggingface.co/spaces/Bhaskar2611/Code_Generater_best) model, a powerful instruction-tuned language model specialized in code generation. Compared to other coding LLMs, Qwen 2.5 performs better at generating full-fledged HTML, CSS, JS, and even backend templates from a single prompt.

### 🧠 How it works:
- Uses a **prompt template** specifically designed to elicit full-stack website code.
- Accepts user inputs like *"Create a portfolio website with dark theme and navbar"*, and generates the entire codebase (HTML/CSS/JS).
- Returns results in an easily copyable and previewable format.
- Model Link: [Qwen 2.5 Code Generator](https://huggingface.co/spaces/Bhaskar2611/Code_Generater_best)

---

## 🎨 LogoLab AI – AI Logo Generator

**LogoLab AI** was initially built using a **LoRA-trained Flux model**, specifically fine-tuned on a large set of brand logos to generate clean and stylistic logo outputs. However, the base model used for that version is currently unavailable on Hugging Face.

🚨 **Update**: To overcome this, the platform now uses the [FLUX-Pro-Unlimited](https://huggingface.co/spaces/NihalGazi/FLUX-Pro-Unlimited) model, which supports **unlimited logo generation** and maintains high image quality and design diversity.

### 🧠 Features:
- Accepts prompts like *"Minimal logo for a tech startup with blue tones"*
- Returns high-resolution, stylized logo options
- Works well for branding, pitch decks, and design mockups

Model Link: [FLUX-Pro Unlimited](https://huggingface.co/spaces/NihalGazi/FLUX-Pro-Unlimited)

---

## 🔧 Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: None (Hugging Face Spaces API integrations)
- Models: Hugging Face Hosted
- Deployment: GitHub Pages

---

## 👨‍💻 Author

**Jyothula Bhaskar**  
B.Tech in Computer Science & Engineering (AI & ML)  
[LinkedIn](https://www.linkedin.com/in/bhaskar-jyothula-974bbb271/) | [Hugging Face](https://huggingface.co/Bhaskar2611) | [GitHub](https://github.com/Bhaskar2603) | [Kaggle](https://www.kaggle.com/bhaskarjyothula)

---

## 🙏 Acknowledgements

- Thanks to the **Hugging Face** open-source community for providing these powerful models.
- Special mention to **Qwen** and **Flux** model developers.
- UI inspired by various open-source design kits and prompt engineering best practices.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
