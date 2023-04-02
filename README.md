# QML-HEP-GSOC-2023
  
*A dedicated submission repository for the Google Summer of Code 2021 [QML-HEP Projects](https://ml4sci.org/gsoc/projects/2023/project_QMLHEP.html).*
  
<br>

The tasks description can be read [here](https://docs.google.com/document/d/1dqBGbH44Eu3W432oRxpOCfI5Dy2pgh2E21JcHeD0fng/edit).


This completed test is submitted as an application for project ideas:
1. [Implementation of Quantum Generative Adversarial Networks to Perform High Energy Physics Analysis at the LHC](https://ml4sci.org/gsoc/2023/proposal_QMLHEP1.html)
 <br>

All from [Machine Learning for Science (ML4Sci)](https://summerofcode.withgoogle.com/programs/2023/organizations/machine-learning-for-science-ml4sci) organization.

## Notes on tasks
- **Task I**: is trivial and straightforward.
- **For Task II**: I looked through previous work especially through 2 architectures 
    1. [ABCNet: An attention-based method for particle tagging](https://arxiv.org/pdf/2001.05311.pdf)
    2. [Jet tagging via particle clouds](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.101.056019)
    
    The dataset [link](https://zenodo.org/record/3164691#.YigdGt9MHrB) is huge and for the computation power I had, the results weren't satisfying.
    I definetely think there is a scope for improvement here.
- **For Task III**: I mainly spoke about how I was amazed by the state of quantum computers itself, being a ML enthusiast I spent the past month or two learning tensorflow quantum and cirq. I also learned about how the various research done on this topic. 
- **For Task IV**: This was one of the most time consuming and most interesting task of all. I refered the previous work from the following paper.
    1. [Quantum semi-supervised generative adversarial network for enhanced data classification](https://arxiv.org/pdf/2010.13727.pdf)
    2. [Entangling Quantum Generative Adversarial Networks](https://arxiv.org/pdf/2105.00080.pdf)
    
    There were two models, generator and discriminator that are trained together and the model was overfitting, as expected due to the small size dataset.
- **For Task VI**: This was simple and straight forward, I just had to implement two functions and train a model based on MNIST dataset.
- **For Task VIII**: Transformers are something I've worked before with, so it was a smooth ride along. I've discussed some ideas about implementing them as quantum transformers. most of the reference for this task was from the paper.
  1. [AN IMAGE IS WORTH 16X16 WORDS:TRANSFORMERS FOR IMAGE RECOGNITION AT SCALE](https://arxiv.org/pdf/2010.11929.pdf)

A quick note on other tasks, I've completed all the neccessary tasks for the project I'm proposing. the google document mentioned that doing all the tasks would likely increase my chance of selection. but while I spend time doing other tasks, It's high time I start writing a good proposal so I would spend the upcoming week for doing the proposal. I'll be uploading the remaining tasks as I complete them.

## Platform
All tasks are done in the Google Colab platform.

## Table of Contents
### Evaluation Test
- Task I: Quantum Computing Part ([Notebook file](https://github.com/Userfound404/QML-HEP-GSOC-2023/blob/main/GsoC_task_1_quantum_circuits.ipynb)) [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lreqB949FE0kZAscmD9LB4LU85zNtc-K?usp=sharing)

- Task II: Classical Graph Neural Network (GNN) Part ([Notebook file](https://github.com/Userfound404/QML-HEP-GSOC-2023/blob/main/GsoC_task_2_CGNN_(1).ipynb)) [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1U3pMwhdL83UD9LT-SjSWq0VFmCSJ6zii?usp=sharing)

- Task III: Open Task Part ([Notebook file](https://github.com/Userfound404/QML-HEP-GSOC-2023/blob/main/Gsoc_Task_3__open_task.ipynb)) [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Userfound404/QML-HEP-GSOC-2023/blob/main/Gsoc_Task_3__open_task.ipynb#scrollTo=-to5lp4aFGwq)

- Task IV: Quantum Generative Adversarial Network (QGAN) Part ([Notebook file](https://github.com/Userfound404/QML-HEP-GSOC-2023/blob/main/GsoC_task_4_QGANs.ipynb)) [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wOEfKupZtjJaAvOcPZcpCgSxOecA6rKO?usp=sharing)

- Task VI: Quantum representation learning Part ([Notebook file](https://github.com/Userfound404/QML-HEP-GSOC-2023/blob/main/GsoC_task_6_Representation_learning.ipynb)) [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qJeoI_DO9F-XjlSeOyCbTAUSbaYz8dwv)

- Task VIII: Transformers Part([Notebook file](https://github.com/Userfound404/QML-HEP-GSOC-2023/blob/main/GsoC_task_8_transformers.ipynb)) [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dtsYRxWHvpWwE9XCaKnY59I0L_xK2oR-?usp=sharing)
<br>
**Note**: GitHub sometimes failed to render Jupyter Notebook's markdown properly, so in case of that, please click the **Open in Colab** button to see the notebook in the browser via Google Colab.


## How to Run the Code
1. Download the repository into your local machine.
2. Ensure that your local machine already has the standard machine learning/data science packages (NumPy, pandas, Matplotlib, scikit-learn, TensorFlow), Cirq and Tensorflow Quantum.
3. For every task, the **Notebook file** should be enough by itself. All the other requirements were already inside the notebook in the **pip install** form or already inside the repository folder that is readily accessible.
4. The only things missing are the datasets (since their size is just too large). You can download them from their respective source to your local machine.
5. Please note that you need to make sure all directories (either for loading the dataset or saving the results) in the notebook are already pointed to the correct directories based on your local machine. The directories written in the notebook are my directories in Google Colab.
6. Please feel free to contact my email if you have trouble running the code.

## Closing Remarks
Thanks a lot to all the mentors for the test. I had the opportunity to learn new things related to quantum machine learning and HEP during the process of finishing the test. Also on a personal note I chose this project the minute I saw because it had two things that I love, Quantum and GAN's. I've been working with classical GANs since long for generating deepfakes(for research ofcourse) and the thought of extending it for solving such a valuble problem is always my motivation.
