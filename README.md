# Hi, I'm Meshal AlRubaie

Artificial Intelligence student at Imam Abdulrahman Bin Faisal University (class of 2027), building intelligent systems that turn data into decisions.

- **Focus:** machine learning, natural language processing, computer vision, and the software around them
- **Currently:** Saudi Sign Language recognition (below), a computer-vision graduation project (littering-event detection from a fixed camera, with an evidence-review dashboard) and an NLP project comparing TF-IDF and sentence-embedding classifiers for noisy SMS spam
- **Open to:** AI and machine-learning internships and co-ops in Saudi Arabia or remote

## Toolbox

`Python` `PyTorch` `scikit-learn` `Hugging Face Transformers` `MediaPipe` `ONNX Runtime` `FastAPI` `NLTK` `spaCy` `OpenCV` `pandas` `NumPy` `SQL` `Git` `Jupyter` `C++` `Java`

## Projects

### [Saudi Sign Language Recognition](https://github.com/meshalbr/saudi-sign-language-recognition)

Recognises Saudi Sign Language signs live from a laptop webcam or a phone camera, on a laptop with no graphics card.

- MediaPipe turns each frame into body, hand and face landmarks; a 450k-parameter Transformer classifies the movement. No video is stored or sent.
- **85.8% top-1 / 97.2% top-5 on signers the model has never seen** (KArSL-100, 100 signs, leave-one-signer-out), up from 67.0% for the first baseline. The published signer-independent result on the same benchmark is 68.2%.
- Found and fixed data problems along the way: hands lost when they touch the chest (recovered from a wrist crop, coverage 68% to 97%) and phone aspect-ratio errors (40% to 83% on an upright phone).
- 2 MB ONNX model, under 2 ms per prediction on the CPU; browser app with practice mode and phone-as-camera over a QR code; tests and CI on every push.

## Course work

| Repository | What it is |
|------------|------------|
| [Natural-Language-Processing-9MA2-labs](https://github.com/meshalbr/Natural-Language-Processing-9MA2-labs) | NLP labs organised one folder per lab (tokenisation and regex, n-gram language models, text classification, TF-IDF and Word2Vec), each with a README, the notebook and a Markdown version with outputs |
| [Image-Processing-8MA2-Labs](https://github.com/meshalbr/Image-Processing-8MA2-Labs) | Ten image-processing labs with OpenCV: transforms, filtering, frequency domain, edge detection, morphology, segmentation |
| [Machine-Learning-8MA2-Labs](https://github.com/meshalbr/Machine-Learning-8MA2-Labs) | Data quality, preprocessing and PCA on a 145k-row weather dataset |

## Contact

[LinkedIn](https://www.linkedin.com/in/meshal-alrubaie) · meshalbr@gmail.com
