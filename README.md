# Research purpose and finding
Ensemble machine learning methods enhance model accuracy and precision during training by segmenting data into subsets and selecting features via techniques such as Random Patching, thus enabling learning from a broader data spectrum.
Presently, neural network models incorporate ensemble learning benefits by partitioning data into mini-batches and integrating Dropout layers, among other strategies.
Masked Autoencoders (MAEs) present an innovative method by masking images and leveraging autoencoders to extract features, thereby restoring or eliminating original image attributes.

Our study explored substituting Dropout layers in neural network models with MAEs. By varying masking ratios in MAEs to create a new dataset from facial images for training a model on gender classification and age prediction (multi-label), we compared this approach with the original dataset employing Dropout layers.
In this configuration, the number of MAE hidden layers and the architecture of the initial layers in the neural network model using the original dataset remained unchanged, with only the continuation layer in the neural network model adjusted to accommodate the original dataset.

Our findings indicate that neural network models trained with datasets processed by MAEs demonstrate comparable accuracy and precision to those trained with traditional layer-based approaches.
