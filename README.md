## Urban Sound classification using CNN

## Environment
- Python 3.8
- All necessary dependencies in [requirements.txt](https://github.com/GKPr0/AcusticEventsDetection/blob/master/requirements.txt)

### Dataset
- Urban sound 8K [dataset](https://urbansounddataset.weebly.com/urbansound8k.html)

### Data analysis
- Analysis of dataset such as recording lengths, class distribution or sampling frequencies.
- Listening to class samples.
- Visualization of data as waveform, STFT, MEL-STFT, MFCC.
- [Jupyter notebook](https://github.com/GKPr0/AcusticEventsDetection/blob/master/DataAnalysis.ipynb)
- [Google colab](https://colab.research.google.com/github/GKPr0/AcusticEventsDetection/blob/master/DataAnalysis.ipynb) 

### CNN Training
- Trying to classify based on MelSpectogram.
- Data augmented with time shifting, time masking and freq masking.
- Model is saved after each epoch.
- Confusion matrix to peak at model behavior.
- [Jupyter notebook](https://github.com/GKPr0/AcusticEventsDetection/blob/master/Training.ipynb)
- [Google colab](https://colab.research.google.com/github/GKPr0/AcusticEventsDetection/blob/master/Training.ipynb)