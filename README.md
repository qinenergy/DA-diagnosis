# DA-diagnosis
Code for our paper "Domain adaptive transfer learning for fault diagnosis." 2019 Prognostics and System Health Management Conference (PHM-Paris). IEEE, 2019.

### Colab Demo
[Google Colab](https://colab.research.google.com/drive/17oQvdI41wxBWU8zZInfvGzD-YJyGdLLl?usp=sharing)

### Demo Experiment
CWRU: Source is recorded under load 3; Target is recorded under load 1

The code was not identical to the paper as we updated the code from tf1.x to tensorflow2/keras. The provided notebook was used as part of the tutorial session for the European conference of the prognosticas and health management society (PHME21).

### References
Please cite our work if you use this code:
```
@inproceedings{wang2019domain,
  title={Domain adaptive transfer learning for fault diagnosis},
  author={Wang, Qin and Michau, Gabriel and Fink, Olga},
  booktitle={2019 Prognostics and System Health Management Conference (PHM-Paris)},
  pages={279--285},
  year={2019},
  organization={IEEE}
}
@article{wang2020missing,
  title={Missing-class-robust domain adaptation by unilateral alignment},
  author={Wang, Qin and Michau, Gabriel and Fink, Olga},
  journal={IEEE Transactions on Industrial Electronics},
  volume={68},
  number={1},
  pages={663--671},
  year={2020},
  publisher={IEEE}
}
```

### Acknowledgement
[Unsupervised domain adaptation by backpropagation](http://proceedings.mlr.press/v37/ganin15.pdf)
Ganin, Yaroslav, and Victor Lempitsky | ICML, 2015
