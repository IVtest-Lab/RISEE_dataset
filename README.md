# RISEE Dataset
[![website](https://img.shields.io/badge/Website-Explore%20Now-blueviolet?style=flat&logo=google-chrome)](https://ivtest-lab.github.io/RISEE_dataset/)

Full data will be released by ITSC 2025.

For detailed data format description, please refer to [@data_format_description.pdf](data_format_description.pdf)


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

```bibtex
@InProceedings{,
  
}
```

## Contact
If you have any questions or suggestions, please feel free to open an issue or contact us (*wuxinzheng@tongji.edu.cn* or *chenjunyi@tongji.edu.cn*).
