<div align="center">

# Soham Nilesh Bacchuwar

**Applied ML · LLM fine-tuning · Full-stack**

I take a model from raw data to a deployed app, and I measure whether it actually works.

*I don't call a model "working" until a test says so, and I write down what the test can't see.*

<sub>Final-year B.Tech CSE, MNNIT Allahabad (graduating June 2027) · Open to internships now</sub>

<sub>[LinkedIn](https://www.linkedin.com/in/soham-bacchuwar-47a5b4296/) &nbsp;·&nbsp; [Hugging Face](https://huggingface.co/Sohamb2005) &nbsp;·&nbsp; sohambacchuwar@gmail.com</sub>

</div>

---

## Projects

**[Excusify](https://github.com/soham200521/Excusify)**: situation-aware excuse and apology generator, built on three GPT-2 models fine-tuned on ~1,400 situation-labelled examples.<br/>
I built a "situation match" test (held-out prompts plus 20 situations that aren't in the data) and used it to find a decoding bug: repetition penalties also penalise the prompt, so "late to the meeting" came back as "early to the gathering". Fixing it took excuse relevance from 31% to 100%. The test only checks that an answer is about the right situation, not that it makes sense, so the app also re-ranks 6 samples by model likelihood.<br/>
<sub>`Python` `PyTorch` `Transformers` `Streamlit` &nbsp;·&nbsp; [live demo](https://huggingface.co/spaces/Sohamb2005/excusify-app) &nbsp;·&nbsp; [models](https://huggingface.co/Sohamb2005) &nbsp;·&nbsp; perplexity 32.1 → 5.8</sub>

**[CredChain](https://github.com/sriramvarun0636/CredChain)**: credit scores for gig workers from alternative data, stored on-chain. Built in a team of four at Hack36.<br/>
A worker connects MetaMask and submits income, dues and documents; an admin verifies them, a random-forest model scores them, and the score is written to a Solidity contract on the Sepolia testnet. I built the React frontend: the wallet connection, the financial-details form with document uploads, and the score view that reads straight from the contract with ethers.js.<br/>
<sub>`React` `Tailwind CSS` `ethers.js` `Solidity` &nbsp;·&nbsp; [demo video](https://drive.google.com/drive/folders/1pDdWL6IcOdvwN1UJFaphEq6vsTtWHzrs?usp=drive_link) &nbsp;·&nbsp; team project</sub>

**[Sign-language recognition](https://github.com/ShubhamVadher/AIProject)**: real-time sign recognition from a webcam, built in a team of five.<br/>
MediaPipe Holistic turns each frame into 258 body and hand keypoints, a three-layer LSTM classifies 30-frame windows, and only predictions above 90% confidence reach the live caption. It recognises 6 signs and got all 9 held-out clips right, which is too small a test to quote as an accuracy.<br/>
<sub>`Python` `TensorFlow / Keras` `MediaPipe` `OpenCV`</sub>

## Currently building

**Hologram generation from 2D images**: an academic project to build a computational platform that generates high-quality holograms from ordinary 2D images, in Python. In progress; repository coming soon.

---

<div align="center">

**Stack**

<sub>Python &nbsp;·&nbsp; PyTorch &nbsp;·&nbsp; Hugging Face Transformers &nbsp;·&nbsp; TensorFlow / Keras &nbsp;·&nbsp; scikit-learn &nbsp;·&nbsp; MediaPipe &nbsp;·&nbsp; OpenCV<br/>
Streamlit &nbsp;·&nbsp; React &nbsp;·&nbsp; Tailwind CSS &nbsp;·&nbsp; JavaScript &nbsp;·&nbsp; ethers.js &nbsp;·&nbsp; Solidity &nbsp;·&nbsp; Git &nbsp;·&nbsp; Google Colab &nbsp;·&nbsp; Hugging Face Spaces</sub>

</div>
