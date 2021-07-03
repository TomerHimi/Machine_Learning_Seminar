# Machine_Learning_Seminar

Author: Tomer Himi.

It's obvious that supervised representation learning is still better, but unsupervised representation is catching up and may soon replace the need for many labeled samples.

**Notes:**

1) When reviewing a presentation pay attention to the explanations and additional information displayed below each slide.

2) **How to run simCLR code?**

    a. Download the model weights from the link below and extract its content into the checkpoints folder - ResNet50x1                                                                 https://drive.google.com/file/d/13x2-QBIF1s6EkTWf1AjHEGUc4v047QVF/view?usp=sharing.
    b. Run the system with the either commands:
        - For the default run with 20 epochs and a validation size of 0.2- python main.py.
        - For a custom run: python main.py {number of epochs} {size of validation size}.

3) **Description:**

    simCLR linear evaluation using pre-trained weights by https://github.com/google-research/simclr. This file is added as a resource to my seminar presentation at Bar-Ilan            University. 

    File locations:
    - ../data
    - ../models
    - ../checkpoints

    I was using a pre-trained ResNet50 (x1) as the encoding-head and fine-tuning a multiclass logistic regression over it.
    I have decided to use the STL-10 dataset as my second dataset. Everything other than the model checkpoint will be downloaded automatically.

    Requirement: PyTorch.
