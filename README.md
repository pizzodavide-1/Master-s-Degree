# Master-s-Degree
Repository for my Master's thesis at the University of Milano-Bicocca, titled: "Through the Eyes of the Model: Comparing Human and Machine Attention in Multimodal Misogyny Detection"

This project studies the explainability of multimodal deep learning models used to detect misogynous content in memes and asks a simple question: does the model look at the same things a human does? To answer it, model attention is compared against real human gaze data collected via eye-tracking.

This project:
-Applies explainability techniques to two multimodal models, mCLIP and mBLIP, on the misogyny-detection task.
-Builds attention maps using Grad-CAM, per-head attention analysis, and Integrated Gradients for the textual component.
-Fuses image and text explanations into a single saliency map for each meme.
-Evaluates how closely model attention matches human eye-tracking data, using the NSS (Normalized Scanpath Saliency) and EMD (Earth Mover's Distance) metrics.

This project uses the MAMI dataset (SemEval-2022 Task 5, Multimedia Automatic Misogyny Identification). The dataset is not included in this repository: it is distributed under a restricted-access agreement.

Update the data and output paths at the top of each notebook to point to your local ./data/ and ./results/ folders before running.
