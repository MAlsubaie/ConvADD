
# ConvADD: Exploring a Novel CNN Architecture for Alzheimer's Disease Detection



## Abstract
Alzheimer's disease (AD) poses a significant healthcare challenge, with an escalating prevalence and a forecasted surge in affected individuals. The urgency for precise diagnostic tools to enable early interventions and improved patient care is evident. Despite advancements, existing detection frameworks exhibit limitations in accurately identifying AD, especially in its early stages. Model optimisation and accuracy are other issues. This paper aims to address this critical research gap by introducing ConvADD, an advanced Convolutional Neural Network architecture tailored for AD detection. By meticulously designing ConvADD, this study endeavours to surpass the limitations of current methodologies and enhance accuracy metrics, optimisation, and reliability of AD diagnosis. The dataset was collected from Kaggle and consists of preprocessed 2D images extracted from 3D images. Through rigorous experimentation, ConvADD demonstrates remarkable performance metrics, showcasing its potential as a robust and effective. The proposed model shows remarkable results with a tool for AD detection accuracy of 98.01%, precision of 98%, recall of 98%, and an F1-Score of 98%, with only 2.1 million parameters. However, despite its promising results, several challenges and limitations remain, such as generalizability across diverse populations and the need for further validation studies. By elucidating these gaps and challenges, this paper contributes to the ongoing discourse on improving AD detection methodologies and lays the groundwork for future research endeavours in this domain.


## Model Architecture
![Model Architecture](images/arch_diag.png)

## Methodology
![Mmethodology](images/Methodology%20Diagram_2%20-%20Copy.png)


## Important Preprocessing


## Datset Prepration:


## Requirements
- Python 3.9.19
- ```sh
conda create MAF python=3.9.19
```

## Installation
1. Clone the repository:
    ```sh
    git clone ..
    ```
2. Navigate to the project directory:
    ```sh
    cd Attention-Driven-CNNs-for-AD-Detection-via-MAF
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Training
To train the model, run the following command:
```sh
python train.py
```

### Evaluation
To evaluate the model, run the following command:
```sh
python evaluate.py
```

### GradCAM Results



## License
