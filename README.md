# Unrestricted Facial Geometry Reconstruction Using Image-to-Image Translation
[[Arxiv]](https://arxiv.org/pdf/1703.10131.pdf) [[Video]](https://www.youtube.com/watch?v=6lUdSVcBB-k)

Evaluation code for Unrestricted Facial Geometry Reconstruction Using Image-to-Image Translation. Given a single image, the code outputs the reconstructed mesh.

<img src="imgs/teaser.png" width="900px"/>

## Recent Updates

**`2018.07.20`**: Spiltted `postprocess` into the different steps composing the pipeline, changed models to `float` to save space.

## Setup & Usage
The project was tested on Ubuntu 14.04 LTS with Matlab R2015b, to run it follow these instructions:
- Make sure you have <a href="http://torch.ch/docs/getting-started.html">Torch</a> installed on your machine.
- Install the ```mattorch``` and ```nngraph``` packages.

  ```bash
  luarocks install mattorch    
  luarocks install nngraph
  ```
- Download the <a href="https://drive.google.com/file/d/1JZLKxqggY1I4ggtx7TFWp_mP-KGywkVK/view">model files</a> and extract them into the ```models``` directroy.

- Run the ```runme.m``` script in Matlab.

## Citation
If you use this code for your research, please cite our paper <a href="https://arxiv.org/pdf/1703.10131.pdf">Unrestricted Facial Geometry Reconstruction Using Image-to-Image Translation</a>:

```
@article{sela2017unrestricted,
  title={Unrestricted Facial Geometry Reconstruction Using Image-to-Image Translation},
  author={Sela, Matan and Richardson, Elad and Kimmel, Ron},
  journal={arxiv},
  year={2017}
}
```
