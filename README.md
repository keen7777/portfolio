# Keen's Alchemy Lab 

*Turning curiosity, tea polyphenols, and questionable ideas into working code~*

## About Me

Hey, I'm Keen! 

I like experimenting with different technologies, mixing ideas that probably shouldn't go together, and occasionally turning tiny inconveniences into unnecessarily elaborate programming projects.

Some experiments become useful tools. Others explode spectacularly (figuratively, of course). Either way, there's usually something interesting to learn.

This lab is where I keep my software projects, AI experiments, and whatever else I've managed to conjure up with code.


# The Experiments

### WUSCHEL: NLP Analysis & Validation

**Python · spaCy · TypeScript · MongoDB · Git**

A research software project for assessing children's language competencies using NLP.

My work focuses on refactoring a legacy Python analysis pipeline, investigating scoring inconsistencies, and building tools that allow linguistic researchers to inspect and validate automated results.

**Highlights:** NLP pipeline refactoring, regression testing, expert validation, researcher-friendly interfaces.

*Research project — source code and internal data are not publicly available.*

---

### Poodle or Cookie: X-ray Inspection Prototype

**C++17 · OpenCV · CMake · CTest**

A small, AI-assisted computer vision experiment exploring how image-processing techniques can reveal potential defects in industrial X-ray images.

Features interactive parameter adjustment, morphological operations, connected-component analysis, and visualisation of candidate defect regions.

**Highlights:** C++, computer vision, AI-assisted prototyping, automated testing.

🔗 [Source Code](https://github.com/keen7777/poodle-or-cookie)

---


### Neural Image Watermarking: Bachelor's Thesis

**Robustness of Neural Image Watermarking against Inpainting-Based Attacks**

**Python · PyTorch · OpenCV · Deep Learning · Image Processing**

Can invisible image watermarks survive when parts of an image are removed and reconstructed?

My Bachelor's thesis explored this question by extending the HiDDeN framework and systematically evaluating neural watermark robustness against inpainting-based attacks.

**What I worked on:**
- Compared four watermark training strategies: baseline, Gaussian blur, Haar-wavelet distortion, and frozen U-Net inpainting.
- Evaluated five reconstruction methods under rectangular and sparse pixel-removal attacks.
- Investigated spatial mask optimisation using probabilistic sparsification and non-local pixel exchange.
- Conducted quantitative evaluations using BER, PSNR, SSIM, and paired bootstrap confidence intervals.

**Key finding:** Better image reconstruction does not necessarily mean better watermark recovery. At the same retained-pixel density, optimising *where* pixels survive can significantly improve visual reconstruction while the hidden message remains degraded.

**Takeaway:** A system's apparent output quality is not always a reliable measure of its actual robustness.

*Full thesis and source code are not publicly available.*

---

### Phonetics Quiz: Surviving Linguistics Exams

**Python · Streamlit · pandas**

A little interactive learning tool I built to make
phonetics exam preparation less painful.

Instead of memorising IPA symbols and phonetic features
from static tables, I wanted something I could actually
practise with.

**Features:**
- Interactive IPA and phonetic feature exercises.
- Editable tables for exploring phonetic properties.
- Answer checking and quiz-based practice.
- Browser-based interface built with Streamlit.

**Highlights:** Python, interactive data applications,
input validation, linguistics, self-directed development.

🔗 [Live Demo](https://phonetics-de-quiz.streamlit.app/)
🔗 [Source Code](https://github.com/keen7777/phonetics)

---

### Flow Reading Tracker

**Angular · TypeScript**

A reading tool featuring TXT import, interactive word highlighting, and local vocabulary storage.

Built to make reading and vocabulary collection a little more convenient.

**Highlights:** Frontend development, interactive UI, local data storage.

🔗 [Source Code](https://github.com/keen7777/flow_reading_tracker)

---

###  React E-Commerce Frontend

**React · JavaScript · HTML · CSS**

A tutorial-based frontend project featuring a product-oriented shopping interface.

A learning experiment in React components and frontend development, with a deployed live demo.

**Highlights:** React, UI development, deployment.

🔗 [Live Demo](https://react-practice-45zv.onrender.com/)

---

###  Scientific Literature RAG (Work in Progress)

**Python · PyMuPDF · Ollama · Qwen2.5**

An experimental, fully local research assistant for exploring scientific literature with retrieval-augmented generation.

Currently at the early development stage, focusing on PDF ingestion and local LLM experimentation.

**Highlights:** Local AI, document processing, RAG architecture.

*Still brewing...*


---

## My Crucible: Tools & Technologies

**Languages:** Python, TypeScript, JavaScript, C++, Java, SQL (basic)

**Web:** React, Angular, HTML, CSS

**Data & AI:** PyTorch, OpenCV, pandas, spaCy, MongoDB

**Testing:** pytest, Vitest, Jasmine, CTest

**Tools:** Git, Linux, CMake, Ollama

---

## 🧙 More Experiments Coming Soon...

There are always a few half-finished ideas bubbling away in the lab.

Some might become useful. Others might just be fun.

Either way, I'll probably end up writing code for them.
