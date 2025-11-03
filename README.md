# SEF-cyberbullying
Sentiment &amp; Emotion Fusion (SEF) — hybrid pipeline (toxicity + emotion + sarcasm) for real-time cyberbullying detection (DistilBERT, GoEmotions)
# SEF: Sentiment and Emotion Fusion (Cyberbullying Detection)

*Short:* Hybrid pipeline combining toxicity (DistilBERT), emotion (GoEmotions), and sarcasm detection for real-time moderation in educational chat. This repo contains a single notebook that includes model loading, SEF based fine-tuning, and a GUI demo.

## Files
- refined_model.ipynb — Jupyter notebook: model load / fine-tune / GUI demo (all steps in one file).
- SEF_research.pdf — accepted manuscript (IJCRT Paper ID: IJCRT-295867).
- requirements.txt — Python dependencies.

## Quickstart (run on Google Colab / locally)
1. Open refined_model.ipynb in Google Colab or Jupyter.
2. Install dependencies: pip install -r requirements.txt
3. Run the notebook cells in order. The notebook includes:
   - Model load (prebuilt DistilBERT weights)
   - Optional fine-tuning on a small sample
   - GUI demo (PyQt5) to test live messages

## Notes
- Dataset links are not included. Please download Jigsaw Toxic Comments and GoEmotions externally. See data/README_data.md for instructions (if provided).
- Model weights (if large) are linked in Releases or via external link in this README.

## Contact
Aditya Kumar Maurya — alok2371354@gmail.com — www.linkedin.com/in/adityakmaurya
