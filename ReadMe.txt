Multimodal emotions reconition collab notebook
Requirments:pytorch, librosa, eficieantface
in the preprocessing we transformed the data into a npy file and use to create the anonations.txt that gonna be used later in the training phase
we used a pretrain efficientface model can be dowload from here  
Dataset: RAVDESS an audio visual dataset preformed by 24 actors cnexpression 8 emotions
in This approach we used transforms and implimented three types of fusion the late transformer fusion the intermediant usion approach and the late attention aproach so far the accuracy reached 74% 