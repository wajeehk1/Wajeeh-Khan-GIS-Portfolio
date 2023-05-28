<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="initial-scale=1,user-scalable=no,maximum-scale=1,width=device-width">
        <meta name="mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="stylesheet" href="css/leaflet.css"><link rel="stylesheet" href="css/L.Control.Locate.min.css">
        <link rel="stylesheet" href="css/qgis2web.css"><link rel="stylesheet" href="css/fontawesome-all.min.css">
        <link rel="stylesheet" href="css/filter.css">
<link rel="stylesheet" href="css/nouislider.min.css">
        <link rel="stylesheet" href="css/leaflet-measure.css">
        <style>
        #map {
            width: 723px;
            height: 843px;
        }
        </style>
        <title></title>
    </head>
    <body>
        <div id="map">
        </div>
        <script src="js/qgis2web_expressions.js"></script>
        <script src="js/leaflet.js"></script><script src="js/L.Control.Locate.min.js"></script>
        <script src="js/multi-style-layer.js"></script>
        <script src="js/leaflet-svg-shape-markers.min.js"></script>
        <script src="js/leaflet.rotatedMarker.js"></script>
        <script src="js/leaflet.pattern.js"></script>
        <script src="js/leaflet-hash.js"></script>
        <script src="js/Autolinker.min.js"></script>
        <script src="js/rbush.min.js"></script>
        <script src="js/labelgun.min.js"></script>
        <script src="js/labels.js"></script>
        <script src="js/leaflet-measure.js"></script>
        <script src="js/tailDT.js"></script>
