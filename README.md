# Fine_Grained_Dog_Breed_Recognition
A CNN Approach for Fine-grained Dog Breed Recognition

Fine-grained dog breed classification is difficult due to subtle inter-class differences and large intra-
class variation. Most prior work reports high overall accuracy on the Stanford Dogs Dataset but
rarely examines the breeds that models consistently misclassify. This study focuses on improving
performance for such weak classes using a ResNet-50 baseline and targeted refinements including
data augmentation, bounding-box cropping, and a feature-level fusion model with Xception. The
final RestNet-50 model achieves 85.2% test accuracy, and the fusion model reaches 90.5%. Saliency
analysis further shows why certain breeds, such as the Siberian Husky and Canadian Eskimo Dog,
remain challenging. The results demonstrate that targeted adjustments can improve classification for
visually similar breeds without relying on excessively large or complex architectures.