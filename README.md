This project presents a transformer-based approach to detecting toxic language using fine-tuned BERT and DistilRoBERTa models. 
Starting from a highly imbalanced dataset (144k non-toxic vs. 15k toxic comments), we applied data augmentation and rebalancing strategies to improve minority class detection. 
Using stratified 5-fold cross-validation, we fine-tuned bert-base-uncased and distilroberta-base, achieving an F1-score of 0.984 for toxic classification with BERT.
We will compare pretrained and fine-tuned transformer models, discuss class imbalance handling, and explore real-world deployment trade-offs between performance and computational efficiency.
