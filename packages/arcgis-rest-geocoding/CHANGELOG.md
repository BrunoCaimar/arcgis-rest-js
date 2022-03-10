# @esri/arcgis-rest-geocoding [4.0.0-beta.3](https://github.com/Esri/arcgis-rest-js/compare/@esri/arcgis-rest-geocoding@4.0.0-beta.2...@esri/arcgis-rest-geocoding@4.0.0-beta.3) (2022-03-10)


### Bug Fixes

* add package.json files to builds for individual build types ([#955](https://github.com/Esri/arcgis-rest-js/issues/955)) ([c162125](https://github.com/Esri/arcgis-rest-js/commit/c16212594f0b914425548be5d61d7435d54a2718))





### Dependencies

* **@esri/arcgis-rest-request:** upgraded to 4.0.0-beta.3

# @esri/arcgis-rest-geocoding [4.0.0-beta.2](https://github.com/Esri/arcgis-rest-js/compare/@esri/arcgis-rest-geocoding@4.0.0-beta.1...@esri/arcgis-rest-geocoding@4.0.0-beta.2) (2022-03-02)


### Features

* **arcgis-rest-request:** rewrite oauth 2 functions to use PKCE ([e49f88c](https://github.com/Esri/arcgis-rest-js/commit/e49f88c700694aed472733527124c4d0d54e45d6))





### Dependencies

* **@esri/arcgis-rest-request:** upgraded to 4.0.0-beta.2

# @esri/arcgis-rest-geocoding 1.0.0-beta.1 (2022-02-17)


### Bug Fixes

* **bulk geocoding:** clean up code in bulk geocoding ([5e28028](https://github.com/Esri/arcgis-rest-js/commit/5e28028ff998422ce300afa4bf6fb0284b7cc5a8)), closes [#630](https://github.com/Esri/arcgis-rest-js/issues/630)
* **geocode:** ensure the magicKey property is passed through. ([#603](https://github.com/Esri/arcgis-rest-js/issues/603)) ([cc2c352](https://github.com/Esri/arcgis-rest-js/commit/cc2c352accd8b0090177f3b45fec68d95431b96e)), closes [#601](https://github.com/Esri/arcgis-rest-js/issues/601)


### Code Refactoring

* remove the word Request from custom geocoding RequestOptions interfaces ([f8c6255](https://github.com/Esri/arcgis-rest-js/commit/f8c6255ea471a1861cbbacdf03b1beb584148a8f))


### BREAKING CHANGES

* IGeocodeRequesttOptions is now IGeocodeOptions, IBulkGeocodingRequestOptions is now
IBulkGeocodeOptions





### Dependencies

* **@esri/arcgis-rest-request:** upgraded to 1.0.0-beta.1
