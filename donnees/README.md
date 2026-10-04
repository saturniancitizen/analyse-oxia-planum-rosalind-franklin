# Sources des données

Les noms ci-dessous correspondent aux fichiers visibles dans le dossier local du projet. Les liens renvoient au paquet officiel **« The Geography of Oxia Planum »**, hébergé par l’archive scientifique planétaire de l’Agence spatiale européenne (ESA). Les rasters d’origine sont volumineux ; ils sont accessibles auprès de l’ESA.

| Fichier | Source officielle | Rôle du produit |
| --- | --- | --- |
| `CASSIS_OP_sRGB_mosaic_4m_april2021.tif` | [Mosaïque CaSSIS en couleurs](https://archives.esac.esa.int/psa/ftp/Guest-Storage-Facility/ExoMars2022-RSOWG_Oxia-Planum_Geography-CaSSIS-CTX_V1.0/02_a_CASSIS_georeferenced_sRGB_mosaic/) | Mosaïque couleur géoréférencée d’Oxia Planum, à environ 4 m par pixel ; elle donne une vue détaillée des couleurs et des textures de surface. |
| `CTX_OXIA_ORI_6m.tif` | [Image orthorectifiée CTX](https://archives.esac.esa.int/psa/ftp/Guest-Storage-Facility/ExoMars2022-RSOWG_Oxia-Planum_Geography-CaSSIS-CTX_V1.0/03_b_CTX_ORI_mosaic/) | Mosaïque d’images CTX corrigées géométriquement, à environ 6 m par pixel ; elle sert de fond cartographique pour examiner le site. |
| `CTX_OXIA_DEM_20m.tif` | [Modèle numérique de terrain CTX](https://archives.esac.esa.int/psa/ftp/Guest-Storage-Facility/ExoMars2022-RSOWG_Oxia-Planum_Geography-CaSSIS-CTX_V1.0/03_d_CTX_DEM_mosaic/) | Modèle du relief à environ 20 m par pixel, complémentaire de l’image CTX. |
| `OxiaPlanum_QuadGrid_1km.dbf` et `OxiaPlanum_QuadGrid_1km.shx` | [Grille de quadrangles et régions géographiques](https://archives.esac.esa.int/psa/ftp/Guest-Storage-Facility/ExoMars2022-RSOWG_Oxia-Planum_Geography-CaSSIS-CTX_V1.0/01_a_quad_grid_and_geographic_regions/) | Éléments associés à la grille de carrés de 1 km utilisée pour repérer les zones d’Oxia Planum. Les fichiers `.dbf` et `.shx` font partie d’un shapefile : il faut aussi télécharger le fichier géométrique `.shp` et les fichiers de projection associés pour utiliser la grille correctement. |

## Documentation et référence scientifique

- [Guide du produit de l’ESA (PDF)](https://archives.esac.esa.int/psa/ftp/Guest-Storage-Facility/ExoMars2022-RSOWG_Oxia-Planum_Geography-CaSSIS-CTX_V1.0/Product_User_Guide_ExoMars2022-RSOWG_Oxia-Planum_Geography-CaSSIS-CTX_V1.0.pdf) — décrit le contenu du paquet, les résolutions, les formats et le contexte des produits.
- [Fawdon et al. (2021), *The geography of Oxia Planum*](https://doi.org/10.1080/17445647.2021.1982035) — article scientifique présentant le cadre géographique et les produits cartographiques du site.
- [Page du paquet de données de l’ESA](https://archives.esac.esa.int/psa/ftp/Guest-Storage-Facility/ExoMars2022-RSOWG_Oxia-Planum_Geography-CaSSIS-CTX_V1.0/) — accès au jeu de données complet.

## À propos des fichiers de la capture

`python-3.13.5-amd64.exe` est un installateur Python pour Windows, pas une donnée scientifique. [La page officielle de Python 3.13.5](https://www.python.org/downloads/release/python-3135/) permet de vérifier la version et de retrouver le téléchargement correspondant.
