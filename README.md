# Collaborative DDoS Detection in collaborative intrusion detection system for Heterogeneous Network Using Multi Deep Learning Model Ensemble Stacking

DetectionCode
Code of the experiment of Collaborative DDoS Detection in collaborative intrusion detection system for Heterogeneous Network Using Multi Deep Learning Model Ensemble Stacking paper
the code already included for the dataset import from kaggle, dataset exploration ,and cleaning. The model already implemented in the file too. it will give the result after run it all. 

dataset 1 : NF-BoT-IoT 
- https://www.kaggle.com/api/v1/datasets/download/dhoogla/nfbotiot
- /content/nfbotiot/NF-BoT-IoT.parquet
dataset 2 : nf-cse-cic-ids2018 
- https://www.kaggle.com/api/v1/datasets/download/dhoogla/nf-cse-cic-ids2018
- /content/nf-cse-cic-ids2018/NF-CSE-CIC-IDS2018.parquet
dataset 3 : nftoniot 
- https://www.kaggle.com/api/v1/datasets/download/dhoogla/nftoniot
- /content/nftoniot/NF-ToN-IoT.parquet
  
experiment 1
MLP - nftoniot
CNN - nf-cse-cic-ids2018
LSTM - nfbotiot
stacking result: 0.837

experiment 2
MLP - nf-cse-cic-ids2018
CNN - nfbotiot
LSTM - nftoniot
stacking result: 0.832

experiment 3
MLP - nfbotiot
CNN - nftoniot
LSTM - nf-cse-cic-ids2018
stacking result: 0.843

experiment 4
MLP - nf-cse-cic-ids2018
CNN - nftoniot
LSTM - nfbotiot
stacking result: 0.837

experiment 5
MLP - nftoniot
CNN - nfbotiot
LSTM - nf-cse-cic-ids2018
stacking result: 0.836

experiment 6
MLP - nfbotiot
CNN - nf-cse-cic-ids2018
LSTM - nftoniot
stacking result: 0.840
