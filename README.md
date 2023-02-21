# CLIP Playground

## Getting Started

1. Prepare environment
    ```commandline
    brew install pyenv
    brew install pyenv-virtualenv
    pyenv install 3.10.9
    pyenv virtualenv 3.10.9 clip-playground
    ```
2. Install environment packages
    ```commandline
    pip install --upgrade pip
    pip install jupyter
    pip install Pillow
    pip install pytorch-lightning
    pip install open_clip_torch
    pip install tqdm
    ```
3. Run the playground notebook
   ```commandline
   jupyter notebook playground.ipynb
   ```

## Useful Links

- https://laion.ai/blog/large-openclip/
- https://github.com/mlfoundations/open_clip
- https://laion.ai/blog/laion-aesthetics/
- https://github.com/LAION-AI/aesthetic-predictor
- https://github.com/christophschuhmann/improved-aesthetic-predictor
