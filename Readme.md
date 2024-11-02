# Model Instructions

## Setup Instructions

1. Clone the repository: git clone https://github.com/RSM1234q/LLMs-Final-Project.git
2. Navigate to the project directory.
3. Create a virtual environment: python -m venv venv
4. Activate the virtual environment:
   - Windows: venv\Scripts\activate
   - macOS/Linux: source venv/bin/activate
5. Install the dependencies: pip install -r requirements.txt

## Instructions for Running Full Fine-Tuned (FFT) Models

1. Open `FFTModels.ipynb`.
2. Both BERT and RoBERTa models are available in separate cells; run only the cell corresponding to the model you wish to use.
3. The remaining code is shared between both models, so no additional modifications are needed.

## Instructions for Running Parameter-Efficient Fine-Tuning (PEFT) Models

1. Open `PEFTModels.ipynb`.
2. Six model configurations are available, supporting 1-shot, 3-shot, and 6-shot prompting for both BERT and RoBERTa.

### To Create 1-Shot Prompt Models:

- Run all cells **except** cells 3, 11, and 12.
- **For BERT**: skip cell 6.
- **For RoBERTa**: skip cell 7.

### To Create 3-Shot Prompt Models:

- Run all cells **except** cells 3, 10, and 12.
- **For BERT**: skip cell 6.
- **For RoBERTa**: skip cell 7.

### To Create 6-Shot Prompt Models:

- Run all cells **except** cells 10 and 11.
- **For BERT**: skip cell 6.
- **For RoBERTa**: skip cell 7.
