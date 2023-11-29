<a href="https://www.tum.de/en/">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c8/Logo_of_the_Technical_University_of_Munich.svg" align="right"
     alt="Size Limit logo by Anton Lovchikov" height="80">
</a>

# tum2twin

This repository contains [CityGML](https://www.ogc.org/standard/citygml/) LOD3 models of the [Technical University of Munich](https://www.tum.de/en/).

![screenshot](./docs/screenshot.png)


## 🚀 Getting Started

The datasets are stored on a dedicated [GitLab repository](https://gitlab.lrz.de/tum-gis/tum2twin-datasets).
To clone the repo, make sure to have [Git LFS](https://git-lfs.com/) installed and run:

```bash
git clone --depth 1 git@gitlab.lrz.de:tum-gis/tum2twin-datasets.git
```

The tum2twin-dataset repository contains:

- CityGML
  - [lod2-building-datasets](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/citygml/lod2-building-datasets): LOD2 building models of the [Bavarian State Office for Digitizing, Broadband and Survey (LDBV)](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=lod2)
  - [lod2-textured-building-datasets](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/citygml/lod2-textured-building-datasets): LOD2 textured building models
  - [lod3-building-datasets](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/citygml/lod3-building-datasets): Exported CityGML v2 LOD3 building models
  - [lod3-vegetation-datasets](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/citygml/lod3-vegetation-datasets): Trees modelled using [this workflow](https://github.com/SabineZa/Automatic_Tree_Cadastre)
- SketchUp
  - [lod2-textured-building-projects](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/sketchup/lod2-textured-building-projects): LOD2 SketchUp projects for texturing the building models
  - [lod3-building-projects](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/sketchup/lod3-building-projects): SketchUp projects modelled according to [this guideline](https://creating-citygml-datasets.readthedocs.io/en/latest/creation-guidelines/lod3-models-based-on-point-clouds.html)

The file names follow the GML IDs of the [LDBV](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=lod2).

## 🧪 Model Collection

The goal of tum2twin is to contribute to a collection of different representations of the TUM campus and its surroundings to promote research and development of new methods.

- [LDBV](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=lod2): tum2twin follows and preserves the structure of the official LOD2 building models (tile [690_5336](https://download1.bayernwolke.de/a/lod2/citygml/690_5336.gml) and [690_5334](https://download1.bayernwolke.de/a/lod2/citygml/690_5334.gml))
- [TUM-FAÇADE](https://github.com/oloocki/tum-facade): MLS point clouds with facade-level labels

## 🛠️ Contributing

If you find any errors or deficiencies, please create an [issue](https://github.com/tum-gis/tum2twin/issues).
Improvements and extensions of the models are also highly welcome.

## 🎓 Research

Publications that use the dataset:

- [Scan2LoD3: Reconstructing semantic 3D building models at LoD3 using ray casting and Bayesian networks](https://openaccess.thecvf.com/content/CVPR2023W/PCV/papers/Wysocki_Scan2LoD3_Reconstructing_Semantic_3D_Building_Models_at_LoD3_Using_Ray_CVPRW_2023_paper.pdf), CVPRW '23 proceedings
- [TUM-FAÇADE: Reviewing and enriching point cloud benchmarks for façade segmentation](https://isprs-archives.copernicus.org/articles/XLVI-2-W1-2022/529/2022/isprs-archives-XLVI-2-W1-2022-529-2022.html), ISPRS Archives, ArCH '22 proceedings 
- [Automatisierte Generierung eines Baumkatasters aus Punktwolken in unterschiedlichen urbanen Umgebungen](https://mediatum.ub.tum.de/1713266), Masterarbeit 2023, Technische Universität München, [Github Repository](https://github.com/SabineZa/Automatic_Tree_Cadastre)
- [Thermal Mapping from Point Clouds to 3D Building Model Facades](https://www.mdpi.com/2072-4292/15/19/4830), Remote Sensing journal, 2023
- [Evaluation of the Effect of Enriched Facade Models on Image-Based Localization of Vehicles](https://mediatum.ub.tum.de/1720655), Bachelorthesis 2023, Technical University of Munich, [Github Repository](https://github.com/AntoniaBie/LoD3ForLocalization)

## 🤝 Acknowledgement

- [Landesamt für Digitalisierung,
Breitband und Vermessung (LDBV)](https://www.ldbv.bayern.de) for their great [open data](https://geodaten.bayern.de/opengeodata/) offering
- [AI4TWINNING](https://www.mdsi.tum.de/gni/gni-funded-projects/ai4twinning/), the project which is facilitating the development of the LoD3 models. 
- [3D Mapping Solutions](https://www.3d-mapping.de/home/) for providing high-grade 3D point clouds within the scope of the MoFa project
