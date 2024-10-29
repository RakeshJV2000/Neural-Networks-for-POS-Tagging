# Neural-Networks-for-POS-Tagging

- Developed and fine-tuned a neural network model for part-of-speech tagging on English tweets, implementing a feed-forward neural network (FFNN) with varying context window sizes and custom feature engineering
- Experimented with feature engineering, adding binary features for capitalization patterns, common suffixes, and special characters, leading to improved model accuracy from 77.6% to 82.0% (for w=0) and 80.77% to 83.08% (for w=1) on the TEST set.
- Utilized pretrained word embeddings from Twitter data and empirically evaluated the effect of fine-tuning embeddings versus keeping them fixed, achieving an accuracy increase from 78.16% to 82.3% on the TEST set (w=1)
- Explored multiple neural network architectures, comparing 0, 1, and 2 hidden layers, various layer sizes (128, 256, 512), and activation functions (tanh, ReLU, sigmoid), to optimize model performance for part-of-speech tagging
- Conducted comparative analysis of random versus pretrained embeddings for part-of-speech tagging, demonstrating that fine-tuning pretrained embeddings from Twitter data achieved a significant accuracy boost on the DEVTEST set, improving from 77.6% (randomized) to 82.3% (pretrained, w=1)
