# thesis_project
Sleep Spindle Detection using CNN
In this thesis we present the development and evaluation of an automated method for sleep spindle detection based on real electroencephalogram signal using convolutional neural networks (CNN). Specifically, supervised learning was performed οn the artificial neural network having as input filtered and normalized signal samples and as output the desired value for each sample. As our problem leads to a binary classification we used “binary crossentropy” as our cost function which gave us as output a percentage value between zero and one. The evaluation of the network response was done through calculating the accuracy and loss using as input an unknown EEG signal.

The EEG signals came from THE DREAMS database, which contains excerpts of half-hour recordings from eight different patients with different pathologies. The sampling frequency was 200Hz,100Hz or 50Hz. Also, for each signal there was a corresponding evaluation from two experts for sleep spindle scoring.

