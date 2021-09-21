# MLDA-MNVAE
This is a implementation of a method for multimodal concept formation.
In this method, unsupervised multimodal clustering and cross-modal inference, as well as unsupervised representation learning, can be performed by integrating the multimodal latent Dirichlet allocation (MLDA)-based concept formation and VAE-based feature extraction. 

# Requirements
```
pip install tensorflow-gpu==1.12.0
pip install numba 
```

# Training data
Download training data from [here](https://drive.google.com/file/d/1pnP_tVUEgRs3VnUIo4IoA4V-ga5mkV9Y/view?usp=sharing) and put it in the cloned repository. 

# Execution
```
python main.py
```

If you encountered an error of TensorFlow, try to execute the following command: 
```
export TF_FORCE_GPU_ALLOW_GROWTH=true
```

# Citation
Ryo Kuniyasu, Tomoaki Nakamura, Tadahiro Taniguchi, Takayuki Nagai, "Robot Concept Acquisition Based on Interaction between Probabilistic and Deep Generative Models", Frontiers in Computer Science, Vol. 3, Article 618069, pp. 1-14, Sep. 2021
