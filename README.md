# SIREN APP - App to Detect Online Predator
### INTERDISCIPLINARY PROJECT
**SIREN** is a real-time mobile application designed to detect and mitigate online predatory behavior targeting teenagers. It combines **machine learning**, **natural language processing**, and **sentiment/context analysis** to analyze chats, profile data, and behavioral cues for early threat detection.

### Objective
To build a smart safety layer that:
- Detects grooming and predatory intent through linguistic patterns, sentiment shifts, and behavioral red flags.
- Sends real-time alerts to teens and designated guardians.
- Empowers users with educational content on online safety and manipulation awareness.

### Tech Stack
- **Frontend:** Flutter (Dart), Figma  
- **Backend:** TensorFlow Lite, Google Colab  
- **ML/NLP Models:** SVM, BERT, TextBlob, Random Forest, TF-IDF, SpaCy  
- **Tools/APIs:** Google NLP, YouTube API, VS Code  

---

## Results

| Task                                 | Model / Method     | Accuracy | Precision | Recall | Remarks                                |
|--------------------------------------|---------------------|----------|-----------|--------|----------------------------------------|
| Sentiment Classification             | SVM + TF-IDF        | 69%      | 1.00 (pos)<br>0.67 (neutral) | 0.50 (pos)<br>1.00 (neutral) | Flagged threats when >30% negative |
| Contextual Behavior Analysis         | BERT                | –        | –         | –      | Identified affectionate/predatory intent |
| Chat Pattern Classification          | Random Forest       | 18.75%   | 0.50 (for some classes) | 1.00 (for some classes) | Needs tuning for accuracy         |
| Alert System, Profile Detection      | Functional Tests    | 100%     | –         | –      | All core app features passed testing    |

---

### Achievements
- Identified three risk levels (friend, risk, high-risk predator) based on language cues.
- Integrated educational modules, customizable alert thresholds, and profile behavior checks.
- Successfully deployed and tested alert flow, sentiment detection, and backend logic.

---

> *SIREN aims to make digital spaces safer by proactively defending teens against online threats with smart, ethical AI.*

