<a href="https://www.tum.de/en/">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c8/Logo_of_the_Technical_University_of_Munich.svg" align="right"
     alt="Size Limit logo by Anton Lovchikov" height="80">
</a>

# tum2twin

This repository contains [CityGML](https://www.ogc.org/standard/citygml/) LOD3 models of the [Technical University of Munich](https://www.tum.de/en/).

![screenshot](./docs/screenshot.png)

> **Warning**
> The models are currently under construction and are therefore in a beta version.

## 🚀 Getting Started

The datasets are stored on a dedicated [GitLab repository](https://gitlab.lrz.de/tum-gis/tum2twin-datasets).
To clone the repo, make sure to have [Git LFS](https://git-lfs.com/) installed and run:

```bash
git clone --depth 1 git@gitlab.lrz.de:tum-gis/tum2twin-datasets.git
```

The tum2twin-dataset repository contains:

- [citygml-lod2-datasets](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/citygml-lod2-datasets): LOD2 building models of the [Bavarian State Office for Digitizing, Broadband and Survey (LDBV)](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=lod2)
- [sketchup-projects](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/sketchup-projects): SketchUp projects modelled according to [this guideline](https://creating-citygml-datasets.readthedocs.io/en/latest/creation-guidelines/lod3-models-based-on-point-clouds.html)
- [citygml-lod3-datasets](https://gitlab.lrz.de/tum-gis/tum2twin-datasets/-/tree/main/citygml-lod3-datasets): Exported CityGML v2 LOD3 building models

The file names follow the GML IDs of the [LDBV](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=lod2).

## 🧪 Model Collection

The goal of tum2twin is to contribute to a collection of different representations of the TUM campus and its surroundings to promote research and development of new methods.

- [LDBV](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=lod2): tum2twin follows and preserves the structure of the official LOD2 building models (tile [690_5336](https://download1.bayernwolke.de/a/lod2/citygml/690_5336.gml) and [690_5334](https://download1.bayernwolke.de/a/lod2/citygml/690_5334.gml))
- [TUM-FAÇADE](https://github.com/oloocki/tum-facade): MLS point clouds with facade-level labels

## 🛠️ Contributing

If you find any errors or deficiencies, please create an [issue](https://github.com/tum-gis/tum2twin/issues).
Improvements and extensions of the models are also highly welcome.

## 🎓 Research

This is a placeholder for publications that use these models.

## 🤝 Acknowlegement

- [Landesamt für Digitalisierung,
Breitband und Vermessung (LDBV)](https://www.ldbv.bayern.de) for their great [open data](https://geodaten.bayern.de/opengeodata/) offering
- [AI4TWINNING](https://www.mdsi.tum.de/gni/gni-funded-projects/ai4twinning/), the project which is facilitating the development of the LoD3 models. 
- [3D Mapping Solutions](https://www.3d-mapping.de/home/) for providing high-grade 3D point clouds within the scope of the MoFa project
