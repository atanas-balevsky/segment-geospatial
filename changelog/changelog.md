# Changelog

## v0.5.0 - May 10, 2023

**New Features**

-   Added support for input prompts (#30)

**Improvements**

-   Fixed the batch processing bug (#29)

**Demos**

![](https://i.imgur.com/GV7Rzxt.gif)

## v0.4.0 - May 6, 2023

**New Features**

-   Added new methods to `SamGeo` class, including `show_masks`, `save_masks`, `show_anns`, making it much easier to save segmentation results in GeoTIFF and vector formats.
-   Added new functions to `common` module, including `array_to_image`, `show_image`, `download_file`, `overlay_images`, `blend_images`, and `update_package`
-   Added tow more notebooks, including [automatic_mask_generator](https://samgeo.gishub.org/examples/automatic_mask_generator/) and [satellite-predictor](https://samgeo.gishub.org/examples/satellite-predictor/)
-   Added `SamGeoPredictor` class

**Improvements**

-   Improved `SamGeo.generate()` method
-   Improved docstrings and API reference
-   Added demos to docs

**Demos**

-   Automatic mask generator

![](https://i.imgur.com/I1IhDgz.gif)

**Contributors**

@darrenwiens

## v0.3.0 - Apr 26, 2023

**New Features**

-   Added several new functions, including `get_basemaps`, `reproject`, `tiff_to_shp`, and `tiff_to_geojson`
-   Added hundereds of new basemaps through xyzservices

**Improvement**

-   Fixed `tiff_to_vector` crs bug #12
-   Add `crs` parameter to `tms_to_geotiff`

## v0.2.0 - Apr 21, 2023

**New Features**

-   Added notebook example
-   Added `SamGeo.generate` method
-   Added `SamGeo.tiff_to_vector` method

## v0.1.0 - Apr 19, 2023

**New Features**

-   Added `SamGeo` class
-   Added GitHub Actions
-   Added notebook example

## v0.0.1 - Apr 18, 2023

Initial release
