# Active 2D Gaussian splatting for space target 3D reconstruction under orbital constraint

## Installation

```bash
# if you have an environment used for 3dgs, use it
# if not, create a new environment
conda env create --file environment.yml
conda activate surfel_splatting
git submodule update --remote  
pip install submodules/diff-surfel-rasterization
```
## Training
```bash
python train.py -s <path to dataset> 
```

## Testing
```bash
python <path to render.py>/render.py -s <path to dataset>  -m <path to pre-trained model>
```

## Acknowledgements
This project is built higly upon [2DGS](https://surfsplatting.github.io/).