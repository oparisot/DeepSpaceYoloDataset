# DeepSpaceYoloDataset

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8387071.svg)](https://doi.org/10.5281/zenodo.8387071)

## 📖 Description

DeepSpaceYoloDataset is an annotated set of smart telescopes images.

During the MILAN research project [https://www.list.lu/en/recherche/projet/milan2/], we have compiled a large collection of deep sky images during Electronically Assisted Astronomy sessions in Luxembourg, France, Belgium.

We have used two instruments for several months (from March 2022 to September 2023): a Stellina smart telescope (https://vaonis.com/stellina) and a Vespera smart telescope (https://vaonis.com/vespera). We have captured data for a representative set of deep sky objects from the Messier / NGC / IC / Sharpless2 / Barnard catalogues. Different types of celestial objects were considered: emission/reflection/dark/planetary nebula, galaxies, globular/open clusters. Images were obtained after the capture and the stacking of sub-frames of 10 seconds exposure time. 

![DeepSpaceYoloDataset](DeepSpaceYoloDataset_cover.png)


## 📜 Dataset Structure

Training images were splitted into 608x608 patches. 

Based on the YOLO format, the dataset is a ZIP file containing 4696 RGB images, and the corresponding 4696 labels text files with the positions of deep sky objets in the images.


## 📑 Examples

The dataset was used to train a YOLOv7 model -- allowing to obtain the following results.

AI-powered observation of Dumbbell Nebula (M27) with a Vespera smart telescope (8/7/2024)

[![AI-powered observation of Dumbbell Nebula with a Vespera smart telescope (8/7/2024)](https://img.youtube.com/vi/R0H--9pOwv0/0.jpg)](https://www.youtube.com/watch?v=R0H--9pOwv0)

AI-powered annotation of a Dwarf Galaxy (NGC185) with a Vespera smart telescope (14/9/2024)

[![AI-powered annotation of a Dwarf Galaxy (NGC185) with a Vespera smart telescope (14/9/2024)](https://img.youtube.com/vi/VgeiGNtPsVw/0.jpg)](https://www.youtube.com/watch?v=VgeiGNtPsVw)

AI-powered annotation of M1 through a Vespera smart telescope (2/2/2025)

[![AI-powered annotation of M1 through a Vespera smart telescope (2/2/2025)](https://img.youtube.com/vi/QtUkOTkg2Zs/0.jpg)](https://www.youtube.com/watch?v=QtUkOTkg2Zs)

AI-powered annotation of NGC2440 Nebula with a Stellina portable smart telescope (3/3/2025) 

[![AI-powered annotation of NGC2440 Nebula with a Stellina portable smart telescope (3/3/2025)](https://img.youtube.com/vi/W_IayjuKhLY/0.jpg)](https://youtu.be/W_IayjuKhLY)

AI-powered detection of Messier 98 Galaxy through a Vespera portable smart telescope (24/5/2025)

[![AI-powered detection of Messier 98 Galaxy through a Vespera portable smart telescope (24/5/2025)](https://img.youtube.com/vi/fv9MrPHOwDs/0.jpg)](https://www.youtube.com/watch?v=fv9MrPHOwDs)



## 📚 Research

The dataset can be found here:

- **[2023] DeepSpaceYoloDataset: an annotated set of smart telescopes images** – [DOI Link](https://doi.org/10.5281/zenodo.8387071) 

The following paper describes the dataset:

- **[2024] DeepSpaceYoloDataset: Annotated Astronomical Images Captured with Smart Telescopes** – [DOI Link](https://doi.org/10.3390/data9010012) 

The following papers are based on work carried out on **DeepSpaceYoloDataset**:

- **[2023] Détection d'objets célestes dans des images astronomiques par IA explicable** – [DOI Link](https://doi.org/10.48550/arXiv.2311.10592)  
- **[2024] Deep Sky Objects Detection with Deep Learning for Electronically Assisted Astronomy** – [DOI Link](https://doi.org/10.3390/astronomy3020009)
- **[2025] Combining AI-powered detection and Immersive Technologies for Robotic Space Mission Planning** – [DOI Link](https://doi.org/10.5281/zenodo.15002649) 
- **[2025] Исследование возможности детектирования объектов глубокого космоса c помощью методов компьютерного зрения** – [Link](https://www.researchgate.net/publication/387825359_Issledovanie_vozmoznosti_detektirovania_obektov_glubokogo_kosmosa_c_pomosu_metodov_komputernogo_zrenia))  
- **[2025] Deep sky object detection in astronomical imagery using YOLO models: a comparative assessment** – [DOI Link](http://dx.doi.org/10.1007/s00521-025-11223-4) 
- **[2025] COSMICA: A Novel Dataset for Astronomical Object Detection with Evaluation Across Diverse Detection Architectures** – [DOI Link](https://doi.org/10.3390/jimaging11060184) 
- **[2025] Method and Tools to Collect, Process, and Publish Raw and AI-Enhanced Astronomical Observations on YouTube** – [DOI Link](https://doi.org/10.3390/electronics14132567) 
- **[2025] LVM4CSI: Enabling Direct Application of Pre-Trained Large Vision Models for Wireless Channel Tasks** – [DOI Link](https://doi.org/10.48550/arXiv.2507.05121) 
- **[2025] Robustness analysis of Deep Sky Objects detection models on HPC** – [DOI Link](https://doi.org/10.48550/arXiv.2508.09831)
- **[2025] YOLO OPTIMIZATION FOR EDGE AI: A LIGHTWEIGHT APPROACH FOR DEEP SKY OBJECT DETECTION** – [DOI Link](https://doi.org/10.31987/ijict.8.2.331) 
- **[2025] Contrast Transformations as a Stage for Improving Deep Space Object Detection Quality in Astronomical Images** – [DOI Link](https://doi.org/10.1007/978-3-032-07690-8_17) 

If you have a publication related to these works, please notify us to include it in this list.

## 🎓 Citation

If you use **DeepSpaceYoloDataset** in your work, please cite it as follows:

```bibtex
@article{parisot2024deepspaceyolodataset,
  title={DeepSpaceYoloDataset: Annotated Astronomical Images Captured with Smart Telescopes},
  author={Parisot, Olivier},
  journal={Data},
  volume={9},
  number={1},
  pages={12},
  year={2024},
  publisher={MDPI}
}
```

## 📝 License

This dataset is released under the **CC Attribution-NonCommercial-NoDerivatives 4.0 International**. 

See [`LICENSE`](https://zenodo.org/records/8387071/files/LICENCE.txt?download=1) for details.


## ✉️ Contact

For questions or collaborations, please contact **Olivier Parisot** at **olivier.parisot@list.lu** or open an issue on **GitHub**.

Copyright 2021-2025 Luxembourg Institute of Science and Technology (LIST - http://www.list.lu/).

