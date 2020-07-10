### /collections/{collection_id}/processes/area:retrieve

* **collection_id** (path) Select the collection 
* **bbox** (query) Only features that have a geometry that intersects the bounding box are selected. The bounding box is provided comma separated string made of four numbers: 
  * Lower left corner, coordinate axis 1
  * Lower left corner, coordinate axis 2
  * Upper right corner, coordinate axis 1
  * Upper right corner, coordinate axis 2
* **datetime** (query) as closed interval date and time expressions adhering to RFC 3339. 
Selects features that have a temporal property that intersects the value of the parameter.
defaults to: `2018-05-01T00:00:00/2020-04-01T00:00:00`

Response: 

json representation of the `xarray.DataArray.to_dict()` method

See it in action with this [notebook](../../../lab/tree/examples/area-retrieve.ipynb)

### /collections/{collection_id}/processes/area:aggregate-space

* **collection_id** (path) Select the collection to  Collections
* **bbox** (query) Only features that have a geometry that intersects the bounding box are selected. The bounding box is provided comma separated string made of four numbers: 
  * Lower left corner, coordinate axis 1
  * Lower left corner, coordinate axis 2
  * Upper right corner, coordinate axis 1
  * Upper right corner, coordinate axis 2
* **datetime** (query) as closed interval date and time expressions adhering to RFC 3339. 
Selects features that have a temporal property that intersects the value of the parameter.
defaults to: `2018-05-01T00:00:00/2020-04-01T00:00:00`
* **function** (query) The statistical function(s) to apply when aggregating multiple values to a single value. Available values : min, count, max, std-dev, sum, mean
* **variable** (query) Atheobservable property that should be returned in the response.

json representation of the `xarray.DataArray.to_dict()` method

See it in action with this [notebook](../../../lab/tree/examples/area-aggregate-space.ipynb)

### /collections/{collection_id}/processes/area:aggregate-time-space

* **collection_id** (path) Select the collection to  Collections
* **bbox** (query) Only features that have a geometry that intersects the bounding box are selected. The bounding box is provided comma separated string made of four numbers: 
  * Lower left corner, coordinate axis 1
  * Lower left corner, coordinate axis 2
  * Upper right corner, coordinate axis 1
  * Upper right corner, coordinate axis 2
* **datetime** (query) as closed interval date and time expressions adhering to RFC 3339. 
Selects features that have a temporal property that intersects the value of the parameter.
defaults to: `2018-05-01T00:00:00/2020-04-01T00:00:00`
* **function** (query) The statistical function(s) to apply when aggregating multiple values to a single value. Available values : min, count, max, std-dev, sum, mean
* **variable** (query) Atheobservable property that should be returned in the response.

Response: 

json `{ "<function>": value }`

See it in action with this [notebook](../../../lab/tree/examples/area-aggregate-time-space.ipynb)

### /collections/{collection_id}/processes/area:aggregate-time

* **collection_id** (path) Select the collection to  Collections
* **bbox** (query) Only features that have a geometry that intersects the bounding box are selected. The bounding box is provided comma separated string made of four numbers: 
  * Lower left corner, coordinate axis 1
  * Lower left corner, coordinate axis 2
  * Upper right corner, coordinate axis 1
  * Upper right corner, coordinate axis 2
* **datetime** (query) as closed interval date and time expressions adhering to RFC 3339. 
Selects features that have a temporal property that intersects the value of the parameter.
defaults to: `2018-05-01T00:00:00/2020-04-01T00:00:00`
* **function** (query) The statistical function(s) to apply when aggregating multiple values to a single value. Available values : min, count, max, std-dev, sum, mean
* **variable** (query) Atheobservable property that should be returned in the response.

Response: 

json representation of the `xarray.DataArray.to_dict()` method

See it in action with this [notebook](../../../lab/tree/examples/area-aggregate-time.ipynb)