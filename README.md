
# 🎓 From Video to Evidence: Automated Classroom Engagement Analytics

### 📊 Transforming raw classroom videos into measurable insights using AI and Data Science

---

## 🧠 Overview

This project demonstrates an **end-to-end automated data analytics pipeline** that converts classroom videos into structured engagement metrics.

It was developed as a **pilot study** to compare two types of teaching modules — **Advance (inquiry-based)** and **Traditional (lecture-style)** — and measure how dialogue, questioning, and participation differ between them.

---

## 🎯 Objectives

- **Technical Objective:** Build a reproducible, multimodal pipeline to process video → audio → transcript → structured dataset.
- **Analytical Objective:** Quantify classroom engagement using statistical and NLP-based indicators.
- **Pedagogical Objective:** Explore whether dialogic teaching design leads to higher student participation.

---

## ⚙️ System Architecture

| Stage | Description | Tools / Libraries |
|-------|--------------|------------------|
| **Video Preprocessing** | Compress and clean classroom recordings | `FFmpeg` |
| **Audio Extraction** | Convert `.mp4` to `.mp3` for speech recognition | `FFmpeg` |
| **Speech-to-Text + Diarization** | Transcribe and label speakers | `Gemini 1.5 Pro` |
| **Utterance Structuring** | Organize transcript into timestamped lines | `Python (Pandas)` |
| **Question Detection** | Identify whether an utterance is a question | `Fine-tuned DistilBERT` |
| **Metric Computation** | Derive engagement indicators (Talk Rate, Dialogue Frequency, etc.) | `Pandas`, `NumPy` |
| **Visualization** | Compare module types and show engagement patterns | `Matplotlib`, `Seaborn` |

---

## 🧩 Engagement Metrics

| Metric | Meaning | Example Insight |
|--------|----------|----------------|
| **Student Talk Rate** | Student words per minute | Measures participation intensity |
| **Dialogue Frequency** | Speaker changes per minute | Measures classroom interactivity |
| **Student Agency** | % of turns initiated by students | Captures learner autonomy |
| **Question Rate (Student)** | Student questions per minute | Inquiry-driven engagement |
| **Question Rate (Teacher)** | Teacher questions per minute | Instructional prompting |

---

## 📈 Key Results

| Metric | Traditional | Advance | % Increase |
|--------|-------------|----------|------------|
| Student Talk Rate | 4.08 | 18.02 | +342% |
| Dialogue Frequency | 1.49 | 6.49 | +336% |
| Student Agency | 0.58 | 1.42 | +145% |
| Student Question Rate | 0.25 | 1.04 | +316% |
| Teacher Question Rate | 2.43 | 6.75 | +178% |

🟩 **Finding:** Advance Modules led to significantly higher student engagement (Cohen’s d > 0.8 for all metrics).



## 🧮 Statistical Analysis

* **Descriptive Stats:** Mean and % change
* **Effect Size:** Cohen’s d for magnitude
* **Significance Test:** Mann–Whitney U (p < 0.10, one-sided)
* **Composite Engagement Index:** Averaged normalized scores across all metrics

---

## 📦 Tech Stack

* **Programming:** Python 3.10 (Colab)
* **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, SciPy
* **AI Models:** Gemini 1.5 Pro, DistilBERT (fine-tuned)
* **Processing Tools:** FFmpeg
* **Environment:** Google Colab → GitHub

---

## 🧠 Key Learnings

* Built a reproducible AI + analytics pipeline for unstructured data (video/audio).
* Applied **NLP and statistical analysis** to real-world educational data.
* Demonstrated how **AI-driven evidence** can improve classroom design and pedagogy.

---

## 🚀 Future Enhancements

* Expand dataset to include multiple teachers and subjects.
* Integrate **multimodal features** (e.g., gaze tracking, gestures).
* Build **interactive Streamlit dashboard** for real-time analytics.

---

## 🪪 Author

**Surya Prakash**
Data Analytics & AI Enthusiast | Educational Data Science
📧 [suryap19997@gmail.com]
🌐 [[LinkedIn profile link](https://www.linkedin.com/in/surya-prakash-a8464420b/)]
[[Project Report]([https://www.linkedin.com/in/surya-prakash-a8464420b/](https://docs.google.com/document/d/1-esHeOjXnePuFSSibvj9DLUPaWkNBT_Yi5Ol11yAmLE/edit?usp=sharing)]

---

## 🏷 Tags

`Data Analytics` · `AI in Education` · `NLP` · `Speech Processing` · `Python` · `Machine Learning`

````

