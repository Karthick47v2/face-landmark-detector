<h1 align="center">Welcome to face-landmark-detector 👋</h1>
<p>
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

This is a part of [Mock-Buddy](https://github.com/Karthick47v2/mock-buddy) project, used to detect face interactivity. CNN architecture used to build the model to detect facial landmarks. The model is build with TensorFlow applying direction regression apporach.

## Prerequisite

- Python 3.7 or newer

## Dataset

> 300W consists of several datasets

- [iBUG](https://ibug.doc.ic.ac.uk/download/annotations/ibug.zip)
- [AFW](https://ibug.doc.ic.ac.uk/download/annotations/afw.zip)
- [HELEN](https://ibug.doc.ic.ac.uk/download/annotations/helen.zip)
- [LFPW](https://ibug.doc.ic.ac.uk/download/annotations/lfpw.zip)

> You need bounding boxes to crop faces from above datasets

- [Bounding-box-annotations](https://ibug.doc.ic.ac.uk/media/uploads/competitions/bounding_boxes.zip)

## Usage

> After downloading datasets just update the extraction paths with your datasets path.

- Export train and test csv from `300W.ipynb`.
- Run `model_train.ipynb` to start training.

> I have taken test datasets as iBug, Helen-test and LFPW-test and used evaluation metrics mentioned in 300 faces in-the-wild challenge ([link](https://ibug.doc.ic.ac.uk/resources/300-W/)).

## Author

👤 **Karthick T. Sharma**

- Github: [@Karthick47v2](https://github.com/Karthick47v2)
- LinkedIn: [@Karthick47](https://linkedin.com/in/Karthick47)

## Todo

- [ ] Add heatmap regression approach

## Citation

```
@article{sagonas2016300,
  title={300 faces in-the-wild challenge: Database and results},
  author={Sagonas, Christos and Antonakos, Epameinondas and Tzimiropoulos, Georgios and Zafeiriou, Stefanos and Pantic, Maja},
  journal={Image and Vision Computing},
  volume={47},
  pages={3--18},
  year={2016},
  publisher={Elsevier}
}
@inproceedings{sagonas2013300,
  title={300 faces in-the-wild challenge: The first facial landmark localization challenge},
  author={Sagonas, Christos and Tzimiropoulos, Georgios and Zafeiriou, Stefanos and Pantic, Maja},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision Workshops},
  pages={397--403},
  year={2013},
  organization={IEEE}
}
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Karthick47v2/face-landmark-detector/issues).

## Show your support

Give a ⭐️ if this project helped you!
