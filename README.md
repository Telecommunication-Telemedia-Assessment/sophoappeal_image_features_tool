# Sophoappeal image features extraction tool
Feature extraction for images considering SoA appeal features.

This repository is part of [Sohpappeal](https://github.com/Telecommunication-Telemedia-Assessment/sophoappeal).
Please use the main repository as starting point.

This repository is part of the DFG project [Sophoappeal (437543412)](https://www.tu-ilmenau.de/universitaet/fakultaeten/fakultaet-elektrotechnik-und-informationstechnik/profil/institute-und-fachgebiete/fachgebiet-audiovisuelle-technik/forschung/dfg-projekt-sophoappeal), it contains images and analysis scripts.


## Requirements


* python3, python3-pip, git, imagemagick, wget

* recommendation: create a virtual environment: `python3 -m venv venv && source venv/bin/activate`
* install pip3 requirements: `pip3 install -r requirements.txt`

## Usage

```
usage: image_features.py [-h] [--cpu_count CPU_COUNT] [--report_file REPORT_FILE] image [image ...]

extract several image features

positional arguments:
  image                 image to be evaluated

optional arguments:
  -h, --help            show this help message and exit
  --cpu_count CPU_COUNT
                        thread/cpu count (default: 4)
  --report_file REPORT_FILE
                        file to store predictions (default: features.json)

stg7 2023
``

## Hint
Parts of the features are taken from [`quat`](https://github.com/Telecommunication-Telemedia-Assessment/quat).
And are also included in [`avt_ai_images`](https://github.com/Telecommunication-Telemedia-Assessment/avt_ai_images).


## Acknowledgments

If you use this software or data in your research, please include a link to the repository and reference the following paper.

```bibtex
@article{goering2023imageappeal,
  title={Image Appeal Revisited: Analysis, new Dataset and Prediction Models},
  author={Steve G\"oring and Alexander Raake},
  journal={IEEE Access},
  year={2023},
  publisher={IEEE},
  note={to appear}
}
```

## License
GNU General Public License v3. See [LICENSE.md](./LICENSE.md) file in this repository.