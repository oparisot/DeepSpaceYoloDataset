# DeepSpaceYoloDataset

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8387071.svg)](https://doi.org/10.5281/zenodo.8387071)

## 📖 Description

DeepSpaceYoloDataset is an annotated set of smart telescopes images.

During the MILAN research project (MachIne Learning for AstroNomy), we have compiled a large collection of deep sky images during Electronically Assisted Astronomy sessions in Luxembourg, France, Belgium.

We have used two instruments for several months (from March 2022 to September 2023): a Stellina smart telescope (https://vaonis.com/stellina) and a Vespera smart telescope (https://vaonis.com/vespera). We have captured data for a representative set of deep sky objects from the Messier / NGC / IC / Sharpless2 / Barnard catalogues. Different types of celestial objects were considered: emission/reflection/dark/planetary nebula, galaxies, globular/open clusters. Images were obtained after the capture and the stacking of sub-frames of 10 seconds exposure time. 


## 📜 Dataset Structure

Training images were splitted into 608x608 patches. 
Based on the YOLOv7 format, the dataset is a ZIP file containing 4696 RGB images, and the corresponding 4696 labels text files with the positions of deep sky objets in the images.


## 📑 Usage

...


## 📚 Research Papers Using This Dataset

The following paper describes the dataset:

- **DeepSpaceYoloDataset: Annotated Astronomical Images Captured with Smart Telescopes** – [DOI Link](https://doi.org/10.3390/data9010012) 

The following studies have utilized this dataset:

- **Détection d'objets célestes dans des images astronomiques par IA explicable** – [DOI Link](https://doi.org/10.48550/arXiv.2311.10592)  
- **Deep Sky Objects Detection with Deep Learning for Electronically Assisted Astronomy** – [DOI Link](https://doi.org/10.3390/astronomy3020009)  

If you use this dataset in a publication, please notify us to include it in this list.

## 🎓 Citation

If you use **DeepSpaceYoloDataset** in your work, please cite it as follows:

```bibtex
@misc{parisot_2023_8387071,
  author       = {Parisot, Olivier},
  title        = {{DeepSpaceYoloDataset: an annotated set of smart telescopes images}},
  year         = 2023,
  publisher    = {Zenodo},
  version      = {1.0.0},
  doi          = {10.5281/zenodo.8387071},
  url          = {https://doi.org/10.5281/zenodo.8387071},
}
```

## 📝 License

This dataset is released under the **CC Attribution-NonCommercial-NoDerivatives 4.0 International**. See [`LICENSE`](https://zenodo.org/records/8387071/files/LICENCE.txt?download=1) for details.

---

✉️ **Contact**: For questions or collaborations, please contact **Olivier Parisot** at **olivier.parisot@list.lu** or open an issue on **GitHub**.  
🌍 **Project Page**: [https://www.list.lu/fr/recherche/projet/milan2/]

