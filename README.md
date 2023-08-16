# “EffiNet-TS”: A deep interpretable architecture using EfficientNet for plant disease detection and visualization

**Abstract:**
Agriculture is crucial to the economy of any nation since it provides food and jobs for a sizable percentage of the populace. However, plant diseases are one of the biggest obstacles to raising farmer’s income. CNN’s applicability in plant disease diagnosis has been greatly augmented by the recent advent of the most efficient and accurate deep learning classification architectures, such as efficientNet. We propose the architecture named EffiNet-TS, a Teacher/Student architecture based on EfficientNetV2, comprising the EffiNet-Teacher classifier, Decoder and EffiNet-Student classifier. The EffiNet-TS not only classifies the disease but also displays important features for categorizing the plant disease, which aids in classification and provides a good visualization of key symptoms of specific plant diseases. The EffiNet-TS aimed to enhance the classification and visualization results of the existing ResTS architecture by replacing the underlying Xception architecture of Teacher and student blocks with EfficientNetV2S and introducing a novel DscDF (Dual skip connection deconv fusion) block in the decoder network. Consequently, EffiNet-TS solves the overfitting concerns seen by ResTS and offers superior and precise visualization results on real-world images. The experiments have shown that the proposed EffiNet-TS architecture surpasses the ResTS architecture with F1 score: 0.989, Accuracy: 0.990 and Validation Loss: 0.045. The MobileNet-TS architecture was also made based on EffiNet-TS and then compared. The PlantVillage dataset, which contains 54,306 photos with 38 categories, is used for the experiments. Additionally, we collected a few samples of infected tomato plant leaves from the field to validate the architectures in the real world.

# Cite the article 
Gehlot, M., & Gandhi, G. C. (2023). “EffiNet-TS”: A deep interpretable architecture using EfficientNet for plant disease detection and visualization. Journal of Plant Diseases and Protection, 130(2), 413-430.
DOI : https://doi.org/10.1007/s41348-023-00707-x

**Article Link :** https://link.springer.com/article/10.1007/s41348-023-00707-x