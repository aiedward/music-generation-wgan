# music-generation-wgan
Music generation using Generative Adversarial Network

In this project, our goal is using GAN to generate music from spectrum image.

## Enviroment install

1. Install Anaconda3 for basic python enviroment
2. Install tensorflow (GPU version is prefered)

    ```
    # install gpu support tensorflow
    pip install -U tensorflow-gpu
    ```

3. Install keras

    ```
    pip install keras
    ```

## Dataset
1. The training dataset can download from google driver

    https://drive.google.com/open?id=1U3V8iSwSwB3F3DQCosirXUoLmeNbxlLR


## Result 

1.  MusicCNN\_WGAN\_result.ipynb

    ipython notebook to create music result
    
    https://drive.google.com/open?id=1U3V8iSwSwB3F3DQCosirXUoLmeNbxlLR

2.  The generated music wav from WGAN with different epochs
    
    * 100 epoch
    
    <audio controls="controls">
      <source type="audio/wav" src="demo/generate_wav/epoch_100.wav"></source>
    </audio>
    
    * 400 epoch
    
    <audio controls="controls">
      <source type="audio/wav" src="demo/generate_wav/epoch_400.wav"></source>
    </audio>
    
    * 1000 epoch
    
    
    <audio controls="controls">
      <source type="audio/wav" src="demo/generate_wav/epoch_1000.wav"></source>
    </audio>

3. The generated music wav convert it back to midi format and post-process to remove noise 

    *  DEMO 1
    
    <audio controls="controls">
      <source type="audio/mp3" src="demo/generate_midi/epoch_400_demo_07.mp3"></source>
    </audio>
    
    *  DEMO 2
    
    <audio controls="controls">
      <source type="audio/mp3" src="demo/generate_midi/epoch_1000_demo_09.mp3"></source>
    </audio>
    
    *  DEMO 3
    
    <audio controls="controls">
      <source type="audio/mp3" src="demo/generate_midi/epoch_1000_demo_13.mp3"></source>
    </audio>
    
    *  DEMO 4
    
    <audio controls="controls">
      <source type="audio/mp3" src="demo/generate_midi/epoch_1000_demo_16.mp3"></source>
    </audio>


## References:

1. Neural Translation of Musical Style

2. https://github.com/tjwei/GANotebooks/blob/master/wgan-keras.ipynb
