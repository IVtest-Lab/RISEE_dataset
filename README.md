# RISEE Dataset
[![website](https://img.shields.io/badge/Website-Explore%20Now-blueviolet?style=flat&logo=google-chrome)](https://ivtest-lab.github.io/RISEE_dataset/)
[![paper](https://img.shields.io/badge/arXiv-Paper-B31B1B?logo=arxiv)](https://arxiv.org/abs/2507.19490)
[![paper](https://img.shields.io/badge/chinaXiv-Paper-<COLOR>.svg)](https://chinaxiv.org/abs/202507.00069?&locale=en)

###  :fire: Full data is available now.
[All FPV videos used in the experiment are now available. Please email us if needed.]

This is the official implementation of ITSC 2025 paper: "[RISEE: A Highly Interactive Naturalistic Driving Trajectories Dataset with Human Subjective Risk Perception and Eye-Tracking Information]([https://chinaxiv.org/abs/202507.00069?locale=en](https://ieeexplore.ieee.org/document/11423845))", Xinzheng Wu, Junyi Chen, Peiyi Wang, Shunxiang Chen, Haolan Meng, Yong Shen.

## Data Format

- For detailed data format description, please refer to [@data_format_description.pdf](data_format_description.pdf)


## Data Organization

```shell
RISEE_dataset
├── example_files/
│   ├── map.xodr                      # the map of the recording site in OpenDrive format
│   ├── trajectory_example.csv        # example of the extracted highly interative scenarios
│   └── eye-trcking_example.csv       # example of the eye-tracking data
│
├── full_data/
│   ├── map.xodr                      # the map of the recording site in OpenDrive format
│   ├── overall_sub_obj_risk.xlsx     # average subjective risk perception results, TTC and DNDA of each scenario
│   ├── cross-references.xlsx         # correspondence between participants and scenarios
│   ├── trajectoris_data/
│   │   ├── scenario_001.csv
│   │   ├── scenario_002.csv
│   │   ├── ...
│   │   └── scenario_179.csv
│   └── eye-tracking_data/
│       ├── scenario_001/              # each scenario is evlauted by at least 20 different participants
│       │   ├── participant_xxx.csv    # but not all of their eye-tracking data is valid
│       │   ├── ...
│       │   └── participant_xxx.csv
│       ├── scenario_002/ 
│       ├── ... 
│       └── scenario_179/  
│
└── data_format_description.pdf
```


## Citation

If you find this repository useful for your research, please consider giving us a star :star2: and citing our paper.

```bibtex
@inproceedings{wu2025riseea,
  title = {RISEE: A Highly Interactive Naturalistic Driving Trajectories Dataset with Human Subjective Risk Perception and Eye-Tracking Information},
  booktitle = {2025 IEEE 28th International Conference on Intelligent Transportation Systems (ITSC)},
  author = {Wu, Xinzheng and Chen, Junyi and Wang, Peiyi and Chen, Shunxiang and Meng, Haolan and Shen, Yong},
  year = 2025,
  month = nov,
  pages = {2315--2322},
  issn = {2153-0017},
  doi = {10.1109/ITSC60802.2025.11423845}
}
```

## Contact
If you have any questions or suggestions, please feel free to open an issue or contact us (*wuxinzheng@tongji.edu.cn* or *chenjunyi@tongji.edu.cn*).
