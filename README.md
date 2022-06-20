# Gait Analysis using a CNN-LSTM Model
Analysis of gait data using a CNN LSTM model 
Gait refers to a person's particular movements and stance while moving around. As gait is a combination of numerous minute limb orientations and body position, it is distinctive for each and every individual. However, all of these distinct gaits have some elements in common that contribute to a person's normalcy. These features can be difficult to spot just by looking at them. The ability to recognise these characteristics swiftly may be useful in monitoring the elderly who require constant care and support. It becomes an important aspect of decision-making when analyzing or reviewing progress and the effects of any treatments. This examination is used to assess, record, and make any necessary adjustments for a smooth gait. There are five types of silhouette images in the dataset: normal, fast-walk, slow-walk, with-bag, and with-coat. In image classification, the hybrid architecture of CNN and LSTM can be used: LSTM is used as a classifier, and CNN is used to extract complex properties from images. Five layers of Time-Distributed Convolutional (TDC) layers, along with an LSTM layer make up the developed CNN-LSTM architecture. This model gave a 87.25% accuracy at a 100 epochs, 6 convolution layers and 7 dropout layers.
