<img src="https://github.com/ethz-asl/maplab/wiki/readme_images/maplab.png" width="400">

# Welcome to maplab
*Ubuntu 14.04+ROS indigo* and *Ubuntu 16.04+ROS kinetic*: [![Build Status](https://jenkins.asl.ethz.ch/buildStatus/icon?job=maplab_nightly)](https://jenkins.asl.ethz.ch/job/maplab_nightly)

This repository contains **maplab**,  an  open,  research-oriented visual-inertial  mapping  framework, written  in  C++,  for  processing  and  manipulating  multi-session  maps.
On  the  one  hand, maplab  can  be  considered  as  a  ready-to-use  visual-inertial mapping  and  localization  system.
On  the  other  hand,  maplab provides  the  research  community  with  a  collection  of  multi-session mapping tools that include map merging, visual-inertial batch optimization, and loop closure.

<img src="https://github.com/ethz-asl/maplab/wiki/readme_images/rovioli.png" width="200">

Furthermore, it includes an online frontend, **ROVIOLI**, that can create visual-inertial maps and also track a global drift-free pose within a localization map.

For documentation, tutorials and datasets, please visit the [wiki](https://github.com/ethz-asl/maplab/wiki).

Please cite the [following paper](https://www.researchgate.net/publication/321332545_maplab_An_Open_Framework_for_Research_in_Visual-inertial_Mapping_and_Localization) when using maplab for your research:

```bibtex
@article{schneider2018maplab,
  title={maplab: An Open Framework for Research in Visual-inertial Mapping and Localization},
  author={Schneider, Thomas and Dymczyk, Marcin and Fehr, Marius and Egger, Kevin and
          Lynen, Simon and Gilitschenski, Igor and Siegwart, Roland}
  year={2018}
}
```

## Installation and getting started

The following articles help you with getting started with maplab and ROVIOLI:

- [Installation on Ubuntu 14.04 or 16.04](https://github.com/ethz-asl/maplab/wiki/Installation-Ubuntu)
- [Introduction to the maplab framework](https://github.com/ethz-asl/maplab/wiki/Introduction-to-the-Maplab-Framework)
- [Structure of the framework](https://github.com/ethz-asl/maplab/wiki/Structure-of-the-framework)
- [Running ROVIOLI in VIO mode](https://github.com/ethz-asl/maplab/wiki/Running-ROVIOLI-in-VIO-mode)
- [Basic console usage](https://github.com/ethz-asl/maplab/wiki/Basic-Console-Usage)
- [Console map management](https://github.com/ethz-asl/maplab/wiki/Console-map-management)

More detailed information can be found in the [wiki pages](https://github.com/ethz-asl/maplab/wiki).

## Features

### Robust visual-inertial estimation with localization

### Consistent map merging and refinement
![cla](https://github.com/ethz-asl/maplab/wiki/readme_images/cla.png)

### Large-scale map processing
![largescale](https://github.com/ethz-asl/maplab/wiki/readme_images/largescale.gif)

### Dense reconstruction
![stereo](https://github.com/ethz-asl/maplab/wiki/readme_images/stereo.png)

### PMVS reconstruction
![pmvs](https://github.com/ethz-asl/maplab/wiki/readme_images/pmvs.png)

### Convenient research interfaces
![topomap](https://github.com/ethz-asl/maplab/wiki/readme_images/topomap.png)

### Extensively tested on real robots
![robots](https://github.com/ethz-asl/maplab/wiki/readme_images/robots.jpg)

## Research Results

The maplab framework has been used as an experimental platform for numerous scientific publications. For a complete list of publications please refer to:

[Research based on maplab](https://github.com/ethz-asl/maplab/wiki/Related-Research)


## Additional Citations

Certain components of maplab are directly using the code of the following publications:

 * Localization:
   ```bibtex
   @inproceedings{lynen2015get,
     title={Get Out of My Lab: Large-scale, Real-Time Visual-Inertial Localization.},
     author={Lynen, Simon and Sattler, Torsten and Bosse, Michael and Hesch, Joel A and Pollefeys, Marc and Siegwart, Roland},
     booktitle={Robotics: Science and Systems},
     year={2015}
   }
   ```
  * ROVIOLI which is composed of ROVIO + maplab for map building and localization:
    ```bibtex
    @article{bloesch2017iterated,
      title={Iterated extended Kalman filter based visual-inertial odometry using direct photometric feedback},
      author={Bloesch, Michael and Burri, Michael and Omari, Sammy and Hutter, Marco and Siegwart, Roland},
      journal={The International Journal of Robotics Research},
      volume={36},
      number={10},
      pages={1053--1072},
      year={2017},
      publisher={SAGE Publications Sage UK: London, England}
    }
    ```

## Credits
### Authors

 * Thomas Schneider
 * Marcin Dymczyk
 * Marius Fehr
 * Kevin Egger
 * Simon Lynen
 * Mathias Bürki
 * Titus Cieslewski
 * Timo Hinzmann
 * Mathias Gehrig
 
For a complete list of contributors, have a look at [CONTRIBUTORS.md](https://github.com/ethz-asl/maplab/blob/master/CONTRIBUTORS.md)
