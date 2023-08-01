# ConvLSTM_with_Attention_Mechanism
This project presents an implementation of a Convolutional LSTM (ConvLSTM) model with multiple attention modules to enhance the model's ability to focus on important features during video or sequential data analysis. The ConvLSTM is a variant of the Long Short-Term Memory (LSTM) model, which integrates convolutional operations within the LSTM architecture, making it suitable for processing spatio-temporal data.

Attention Modules

The ConvLSTM model in this project is equipped with three different attention modules:

    Squeeze and Excitation (SE) Attention: The SE attention module dynamically recalibrates the channel-wise features by adaptively weighing the importance of each channel based on its global context information. This helps the model focus on informative channels and suppress irrelevant ones.

    Channel Attention: The channel attention module focuses on recalibrating the spatial features within each channel, enhancing the model's ability to emphasize relevant spatial regions while suppressing irrelevant ones.

    Spatial Attention: The spatial attention module selectively highlights informative regions within each feature map, allowing the model to concentrate on essential spatial regions while attenuating less important regions.

Features

    Implementation of the ConvLSTM model with three distinct attention modules: Squeeze and Excitation (SE), Channel Attention, and Spatial Attention.
    Configurable hyperparameters for the ConvLSTM and attention modules, allowing users to customize the model architecture to suit their specific tasks.
    Compatibility with video or sequential data inputs, enabling spatio-temporal analysis.
    Training and inference functionalities, with options to use pre-trained models or train from scratch on user-specific datasets.
