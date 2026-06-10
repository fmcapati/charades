Human activities occur everywhere, but can a machine learn to recognize them simply by watching video? 

Our study investigates whether deep learning models can distinguish between actions such as diving, drumming, and pull-ups from short video clips.

Using 6,681 video clips from 50 human action categories in the UCF50 dataset, we built and compared different Convolutional Neural Network (CNN) + Recurrent Neural Network (RNN) architectures, from simple scratch-built baselines to transfer learning models. The idea is that a CNN looks at each frame and extracts spatial features, while a recurrent network learns how those features change over time to recognize the activity being performed.

Our study emphasizes on understanding model design, not just maximizing accuracy. Rather than relying on a single architecture, we systematically investigate how three factors (i.e. recurrent unit selection, CNN depth, and transfer learning versus training from scratch) affect human activity recognition performance.
