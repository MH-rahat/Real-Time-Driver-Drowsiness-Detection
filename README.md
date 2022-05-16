# Real Time Driver Drowsiness Detection  
How humans manage their time has changed dramatically in recent years. As a result, human beings' natural sleep cycles have been disrupted. Humans are prone to feeling tired at any time of day due to a lack of sleep and unpredictable sleep cycles. The classification of eye states (open or closed) offers a wide range of possible applications, including fatigue monitoring, psychological state analysis, and management of smart home devices, among others. Because of its significance, a lot of studies utilizing typical shallow neural networks or support vector machines have already been published in the literature, with good results. However, employing suitable categorization algorithms, there is still room to increase the accuracy of existing systems. Traditional classifiers have a key flaw in that they rely on manual feature selection, which makes selecting meaningful characteristics for such classifiers extremely difficult. Convolutional Neural Networks (CNN) are employed in real-time applications to achieve two goals: high accuracy and speed. We suggested a CNN model for eye state categorization in this paper and tested it on four CNN network models (VGG16, Resnet50, Densenet121, designed custom model) the MRL Eye(47000 eye pictures) dataset is used to train the model. When trained with training samples from the same dataset, the model performs very well (around 99 % accuracy for categorization of eye states on the test set of data). This paper explains how to create a complete drowsiness detection system that analyzes the state of the driver's eyes to further determine the driver's drowsy state and alerts the driver before any severe threat to road safety.
<p align="center">
  <img 
    width="500"
    height="400"
    alt="Result 1"
    src="https://user-images.githubusercontent.com/38842742/168676740-67944a03-f4dd-423a-bbfe-4d36f7dbe675.png"
  >
</p>
