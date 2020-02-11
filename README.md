Based on: https://github.com/bmcbride/geojson-share-maps

### Direct Map Links
- Embedded link: ```<script src="https://embed.github.com/view/geojson/mds08011/KimberlyTravel/master/KS_Map.geojson"></script>```
- Raw geojson: https://raw.githubusercontent.com/mds08011/KimberlyTravel/master/KS_Map.geojson

### Features:

- Fullscreen mobile-friendly map template with responsive navbar and modal popups
- Built on [Bootstrap](http://getbootstrap.com/) and [Leaflet/Mapbox](http://leafletjs.com/) frameworks
- Supports GeoJSON feature styling via [simplestyle-spec](https://github.com/mapbox/simplestyle-spec/)
- Sidebar with basic filtering and sorting via [List.js](http://www.listjs.com/)


### URL Parameters:

| Parameter     | Options                 | Default       | Description                                              | Required |
| ------------- | ----------------------- | ------------- | -------------------------------------------------------- | -------- |
| _src_         | Web accessible GeoJSON  | NA            | URL to GeoJSON source                                    | True     |
| _title_       | Any string              | GeoJSON Data  | navbar, app title                                        | False    |
| _logo_        | Any accessible URL      | NA            | URL to a custom navbar logo                              | False    |
| _title_field_ | Any valid property      | First property| Field used for marker/sidebar title                      | False    |
| _fields_      | Any valid properties    | All           | Comma separated list of specific properties to show      | False    |
| _attribution_ | Any string              | NA            | Source attribution added to text in bottom right of map  | False    |
| _cluster_     | true / false            | True          | Should markers be clustered?                             | False    |

### Other Resources

- Validate geojson files: http://geojsonlint.com/
- Visualize and edit geojson (Option 1): https://geojson.io
- Visualize and edit geojson (Option 2): https://geojson.net/
- Visualize and edit geojson (Option 3): https://geoman.io/geojson-editor
- Using geojson on Github: https://help.github.com/en/github/managing-files-in-a-repository/mapping-geojson-files-on-github
