# DDoS-Attack-detection-code-with-dataset

The work focuses on detecting DDoS attacks in IoT networks using well-known benchmark datasets such as NSL-KDD, BoT-IoT, CICIDS2017, SDN-IoT, KDD Cup 1999, KDDCUP-NSL-KDD, and CICDDoS2019, which contain large volumes of high-dimensional network traffic data. Because these datasets include many features, effective feature selection is essential to remove redundancy and reduce computational complexity. The proposed approach first applies correlation-based filtering, followed by Particle Swarm Optimization (PSO) to perform global feature exploration. The selected features from PSO are then refined using Grey Wolf Optimization (GWO) to obtain a more optimal subset. Finally, the optimized features are used to train an Artificial Neural Network (ANN) to accurately classify normal and DDoS traffic in IoT environments.

# Dataset Download Links

NSL-KDD (train & test files in CSV/ARFF)
🔗 Available via Zenodo: https://zenodo.org/records/17424143

(contains NSL-KDD files you can download directly)

BoT-IoT (UNSW Canberra IoT traffic dataset)
🔗 Official project page with download link: https://research.unsw.edu.au/projects/bot-iot-dataset

Also available on Kaggle at: https://www.kaggle.com/datasets/vigneshvenkateswaran/bot-iot

CICIDS2017 (intrusion detection dataset with many attacks)
🔗 Official Canadian Institute for Cybersecurity page: https://www.unb.ca/cic/datasets/ids-2017.html

CICDDoS2019 (DDoS network traffic dataset)
🔗 Official CANADA CIC download page: https://www.unb.ca/cic/datasets/ddos-2019.html

Or mirror on Kaggle: https://www.kaggle.com/datasets/dhoogla/cicddos2019




KDD Cup 1999 (classic intrusion detection benchmark)
🔗 Official download from SIGKDD: https://www.kdd.org/kdd-cup/view/kdd-cup-1999/Data
