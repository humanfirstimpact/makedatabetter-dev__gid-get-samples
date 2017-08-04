## gid-table-samples

A data component for fetching rows and columns of the specified table.

    <gid-get-samples columns="col-id1,col-id2.." tabledata = {{tabledata}}></gid-get-samples>
    
The property 'user' is mandatory.

If `api-url` is not provided, the component will display sample output for specified entity.

API endpoint:

    GET /samples?columns=id1,id2,id3&limit=50

Input:

- columns : List of Column Ids (mandatory query param)
- limit : limit by row (optional query Param)



Output:

- Samples for provided Column IDs

The output of this components will be as follows:

	   {
		"columns": [{
			"id": "200010",
			"label": "shipstate"
		}, {
			"id": "200001",
			"label": "id"
		}, {
			"id": "200007",
			"label": "ship-date"
		}, {
			"id": "200006",
			"label": "amount"
		}, {
			"id": "200009",
			"label": "ship-city"
		}, {
			"id": "200008",
			"label": "ship-address"
		}, {
			"id": "200003",
			"label": "product_code"
		}, {
			"id": "200002",
			"label": "user_name"
		}, {
			"id": "200005",
			"label": "order_date"
		}, {
			"id": "200004",
			"label": "quantity"
		}],
		"rows": [
		[
			 "Florida",
			 "83",
			 "7/3/2016",
			 "$7.94",
			"Kansas City",
			 "10790 Wayridge Park",
			 "YI-722",
			"ccostin11",
			 "4/17/2017",
			"17"
		], [
			 "Texas",
			"70",
			 "1/18/2017",
			 "$35.29",
			"Washington",
			"6723 Duke Circle",
			 "UR-391",
			"jburgen27",
			 "5/18/2016",
			"41"
		]]
	}



## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
