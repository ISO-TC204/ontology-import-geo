# GeoSPARQL Ontology

An RDF/OWL vocabulary for representing spatial information

NOTE: This ontology has been tweaked to allow it to properly generate the documentation for this site. For example, the ending of the ontology IRI was changed from a `#` to a `/` to allow hyperlinks to work correctly, this note was added, etc.

**Copyright**: (c) 2021 Open Geospatial Consortium

**License**: [https://www.ogc.org/license](https://www.ogc.org/license)


## Ontology concepts

### Classes

- [Feature](classes/Feature.md)
- [Feature Collection](classes/FeatureCollection.md)
- [Geometry](classes/Geometry.md)
- [Geometry Collection](classes/GeometryCollection.md)
- [Spatial Object](classes/SpatialObject.md)
- [Spatial Object Collection](classes/SpatialObjectCollection.md)

### Properties

- [asDGGS](properties/asDGGS.md)
- [asGeoJSON](properties/asGeoJSON.md)
- [asGML](properties/asGML.md)
- [asKML](properties/asKML.md)
- [asWKT](properties/asWKT.md)
- [coordinateDimension](properties/coordinateDimension.md)
- [defaultGeometry](properties/defaultGeometry.md)
- [dimension](properties/dimension.md)
- [ehContains](properties/ehContains.md)
- [ehCoveredBy](properties/ehCoveredBy.md)
- [ehCovers](properties/ehCovers.md)
- [ehDisjoint](properties/ehDisjoint.md)
- [ehEquals](properties/ehEquals.md)
- [ehInside](properties/ehInside.md)
- [ehMeet](properties/ehMeet.md)
- [ehOverlap](properties/ehOverlap.md)
- [hasArea](properties/hasArea.md)
- [hasBoundingBox](properties/hasBoundingBox.md)
- [hasCentroid](properties/hasCentroid.md)
- [hasDefaultGeometry](properties/hasDefaultGeometry.md)
- [hasGeometry](properties/hasGeometry.md)
- [hasLength](properties/hasLength.md)
- [hasMetricArea](properties/hasMetricArea.md)
- [hasMetricLength](properties/hasMetricLength.md)
- [hasMetricPerimeterLength](properties/hasMetricPerimeterLength.md)
- [hasMetricSize](properties/hasMetricSize.md)
- [hasMetricSpatialAccuracy](properties/hasMetricSpatialAccuracy.md)
- [hasMetricSpatialResolution](properties/hasMetricSpatialResolution.md)
- [hasMetricVolume](properties/hasMetricVolume.md)
- [hasPerimeterLength](properties/hasPerimeterLength.md)
- [hasSerialization](properties/hasSerialization.md)
- [hasSize](properties/hasSize.md)
- [hasSpatialAccuracy](properties/hasSpatialAccuracy.md)
- [hasSpatialResolution](properties/hasSpatialResolution.md)
- [hasVolume](properties/hasVolume.md)
- [isEmpty](properties/isEmpty.md)
- [isSimple](properties/isSimple.md)
- [rcc8dc](properties/rcc8dc.md)
- [rcc8ec](properties/rcc8ec.md)
- [rcc8eq](properties/rcc8eq.md)
- [rcc8ntpp](properties/rcc8ntpp.md)
- [rcc8ntppi](properties/rcc8ntppi.md)
- [rcc8po](properties/rcc8po.md)
- [rcc8tpp](properties/rcc8tpp.md)
- [rcc8tppi](properties/rcc8tppi.md)
- [sfContains](properties/sfContains.md)
- [sfCrosses](properties/sfCrosses.md)
- [sfDisjoint](properties/sfDisjoint.md)
- [sfEquals](properties/sfEquals.md)
- [sfIntersects](properties/sfIntersects.md)
- [sfOverlaps](properties/sfOverlaps.md)
- [sfTouches](properties/sfTouches.md)
- [sfWithin](properties/sfWithin.md)
- [spatialDimension](properties/spatialDimension.md)

### Datatypes

- [dggsLiteral](datatypes/dggsLiteral.md)
- [geoJSONLiteral](datatypes/geoJSONLiteral.md)
- [gmlLiteral](datatypes/gmlLiteral.md)
- [kmlLiteral](datatypes/kmlLiteral.md)
- [wktLiteral](datatypes/wktLiteral.md)


The formal definition of this ontology is available in [TURTLE Syntax](geo.ttl).
