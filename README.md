# nlp-hugging-face
- Using nlp with open-source library <a href="https://huggingface.co/">Hugging Face</a>
- You will need to register for a <a href="https://wandb.ai/">Wandb AI</a>and create an access token to track your model parameters
- You will also need an Hugging face account for a secret key with relevant read/write permissions should you wish to push your model
  
   `from huggingface_hub import notebook_login

    notebook_login()
  <name-of-model>push_to_hub("<model-name>")`
