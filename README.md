**WebGuard - Meachine Learning Extention For Spam Prevention**

This project is a Chrome extension designed to provide real-time, adaptive spam detection using an ensemble of machine learning models. As spammers continuously evolve their tactics, there is a growing need for effective tools to filter out unwanted or malicious content across platforms. This extension addresses key challenges in spam detection, focusing on accuracy, adaptability, and user accessibility.

**Key Innovations:**

1. **Multi-Model Fusion Engine :**
   
     Utilizes a synergistic blend of Multinomial Naive Bayes, Bernoulli Naive Bayes, and Random Forest classifiers to maximize detection precision and minimize false positives.

2. **Context-Aware Spam Analysis:**

     Dynamically inspects visible on-page content, analyzing text at the sentence-level granularity to catch nuanced and disguised spam.

3. **Real-Time Spam Visualizer:**

     Automatically highlights suspicious content with red overlays, providing immediate visual cues without disrupting the user experience.

4. **Intelligent Input Scanner:**
   
     A built-in scanner area enables users to manually submit messages or comments from any platform to check for potential spam threats in real-time.

5. **Instantaneous Detection Pipeline:**

     Integrated with your browser session to run low-latency, on-the-fly classifications as you navigate web content.

6. **Self-Evolving Spam Defense:**

     Continuously trains on fresh data patterns, ensuring resilience against novel and evolving spam strategies.

7. **Intuitive Control Panel:**

     A minimalistic interface allows users to fine-tune sensitivity, toggle models, and view detection confidence, offering transparency and customization.

 **Why WebGuard?**

In the age of information overload, users are increasingly vulnerable to deceptive, harmful, or irrelevant content. Traditional spam filters are often reactive, platform-dependent, and slow to adapt.

**WebGuard stands out by:**

Bringing ML-based spam detection directly into the browser

Empowering users to detect, visualize, and respond to spam in real time

Offering a plug-and-play solution without requiring technical knowledge

This project pioneers a cross-platform spam interception layer that redefines how end-users defend against digital spam threats.

**How to Use**

Install the Extension
Add WebGuard to your Chrome browser from the extension store or load it manually via Developer Mode.

Automatic Detection
As you browse, WebGuard automatically scans pages and highlights detected spam messages.

Manual Text Checker
Paste any message into the provided input area to evaluate it for spam characteristics.

Customization (Optional)
Adjust detection thresholds, enable/disable models, or view prediction logs via the control panel.

**Tech Stack**

Frontend: HTML5, CSS3, Vanilla JavaScript

Backend & ML Integration: Python (Scikit-learn, Pandas, NLTK)

Extension Engine: Chrome Manifest V3

Model Deployment: Local JSON-based prediction (or API if hosted)

**Future Scope**

Cloud-based model updates

Phishing and scam detection

Integration with messaging and email platforms

User feedback loop for personalized spam training.
