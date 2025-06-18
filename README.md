# Key Piano Artificial Intellegence (KP-AI)

> learn piano without a teacher with a real-time piano key classification system using deep learning

## 🚀 Overview

- Allows users to practice piano independently through key recognition feedback.
- Implements a deep learning model that accurately classifies pressed keys (single notes and chords) from real-time audio input.
- Provides an easy-to-use interface that visualizes detected keys and highlights correctness compared to reference input.

## 🎯 Objectives

- Optimize inventory management by reducing stockouts and overstocks through data-driven reorder recommendations.
- Apply unsupervised learning (Association Rule Learning) to discover product purchase patterns without labeled data.
- Build a reusable pipeline for rule extraction and evaluate its integration potential in real-time inventory systems.

## 📊 Dataset

The project uses a custom-built dataset consisting of audio recordings from digital piano applications and physical keyboards, annotated with ground truth labels of the played keys or chords.
- Total Samples (target): 2500
- Single Notes: 1000
- Chords: 1000
- Mixed Play (Live Segment): 500
Format: .wav audio files
Annotation: Manual labeling of key names (e.g., C4, E4, G major)
Link : [Piano Data](https://www.kaggle.com/datasets/willianoliveiragibin/grocery-inventory)


## 🛠️ Tech Stack

<table>
  <tr>
    <th>Category</th>
    <th>Technology</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Language</td>
    <td>Python</td>
    <td>Core language for data preprocessing, model development, and evaluation</td>
  </tr>
  <tr>
    <td>Main library</td>
    <td>NumPy </br>Librosa </br>Tensorflow </br>Matplotlib, Seaborn, Chroma</td>
    <td>For numerical calculations </br>For audio feature extraction and signal processing </br>For deep learning model building </br>To visualize waveform, spectrogram, chroma, and prediction feedback</td>
  </tr>
  <tr>
    <td>Tools</td>
    <td>Google Colab </br>Github </td>
    <td>For cloud-based experiments and notebook execution </br>For controlling, documentation, and collaboration in project</td>
  </tr>
</table>

## ⚙️ System Architecture
> akan diisi diagram proses mesin belajar dengan algoritma FP-Growth
## 📈 Results
> akan diisi hasil evaluasi model dan aturan yang digunakan

## 🧠 Learned

- Built a deep learning pipeline to classify piano keys from raw audio.
- Extracted relevant audio features (Mel-spectrogram, Chroma) for input to neural networks.
- Trained and validated multiple architectures including CNN, GRU, and hybrid models.
- Developed feedback visualization to guide piano learners interactively.

## 🌱 Future Work

- Expand dataset with more chord variations and real-performance recordings.
- Add feedback correction for wrong key prediction and fingering guidance.

## 👤 Author

| Nama | Peran | GitHub |
|------|-------|--------|
| Shodiq Wahyu | ML Developer | [@odiqwr](https://github.com/odiqwr) |

## 📄 License

MIT License – See the [LICENSE](LICENSE) file for details.
