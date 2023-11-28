# CS182-final-project


**Fine-tuning Stable Diffusion**

[Writeup](https://docs.google.com/document/d/1AsBL5Dn-hUDKLhNS7wC7CC9FNfGRnPY_mMg0GpEgl2g/edit?usp=sharing)


**Note on Reproducibility**

To train our models, we used the A100 GPU on Google colab. Without this GPU or something comparable, it may be difficult to run the Dreambooth without exceeding **memory** limits. For this reason, we have uploaded the model trained on both objects to Hugging Face so that reproducibility checks may still be done by the graders even if they do not have access to high RAM GPUs to reproduce the process. Our model is available [here](https://huggingface.co/FanjiaYan/CS182-DreamBooth-2-Object)


**Citations**


[This](https://huggingface.co/docs/transformers/main/model_doc/dinov2) is the image embedding model we used for DINO to compute image similarity. 


[This](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/sd_dreambooth_training.ipynb?authuser=3#scrollTo=D633UIuGgs6M
) was the code base we used for the initial implementation of Dreambooth.

[Dreambooth Stable Diffusion paper](https://arxiv.org/pdf/2208.12242.pdf)