<script src="js/nouislider.min.js"></script>
<script src="js/wNumb.js"></script>
        <script src="data/DomesticWaterWithdrawalMgalday_1.js"></script>
        <script src="data/CRBHydrologicalBoundary_2.js"></script>
        <script src="data/MajorCities_3.js"></script>
        <script>
        var highlightLayer;
        function highlightFeature(e) {
            highlightLayer = e.target;

            if (e.target.feature.geometry.type === 'LineString') {
              highlightLayer.setStyle({
                color: '#ffff00',
              });
            } else {
              highlightLayer.setStyle({
                fillColor: '#ffff00',
                fillOpacity: 1
              });
            }
            highlightLayer.openPopup();
        }
        var map = L.map('map', {
            zoomControl:true, maxZoom:28, minZoom:1
        }).fitBounds([[22.89620370163165,-122.62460522784443],[50.50114632623054,-98.95853669950223]]);
        var hash = new L.Hash(map);
        map.attributionControl.setPrefix('<a href="https://github.com/tomchadwin/qgis2web" target="_blank">qgis2web</a> &middot; <a href="https://leafletjs.com" title="A JS library for interactive maps">Leaflet</a> &middot; <a href="https://qgis.org">QGIS</a>');
        var autolinker = new Autolinker({truncate: {length: 30, location: 'smart'}});
        L.control.locate({locateOptions: {maxZoom: 19}}).addTo(map);
        var measureControl = new L.Control.Measure({
            position: 'topleft',
            primaryLengthUnit: 'feet',
            secondaryLengthUnit: 'miles',
            primaryAreaUnit: 'sqfeet',
            secondaryAreaUnit: 'sqmiles'
        });
        measureControl.addTo(map);
        document.getElementsByClassName('leaflet-control-measure-toggle')[0]
        .innerHTML = '';
        document.getElementsByClassName('leaflet-control-measure-toggle')[0]
        .className += ' fas fa-ruler';
        var bounds_group = new L.featureGroup([]);
        function setBounds() {
        }
        map.createPane('pane_OpenStreetMap_0');
        map.getPane('pane_OpenStreetMap_0').style.zIndex = 400;
        var layer_OpenStreetMap_0 = L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
            pane: 'pane_OpenStreetMap_0',
            opacity: 1.0,
            attribution: '',
            minZoom: 1,
            maxZoom: 28,
            minNativeZoom: 0,
            maxNativeZoom: 19
        });
        layer_OpenStreetMap_0;
        map.addLayer(layer_OpenStreetMap_0);
        function pop_DomesticWaterWithdrawalMgalday_1(feature, layer) {
            layer.on({
                mouseout: function(e) {
                    for (i in e.target._eventParents) {
                        e.target._eventParents[i].resetStyle(e.target);
                    }
                    if (typeof layer.closePopup == 'function') {
                        layer.closePopup();
                    } else {
                        layer.eachLayer(function(feature){
                            feature.closePopup()
                        });
                    }
                },
                mouseover: highlightFeature,
            });
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(feature.properties['NAME'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">mhniE</th>\
                        <td>' + (feature.properties['mhniE'] !== null ? autolinker.link(feature.properties['mhniE'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">tot_raceE</th>\
                        <td>' + (feature.properties['tot_raceE'] !== null ? autolinker.link(feature.properties['tot_raceE'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">per_white</th>\
                        <td>' + (feature.properties['per_white'] !== null ? autolinker.link(feature.properties['per_white'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTYFP</th>\
                        <td>' + (feature.properties['COUNTYFP'] !== null ? autolinker.link(feature.properties['COUNTYFP'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">State_Code</th>\
                        <td>' + (feature.properties['State_Code'] !== null ? autolinker.link(feature.properties['State_Code'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">State_Name</th>\
                        <td>' + (feature.properties['State_Name'] !== null ? autolinker.link(feature.properties['State_Name'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">County_Cod</th>\
                        <td>' + (feature.properties['County_Cod'] !== null ? autolinker.link(feature.properties['County_Cod'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">County_Nam</th>\
                        <td>' + (feature.properties['County_Nam'] !== null ? autolinker.link(feature.properties['County_Nam'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Total_Popu</th>\
                        <td>' + (feature.properties['Total_Popu'] !== null ? autolinker.link(feature.properties['Total_Popu'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Domestic_d</th>\
                        <td>' + (feature.properties['Domestic_d'] !== null ? autolinker.link(feature.properties['Domestic_d'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Shape__Are</th>\
                        <td>' + (feature.properties['Shape__Are'] !== null ? autolinker.link(feature.properties['Shape__Are'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">Shape__Len</th>\
                        <td>' + (feature.properties['Shape__Len'] !== null ? autolinker.link(feature.properties['Shape__Len'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_DomesticWaterWithdrawalMgalday_1_0(feature) {
            if (feature.properties['Domestic_d'] >= 0.070000 && feature.properties['Domestic_d'] <= 19.630000 ) {
                return {
                pane: 'pane_DomesticWaterWithdrawalMgalday_1',
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(247,251,255,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['Domestic_d'] >= 19.630000 && feature.properties['Domestic_d'] <= 65.340000 ) {
                return {
                pane: 'pane_DomesticWaterWithdrawalMgalday_1',
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(200,220,240,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['Domestic_d'] >= 65.340000 && feature.properties['Domestic_d'] <= 146.470000 ) {
                return {
                pane: 'pane_DomesticWaterWithdrawalMgalday_1',
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(115,178,216,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['Domestic_d'] >= 146.470000 && feature.properties['Domestic_d'] <= 610.120000 ) {
                return {
                pane: 'pane_DomesticWaterWithdrawalMgalday_1',
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(41,121,185,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['Domestic_d'] >= 610.120000 && feature.properties['Domestic_d'] <= 927.690000 ) {
                return {
                pane: 'pane_DomesticWaterWithdrawalMgalday_1',
                opacity: 1,
                color: 'rgba(255,255,255,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(8,48,107,1.0)',
                interactive: true,
            }
            }
        }
        map.createPane('pane_DomesticWaterWithdrawalMgalday_1');
        map.getPane('pane_DomesticWaterWithdrawalMgalday_1').style.zIndex = 401;
        map.getPane('pane_DomesticWaterWithdrawalMgalday_1').style['mix-blend-mode'] = 'normal';
        var layer_DomesticWaterWithdrawalMgalday_1 = new L.geoJson(json_DomesticWaterWithdrawalMgalday_1, {
            attribution: '',
            interactive: true,
            dataVar: 'json_DomesticWaterWithdrawalMgalday_1',
            layerName: 'layer_DomesticWaterWithdrawalMgalday_1',
            pane: 'pane_DomesticWaterWithdrawalMgalday_1',
            onEachFeature: pop_DomesticWaterWithdrawalMgalday_1,
            style: style_DomesticWaterWithdrawalMgalday_1_0,
        });
        bounds_group.addLayer(layer_DomesticWaterWithdrawalMgalday_1);
        map.addLayer(layer_DomesticWaterWithdrawalMgalday_1);
        function pop_CRBHydrologicalBoundary_2(feature, layer) {
            layer.on({
                mouseout: function(e) {
                    for (i in e.target._eventParents) {
                        e.target._eventParents[i].resetStyle(e.target);
                    }
                    if (typeof layer.closePopup == 'function') {
                        layer.closePopup();
                    } else {
                        layer.eachLayer(function(feature){
                            feature.closePopup()
                        });
                    }
                },
                mouseover: highlightFeature,
            });
            var popupContent = '<table>\
                    <tr>\
                        <td colspan="2">' + (feature.properties['HU_6_Name'] !== null ? autolinker.link(feature.properties['HU_6_Name'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_CRBHydrologicalBoundary_2_0() {
            return {
                pane: 'pane_CRBHydrologicalBoundary_2',
                opacity: 1,
                color: 'rgba(196,127,16,1.0)',
                dashArray: '',
                lineCap: 'round',
                lineJoin: 'round',
                weight: 2.0,
                fillOpacity: 0,
                interactive: true,
            }
        }
        map.createPane('pane_CRBHydrologicalBoundary_2');
        map.getPane('pane_CRBHydrologicalBoundary_2').style.zIndex = 402;
        map.getPane('pane_CRBHydrologicalBoundary_2').style['mix-blend-mode'] = 'normal';
        var layer_CRBHydrologicalBoundary_2 = new L.geoJson(json_CRBHydrologicalBoundary_2, {
            attribution: '',
            interactive: true,
            dataVar: 'json_CRBHydrologicalBoundary_2',
            layerName: 'layer_CRBHydrologicalBoundary_2',
            pane: 'pane_CRBHydrologicalBoundary_2',
            onEachFeature: pop_CRBHydrologicalBoundary_2,
            style: style_CRBHydrologicalBoundary_2_0,
        });
        bounds_group.addLayer(layer_CRBHydrologicalBoundary_2);
        map.addLayer(layer_CRBHydrologicalBoundary_2);
        function pop_MajorCities_3(feature, layer) {
            layer.on({
                mouseout: function(e) {
                    for (i in e.target._eventParents) {
                        e.target._eventParents[i].resetStyle(e.target);
                    }
                    if (typeof layer.closePopup == 'function') {
                        layer.closePopup();
                    } else {
                        layer.eachLayer(function(feature){
                            feature.closePopup()
                        });
                    }
                },
                mouseover: highlightFeature,
            });
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">NAME</th>\
                        <td>' + (feature.properties['NAME'] !== null ? autolinker.link(feature.properties['NAME'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">POP_2010</th>\
                        <td>' + (feature.properties['POP_2010'] !== null ? autolinker.link(feature.properties['POP_2010'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTY</th>\
                        <td>' + (feature.properties['COUNTY'] !== null ? autolinker.link(feature.properties['COUNTY'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">COUNTYFIPS</th>\
                        <td>' + (feature.properties['COUNTYFIPS'] !== null ? autolinker.link(feature.properties['COUNTYFIPS'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE</th>\
                        <td>' + (feature.properties['STATE'] !== null ? autolinker.link(feature.properties['STATE'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">STATE_FIPS</th>\
                        <td>' + (feature.properties['STATE_FIPS'] !== null ? autolinker.link(feature.properties['STATE_FIPS'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_MajorCities_3_0(feature) {
            if (feature.properties['POP_2010'] >= 52527.000000 && feature.properties['POP_2010'] <= 67116.200000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 1.833334,
                opacity: 1,
                color: 'rgba(184,8,8,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(184,8,8,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['POP_2010'] >= 67116.200000 && feature.properties['POP_2010'] <= 107773.600000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 5.04166,
                opacity: 1,
                color: 'rgba(184,8,8,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(184,8,8,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['POP_2010'] >= 107773.600000 && feature.properties['POP_2010'] <= 370429.600000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 8.25,
                opacity: 1,
                color: 'rgba(184,8,8,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(184,8,8,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['POP_2010'] >= 370429.600000 && feature.properties['POP_2010'] <= 590316.800000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 11.45834,
                opacity: 1,
                color: 'rgba(184,8,8,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(184,8,8,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['POP_2010'] >= 590316.800000 && feature.properties['POP_2010'] <= 3792621.000000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 14.66666,
                opacity: 1,
                color: 'rgba(184,8,8,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(184,8,8,1.0)',
                interactive: true,
            }
            }
        }
        function style_MajorCities_3_1(feature) {
            if (feature.properties['POP_2010'] >= 52527.000000 && feature.properties['POP_2010'] <= 67116.200000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 2.0,
                opacity: 1,
                color: 'rgba(255,0,0,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,0,0,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['POP_2010'] >= 67116.200000 && feature.properties['POP_2010'] <= 107773.600000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 5.5,
                opacity: 1,
                color: 'rgba(255,0,0,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,0,0,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['POP_2010'] >= 107773.600000 && feature.properties['POP_2010'] <= 370429.600000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 9.0,
                opacity: 1,
                color: 'rgba(255,0,0,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,0,0,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['POP_2010'] >= 370429.600000 && feature.properties['POP_2010'] <= 590316.800000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 12.5,
                opacity: 1,
                color: 'rgba(255,0,0,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,0,0,1.0)',
                interactive: true,
            }
            }
            if (feature.properties['POP_2010'] >= 590316.800000 && feature.properties['POP_2010'] <= 3792621.000000 ) {
                return {
                pane: 'pane_MajorCities_3',
                radius: 16.0,
                opacity: 1,
                color: 'rgba(255,0,0,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0,
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(255,0,0,1.0)',
                interactive: true,
            }
            }
        }
        map.createPane('pane_MajorCities_3');
        map.getPane('pane_MajorCities_3').style.zIndex = 403;
        map.getPane('pane_MajorCities_3').style['mix-blend-mode'] = 'normal';
        var layer_MajorCities_3 = new L.geoJson.multiStyle(json_MajorCities_3, {
            attribution: '',
            interactive: true,
            dataVar: 'json_MajorCities_3',
            layerName: 'layer_MajorCities_3',
            pane: 'pane_MajorCities_3',
            onEachFeature: pop_MajorCities_3,
            pointToLayers: [function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.shapeMarker(latlng, style_MajorCities_3_0(feature));
            },function (feature, latlng) {
                var context = {
                    feature: feature,
                    variables: {}
                };
                return L.shapeMarker(latlng, style_MajorCities_3_1(feature));
            },
        ]});
        bounds_group.addLayer(layer_MajorCities_3);
        map.addLayer(layer_MajorCities_3);
        var baseMaps = {};
        L.control.layers(baseMaps,{'Major Cities<br /><table><tr><td style="text-align: center;"><img src="legend/MajorCities_3_52527671160.png" /></td><td>52527 - 67116</td></tr><tr><td style="text-align: center;"><img src="legend/MajorCities_3_671161077741.png" /></td><td>67116 - 107774</td></tr><tr><td style="text-align: center;"><img src="legend/MajorCities_3_1077743704302.png" /></td><td>107774 - 370430</td></tr><tr><td style="text-align: center;"><img src="legend/MajorCities_3_3704305903173.png" /></td><td>370430 - 590317</td></tr><tr><td style="text-align: center;"><img src="legend/MajorCities_3_59031737926214.png" /></td><td>590317 - 3792621</td></tr></table>': layer_MajorCities_3,'<img src="legend/CRBHydrologicalBoundary_2.png" /> CRB Hydrological Boundary': layer_CRBHydrologicalBoundary_2,'Domestic Water Withdrawal (Mgal/day)<br /><table><tr><td style="text-align: center;"><img src="legend/DomesticWaterWithdrawalMgalday_1_0200.png" /></td><td>0 - 20</td></tr><tr><td style="text-align: center;"><img src="legend/DomesticWaterWithdrawalMgalday_1_20651.png" /></td><td>20 - 65</td></tr><tr><td style="text-align: center;"><img src="legend/DomesticWaterWithdrawalMgalday_1_651462.png" /></td><td>65 - 146</td></tr><tr><td style="text-align: center;"><img src="legend/DomesticWaterWithdrawalMgalday_1_1466103.png" /></td><td>146 - 610</td></tr><tr><td style="text-align: center;"><img src="legend/DomesticWaterWithdrawalMgalday_1_6109284.png" /></td><td>610 - 928</td></tr></table>': layer_DomesticWaterWithdrawalMgalday_1,"OpenStreetMap": layer_OpenStreetMap_0,}).addTo(map);
        setBounds();
        var mapDiv = document.getElementById('map');
        var row = document.createElement('div');
        row.className="row";
        row.id="all";
        row.style.height = "100%";
        var col1 = document.createElement('div');
        col1.className="col9";
        col1.id = "mapWindow";
        col1.style.height = "99%";
        col1.style.width = "80%";
        col1.style.display = "inline-block";
        var col2 = document.createElement('div');
        col2.className="col3";
        col2.id = "menu";
        col2.style.display = "inline-block";
        mapDiv.parentNode.insertBefore(row, mapDiv);
        document.getElementById("all").appendChild(col1);
        document.getElementById("all").appendChild(col2);
        col1.appendChild(mapDiv)
        var Filters = {"Domestic_d": "real"};
        function filterFunc() {
          map.eachLayer(function(lyr){
          if ("options" in lyr && "dataVar" in lyr["options"]){
            features = this[lyr["options"]["dataVar"]].features.slice(0);
            try{
              for (key in Filters){
                keyS = key.replace(/[^a-zA-Z0-9_]/g, "")
                if (Filters[key] == "str" || Filters[key] == "bool"){
                  var selection = [];
                  var options = document.getElementById("sel_" + keyS).options
                  for (var i=0; i < options.length; i++) {
                    if (options[i].selected) selection.push(options[i].value);
                  }
                    try{
                      if (key in features[0].properties){
                        for (i = features.length - 1;
                          i >= 0; --i){
                          if (selection.indexOf(
                          features[i].properties[key])<0
                          && selection.length>0) {
                          features.splice(i,1);
                          }
                        }
                      }
                    } catch(err){
                  }
                }
                if (Filters[key] == "int"){
                  sliderVals =  document.getElementById(
                    "div_" + keyS).noUiSlider.get();
                  try{
                    if (key in features[0].properties){
                    for (i = features.length - 1; i >= 0; --i){
                      if (parseInt(features[i].properties[key])
                          < sliderVals[0]
                          || parseInt(features[i].properties[key])
                          > sliderVals[1]){
                            features.splice(i,1);
                          }
                        }
                      }
                    } catch(err){
                    }
                  }
                if (Filters[key] == "real"){
                  sliderVals =  document.getElementById(
                    "div_" + keyS).noUiSlider.get();
                  try{
                    if (key in features[0].properties){
                    for (i = features.length - 1; i >= 0; --i){
                      if (features[i].properties[key]
                          < sliderVals[0]
                          || features[i].properties[key]
                          > sliderVals[1]){
                            features.splice(i,1);
                          }
                        }
                      }
                    } catch(err){
                    }
                  }
                if (Filters[key] == "date"
                  || Filters[key] == "datetime"
                  || Filters[key] == "time"){
                  try{
                    if (key in features[0].properties){
                      HTMLkey = key.replace(/[&\/\\#,+()$~%.'":*?<>{} ]/g, '');
                      startdate = document.getElementById("dat_" +
                        HTMLkey + "_date1").value.replace(" ", "T");
                      enddate = document.getElementById("dat_" +
                        HTMLkey + "_date2").value.replace(" ", "T");
                      for (i = features.length - 1; i >= 0; --i){
                        if (features[i].properties[key] < startdate
                          || features[i].properties[key] > enddate){
                          features.splice(i,1);
                        }
                      }
                    }
                  } catch(err){
                  }
                }
              }
            } catch(err){
            }
          this[lyr["options"]["layerName"]].clearLayers();
          this[lyr["options"]["layerName"]].addData(features);
          }
          })
        }
            document.getElementById("menu").appendChild(
                document.createElement("div"));
            var div_Domestic_d = document.createElement("div");
            div_Domestic_d.id = "div_Domestic_d";
            div_Domestic_d.className = "slider";
            document.getElementById("menu").appendChild(div_Domestic_d);
            var lab_Domestic_d = document.createElement('div');
            lab_Domestic_d.innerHTML  = 'Domestic_d: <span id="val_Domestic_d"></span>';
            lab_Domestic_d.className = 'filterlabel';
            document.getElementById("menu").appendChild(lab_Domestic_d);
            var reset_Domestic_d = document.createElement('div');
            reset_Domestic_d.innerHTML = 'clear filter';
            reset_Domestic_d.className = 'filterlabel';
            lab_Domestic_d.className = 'filterlabel';
            reset_Domestic_d.onclick = function() {
                sel_Domestic_d.noUiSlider.reset();
            };
            document.getElementById("menu").appendChild(reset_Domestic_d);
            var sel_Domestic_d = document.getElementById('div_Domestic_d');
            noUiSlider.create(sel_Domestic_d, {
                connect: true,
                start: [0.07, 927.69],
                range: {
                min: 0.07,
                max: 927.69
                }
            });
            sel_Domestic_d.noUiSlider.on('update', function (values) {
            val_Domestic_d = document.getElementById('val_Domestic_d');
            val_Domestic_d.innerHTML = values.join(' - ');
                filterFunc()
            });
        </script>
    </body>
</html>
