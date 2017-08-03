## gid-table-samples

A data component for fetching rows and columns of the specified table.

    <gid-table-samples table = "100007" tabledata = {{tabledata}}></gid-table-samples>
    
The property 'user' is mandatory.

If `api-url` is not provided, the component will display sample output for specified entity.

API endpoint:

    GET /tables/{tableId}/rows

Input:

	- TableId

Output:

	- The table data i.e., rows and columns of the specified table


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
		"rows": [{
			"shipstate": "Florida",
			"id": "83",
			"ship-date": "7/3/2016",
			"amount": "$7.94",
			"ship-city": "Kansas City",
			"ship-address": "10790 Wayridge Park",
			"product_code": "YI-722",
			"user_name": "ccostin11",
			"order_date": "4/17/2017",
			"quantity": "17"
		}, {
			"shipstate": "Texas",
			"id": "70",
			"ship-date": "1/18/2017",
			"amount": "$35.29",
			"ship-city": "Washington",
			"ship-address": "6723 Duke Circle",
			"product_code": "UR-391",
			"user_name": "jburgen27",
			"order_date": "5/18/2016",
			"quantity": "41"
		}, {
			"shipstate": "Ohio",
			"id": "36",
			"ship-date": "1/10/2017",
			"amount": "$32.79",
			"ship-city": "Houston",
			"ship-address": "93 Truax Parkway",
			"product_code": "QA-215",
			"user_name": "ggamlin1v",
			"order_date": "1/17/2017",
			"quantity": "78"
		}, {
			"shipstate": "California",
			"id": "76",
			"ship-date": "7/24/2016",
			"amount": "$17.73",
			"ship-city": "Louisville",
			"ship-address": "34709 Lakewood Gardens Alley",
			"product_code": "WK-621",
			"user_name": "nolennachain1e",
			"order_date": "7/9/2016",
			"quantity": "68"
		}, {
			"shipstate": "Georgia",
			"id": "65",
			"ship-date": "2/14/2017",
			"amount": "$15.66",
			"ship-city": "Falls Church",
			"ship-address": "011 Hovde Park",
			"product_code": "QA-020",
			"user_name": "dlunnl",
			"order_date": "8/9/2016",
			"quantity": "78"
		}, {
			"shipstate": "New York",
			"id": "43",
			"ship-date": "4/13/2017",
			"amount": "$38.81",
			"ship-city": "Reading",
			"ship-address": "00 Kedzie Center",
			"product_code": "MN-917",
			"user_name": "lziehmb",
			"order_date": "10/29/2016",
			"quantity": "89"
		}, {
			"shipstate": "Ohio",
			"id": "60",
			"ship-date": "1/26/2017",
			"amount": "$38.57",
			"ship-city": "Boston",
			"ship-address": "18726 Packers Alley",
			"product_code": "QJ-536",
			"user_name": "pdirkin1f",
			"order_date": "3/23/2017",
			"quantity": "23"
		}, {
			"shipstate": "Missouri",
			"id": "44",
			"ship-date": "10/18/2016",
			"amount": "$46.03",
			"ship-city": "Phoenix",
			"ship-address": "59612 Acker Avenue",
			"product_code": "QX-045",
			"user_name": "ycurnowm",
			"order_date": "7/18/2016",
			"quantity": "36"
		}, {
			"shipstate": "Georgia",
			"id": "100",
			"ship-date": "4/9/2017",
			"amount": "$27.31",
			"ship-city": "Detroit",
			"ship-address": "22528 Pennsylvania Park",
			"product_code": "DQ-512",
			"user_name": "tjahnke1d",
			"order_date": "11/28/2016",
			"quantity": "76"
		}, {
			"shipstate": "Virginia",
			"id": "30",
			"ship-date": "11/26/2016",
			"amount": "$15.17",
			"ship-city": "Little Rock",
			"ship-address": "34855 Pierstorff Point",
			"product_code": "ZU-014",
			"user_name": "bdawdry3",
			"order_date": "10/4/2016",
			"quantity": "36"
		}, {
			"shipstate": "Minnesota",
			"id": "91",
			"ship-date": "12/24/2016",
			"amount": "$31.85",
			"ship-city": "Akron",
			"ship-address": "92 Monterey Trail",
			"product_code": "EG-031",
			"user_name": "mmordy1i",
			"order_date": "11/6/2016",
			"quantity": "9"
		}, {
			"shipstate": "Massachusetts",
			"id": "89",
			"ship-date": "11/11/2016",
			"amount": "$2.68",
			"ship-city": "Washington",
			"ship-address": "57 Evergreen Center",
			"product_code": "JB-756",
			"user_name": "sbansal2e",
			"order_date": "8/21/2016",
			"quantity": "39"
		}, {
			"shipstate": "Michigan",
			"id": "23",
			"ship-date": "12/10/2016",
			"amount": "$36.82",
			"ship-city": "Pittsburgh",
			"ship-address": "1297 Marquette Parkway",
			"product_code": "DL-717",
			"user_name": "pdudney1t",
			"order_date": "2/11/2017",
			"quantity": "17"
		}, {
			"shipstate": "Missouri",
			"id": "61",
			"ship-date": "4/24/2017",
			"amount": "$19.67",
			"ship-city": "Galveston",
			"ship-address": "0 Jenifer Pass",
			"product_code": "SA-411",
			"user_name": "twigelsworth2r",
			"order_date": "7/26/2016",
			"quantity": "0"
		}, {
			"shipstate": "Ohio",
			"id": "62",
			"ship-date": "2/8/2017",
			"amount": "$37.57",
			"ship-city": "Bradenton",
			"ship-address": "717 Cardinal Hill",
			"product_code": "MD-810",
			"user_name": "tcoggin2m",
			"order_date": "12/6/2016",
			"quantity": "60"
		}, {
			"shipstate": "New York",
			"id": "2",
			"ship-date": "1/14/2017",
			"amount": "$33.29",
			"ship-city": "Las Vegas",
			"ship-address": "7 Brickson Park Pass",
			"product_code": "NH-980",
			"user_name": "brosendorf1k",
			"order_date": "3/18/2017",
			"quantity": "76"
		}, {
			"shipstate": "California",
			"id": "17",
			"ship-date": "3/29/2017",
			"amount": "$49.54",
			"ship-city": "Sioux Falls",
			"ship-address": "2541 Clove Crossing",
			"product_code": "MZ-164",
			"user_name": "kwhittleseyi",
			"order_date": "10/25/2016",
			"quantity": "74"
		}, {
			"shipstate": "California",
			"id": "88",
			"ship-date": "2/19/2017",
			"amount": "$22.43",
			"ship-city": "Van Nuys",
			"ship-address": "15 Fallview Junction",
			"product_code": "OW-258",
			"user_name": "jverryg",
			"order_date": "1/20/2017",
			"quantity": "90"
		}, {
			"shipstate": "Texas",
			"id": "96",
			"ship-date": "3/14/2017",
			"amount": "$8.70",
			"ship-city": "Mesa",
			"ship-address": "88 Vera Avenue",
			"product_code": "XD-437",
			"user_name": "imathiassenu",
			"order_date": "11/12/2016",
			"quantity": "19"
		}, {
			"shipstate": "Florida",
			"id": "98",
			"ship-date": "1/10/2017",
			"amount": "$28.32",
			"ship-city": "Springfield",
			"ship-address": "50735 Dayton Lane",
			"product_code": "UV-945",
			"user_name": "mblampied5",
			"order_date": "6/1/2016",
			"quantity": "82"
		}, {
			"shipstate": "California",
			"id": "58",
			"ship-date": "1/21/2017",
			"amount": "$31.94",
			"ship-city": "Abilene",
			"ship-address": "8 Hoffman Drive",
			"product_code": "YW-411",
			"user_name": "bfilippazzo2j",
			"order_date": "2/8/2017",
			"quantity": "52"
		}, {
			"shipstate": "Mississippi",
			"id": "21",
			"ship-date": "9/12/2016",
			"amount": "$25.25",
			"ship-city": "Carlsbad",
			"ship-address": "381 Johnson Trail",
			"product_code": "EX-051",
			"user_name": "alarrington1",
			"order_date": "12/21/2016",
			"quantity": "2"
		}, {
			"shipstate": "California",
			"id": "32",
			"ship-date": "10/25/2016",
			"amount": "$30.67",
			"ship-city": "Raleigh",
			"ship-address": "03 Continental Point",
			"product_code": "DR-751",
			"user_name": "egerwoodp",
			"order_date": "8/19/2016",
			"quantity": "68"
		}, {
			"shipstate": "California",
			"id": "14",
			"ship-date": "12/23/2016",
			"amount": "$43.53",
			"ship-city": "Lincoln",
			"ship-address": "07 Fair Oaks Road",
			"product_code": "OT-516",
			"user_name": "mchatfield29",
			"order_date": "1/19/2017",
			"quantity": "75"
		}, {
			"shipstate": "Texas",
			"id": "53",
			"ship-date": "7/28/2016",
			"amount": "$25.29",
			"ship-city": "Tampa",
			"ship-address": "781 Ridgeway Road",
			"product_code": "JD-425",
			"user_name": "ddrinkhill20",
			"order_date": "10/16/2016",
			"quantity": "67"
		}, {
			"shipstate": "Utah",
			"id": "56",
			"ship-date": "5/4/2017",
			"amount": "$15.07",
			"ship-city": "Portland",
			"ship-address": "61 Upham Hill",
			"product_code": "IY-191",
			"user_name": "rdalstona",
			"order_date": "5/29/2016",
			"quantity": "65"
		}, {
			"shipstate": "Indiana",
			"id": "55",
			"ship-date": "2/1/2017",
			"amount": "$24.69",
			"ship-city": "Indianapolis",
			"ship-address": "07456 South Street",
			"product_code": "JB-936",
			"user_name": "mmccurt2a",
			"order_date": "6/21/2016",
			"quantity": "57"
		}, {
			"shipstate": "Florida",
			"id": "97",
			"ship-date": "11/21/2016",
			"amount": "$10.20",
			"ship-city": "Sacramento",
			"ship-address": "07 Russell Terrace",
			"product_code": "ZS-197",
			"user_name": "eauchinleck4",
			"order_date": "8/6/2016",
			"quantity": "27"
		}, {
			"shipstate": "Florida",
			"id": "64",
			"ship-date": "12/31/2016",
			"amount": "$31.91",
			"ship-city": "Peoria",
			"ship-address": "4 2nd Avenue",
			"product_code": "TG-210",
			"user_name": "ezuanazzi1y",
			"order_date": "8/28/2016",
			"quantity": "21"
		}, {
			"shipstate": "Georgia",
			"id": "54",
			"ship-date": "3/25/2017",
			"amount": "$18.05",
			"ship-city": "Cincinnati",
			"ship-address": "978 Maryland Lane",
			"product_code": "NL-095",
			"user_name": "pdermott6",
			"order_date": "8/28/2016",
			"quantity": "57"
		}, {
			"shipstate": "Arizona",
			"id": "78",
			"ship-date": "4/20/2017",
			"amount": "$20.28",
			"ship-city": "Buffalo",
			"ship-address": "4316 Lake View Trail",
			"product_code": "QF-966",
			"user_name": "ramer1b",
			"order_date": "8/25/2016",
			"quantity": "93"
		}, {
			"shipstate": "Oregon",
			"id": "27",
			"ship-date": "1/2/2017",
			"amount": "$22.05",
			"ship-city": "Atlanta",
			"ship-address": "93502 Roth Drive",
			"product_code": "OB-988",
			"user_name": "knevinson9",
			"order_date": "7/5/2016",
			"quantity": "65"
		}, {
			"shipstate": "New York",
			"id": "35",
			"ship-date": "1/21/2017",
			"amount": "$42.48",
			"ship-city": "Durham",
			"ship-address": "5 Gerald Park",
			"product_code": "KL-767",
			"user_name": "bburden2o",
			"order_date": "1/12/2017",
			"quantity": "16"
		}, {
			"shipstate": "Pennsylvania",
			"id": "12",
			"ship-date": "12/12/2016",
			"amount": "$49.83",
			"ship-city": "Santa Fe",
			"ship-address": "65 Sloan Hill",
			"product_code": "HX-781",
			"user_name": "lnickersony",
			"order_date": "12/27/2016",
			"quantity": "31"
		}, {
			"shipstate": "Texas",
			"id": "26",
			"ship-date": "3/15/2017",
			"amount": "$14.33",
			"ship-city": "Austin",
			"ship-address": "0 Paget Plaza",
			"product_code": "IC-846",
			"user_name": "achatainierk",
			"order_date": "8/8/2016",
			"quantity": "94"
		}, {
			"shipstate": "Kentucky",
			"id": "13",
			"ship-date": "1/25/2017",
			"amount": "$34.95",
			"ship-city": "Dayton",
			"ship-address": "19 Park Meadow Terrace",
			"product_code": "EJ-263",
			"user_name": "lseabourne2d",
			"order_date": "10/29/2016",
			"quantity": "29"
		}, {
			"shipstate": "Alaska",
			"id": "52",
			"ship-date": "11/3/2016",
			"amount": "$42.65",
			"ship-city": "Raleigh",
			"ship-address": "848 Hanson Trail",
			"product_code": "UM-885",
			"user_name": "kgoudieh",
			"order_date": "9/30/2016",
			"quantity": "32"
		}, {
			"shipstate": "California",
			"id": "49",
			"ship-date": "12/28/2016",
			"amount": "$12.78",
			"ship-city": "El Paso",
			"ship-address": "7785 Summit Point",
			"product_code": "EN-888",
			"user_name": "glelandz",
			"order_date": "9/6/2016",
			"quantity": "80"
		}, {
			"shipstate": "California",
			"id": "71",
			"ship-date": "7/29/2016",
			"amount": "$9.95",
			"ship-city": "San Francisco",
			"ship-address": "605 Hagan Point",
			"product_code": "JS-164",
			"user_name": "damortsx",
			"order_date": "4/5/2017",
			"quantity": "69"
		}, {
			"shipstate": "Ohio",
			"id": "74",
			"ship-date": "6/16/2016",
			"amount": "$19.00",
			"ship-city": "Minneapolis",
			"ship-address": "0 7th Junction",
			"product_code": "QO-297",
			"user_name": "mmulmuray1m",
			"order_date": "11/1/2016",
			"quantity": "80"
		}, {
			"shipstate": "North Carolina",
			"id": "95",
			"ship-date": "9/11/2016",
			"amount": "$9.12",
			"ship-city": "Stockton",
			"ship-address": "6031 Knutson Avenue",
			"product_code": "TG-711",
			"user_name": "eelcome2l",
			"order_date": "4/1/2017",
			"quantity": "32"
		}, {
			"shipstate": "Missouri",
			"id": "41",
			"ship-date": "6/1/2016",
			"amount": "$26.87",
			"ship-city": "El Paso",
			"ship-address": "035 Melrose Center",
			"product_code": "UT-776",
			"user_name": "rblatherwickc",
			"order_date": "5/7/2017",
			"quantity": "53"
		}, {
			"shipstate": "Arizona",
			"id": "5",
			"ship-date": "11/26/2016",
			"amount": "$42.35",
			"ship-city": "Dallas",
			"ship-address": "91 Shasta Court",
			"product_code": "HA-785",
			"user_name": "autterson2b",
			"order_date": "8/13/2016",
			"quantity": "16"
		}, {
			"shipstate": "Iowa",
			"id": "20",
			"ship-date": "7/11/2016",
			"amount": "$18.24",
			"ship-city": "Harrisburg",
			"ship-address": "94 Hollow Ridge Pass",
			"product_code": "CK-205",
			"user_name": "ggreenman25",
			"order_date": "6/23/2016",
			"quantity": "26"
		}, {
			"shipstate": "Arizona",
			"id": "99",
			"ship-date": "6/23/2016",
			"amount": "$12.98",
			"ship-city": "New Orleans",
			"ship-address": "72 Nancy Terrace",
			"product_code": "UP-953",
			"user_name": "bfurminger2h",
			"order_date": "7/13/2016",
			"quantity": "41"
		}, {
			"shipstate": "Arizona",
			"id": "84",
			"ship-date": "4/19/2017",
			"amount": "$41.54",
			"ship-city": "New Orleans",
			"ship-address": "8184 Moland Pass",
			"product_code": "GY-936",
			"user_name": "rgrafton28",
			"order_date": "2/16/2017",
			"quantity": "45"
		}, {
			"shipstate": "California",
			"id": "86",
			"ship-date": "3/13/2017",
			"amount": "$14.55",
			"ship-city": "San Antonio",
			"ship-address": "7200 Birchwood Road",
			"product_code": "OJ-999",
			"user_name": "mricht1g",
			"order_date": "6/29/2016",
			"quantity": "43"
		}, {
			"shipstate": "District of Columbia",
			"id": "42",
			"ship-date": "3/6/2017",
			"amount": "$8.59",
			"ship-city": "Albany",
			"ship-address": "52 Del Mar Hill",
			"product_code": "YB-195",
			"user_name": "apridhams",
			"order_date": "12/9/2016",
			"quantity": "8"
		}, {
			"shipstate": "Nevada",
			"id": "66",
			"ship-date": "12/1/2016",
			"amount": "$35.10",
			"ship-city": "Atlanta",
			"ship-address": "60505 Golden Leaf Pass",
			"product_code": "AP-280",
			"user_name": "rglantz1o",
			"order_date": "4/22/2017",
			"quantity": "16"
		}, {
			"shipstate": "Pennsylvania",
			"id": "94",
			"ship-date": "4/20/2017",
			"amount": "$15.22",
			"ship-city": "Wilmington",
			"ship-address": "0 Havey Lane",
			"product_code": "GO-897",
			"user_name": "gwozencroft22",
			"order_date": "3/3/2017",
			"quantity": "50"
		}, {
			"shipstate": "Illinois",
			"id": "11",
			"ship-date": "5/1/2017",
			"amount": "$36.33",
			"ship-city": "El Paso",
			"ship-address": "376 Logan Place",
			"product_code": "FO-338",
			"user_name": "crosso0",
			"order_date": "7/19/2016",
			"quantity": "81"
		}, {
			"shipstate": "Florida",
			"id": "15",
			"ship-date": "10/3/2016",
			"amount": "$31.11",
			"ship-city": "Hartford",
			"ship-address": "9611 Lakeland Lane",
			"product_code": "NX-034",
			"user_name": "mbolter1s",
			"order_date": "3/28/2017",
			"quantity": "85"
		}, {
			"shipstate": "Texas",
			"id": "73",
			"ship-date": "1/8/2017",
			"amount": "$37.97",
			"ship-city": "Houston",
			"ship-address": "72821 Hanover Drive",
			"product_code": "RF-226",
			"user_name": "afarrar1a",
			"order_date": "3/23/2017",
			"quantity": "39"
		}, {
			"shipstate": "District of Columbia",
			"id": "77",
			"ship-date": "6/22/2016",
			"amount": "$28.58",
			"ship-city": "Cincinnati",
			"ship-address": "7912 Melrose Park",
			"product_code": "CX-832",
			"user_name": "dkift1q",
			"order_date": "12/19/2016",
			"quantity": "44"
		}, {
			"shipstate": "Louisiana",
			"id": "16",
			"ship-date": "11/21/2016",
			"amount": "$16.53",
			"ship-city": "Washington",
			"ship-address": "96066 Meadow Vale Place",
			"product_code": "EC-210",
			"user_name": "mmcgahy18",
			"order_date": "6/10/2016",
			"quantity": "87"
		}, {
			"shipstate": "Delaware",
			"id": "92",
			"ship-date": "5/18/2016",
			"amount": "$27.92",
			"ship-city": "Phoenix",
			"ship-address": "94 3rd Lane",
			"product_code": "OK-283",
			"user_name": "ssommerling21",
			"order_date": "4/21/2017",
			"quantity": "66"
		}, {
			"shipstate": "New Mexico",
			"id": "24",
			"ship-date": "2/12/2017",
			"amount": "$2.74",
			"ship-city": "Louisville",
			"ship-address": "238 Continental Alley",
			"product_code": "LJ-508",
			"user_name": "rmethven7",
			"order_date": "1/23/2017",
			"quantity": "42"
		}, {
			"shipstate": "Florida",
			"id": "67",
			"ship-date": "5/8/2016",
			"amount": "$47.55",
			"ship-city": "Denver",
			"ship-address": "7 Cody Center",
			"product_code": "GA-829",
			"user_name": "covens24",
			"order_date": "7/17/2016",
			"quantity": "71"
		}, {
			"shipstate": "Indiana",
			"id": "6",
			"ship-date": "6/29/2016",
			"amount": "$38.37",
			"ship-city": "Miami",
			"ship-address": "697 Stang Center",
			"product_code": "KI-495",
			"user_name": "ekift26",
			"order_date": "2/23/2017",
			"quantity": "96"
		}, {
			"shipstate": "Colorado",
			"id": "81",
			"ship-date": "9/28/2016",
			"amount": "$45.40",
			"ship-city": "Brooklyn",
			"ship-address": "962 Walton Drive",
			"product_code": "ZL-219",
			"user_name": "wstrettell10",
			"order_date": "5/17/2016",
			"quantity": "36"
		}, {
			"shipstate": "Connecticut",
			"id": "4",
			"ship-date": "5/19/2016",
			"amount": "$6.71",
			"ship-city": "Fresno",
			"ship-address": "1572 Redwing Lane",
			"product_code": "NC-285",
			"user_name": "hdubberd",
			"order_date": "11/2/2016",
			"quantity": "51"
		}, {
			"shipstate": "Ohio",
			"id": "63",
			"ship-date": "12/31/2016",
			"amount": "$30.32",
			"ship-city": "Juneau",
			"ship-address": "2 American Park",
			"product_code": "ZE-134",
			"user_name": "gcape8",
			"order_date": "12/5/2016",
			"quantity": "5"
		}, {
			"shipstate": "California",
			"id": "68",
			"ship-date": "3/4/2017",
			"amount": "$41.01",
			"ship-city": "Ocala",
			"ship-address": "8 Macpherson Alley",
			"product_code": "ZD-904",
			"user_name": "lfindon1w",
			"order_date": "1/22/2017",
			"quantity": "81"
		}, {
			"shipstate": "Florida",
			"id": "19",
			"ship-date": "8/8/2016",
			"amount": "$43.04",
			"ship-city": "Peoria",
			"ship-address": "708 Caliangt Crossing",
			"product_code": "YX-943",
			"user_name": "rdanneil2f",
			"order_date": "9/5/2016",
			"quantity": "29"
		}, {
			"shipstate": "Texas",
			"id": "22",
			"ship-date": "10/4/2016",
			"amount": "$30.00",
			"ship-city": "Miami",
			"ship-address": "7 Barnett Hill",
			"product_code": "AU-198",
			"user_name": "biggalden23",
			"order_date": "3/6/2017",
			"quantity": "75"
		}, {
			"shipstate": "Washington",
			"id": "90",
			"ship-date": "5/26/2016",
			"amount": "$26.66",
			"ship-city": "Pompano Beach",
			"ship-address": "69 Mitchell Parkway",
			"product_code": "FD-858",
			"user_name": "kgergus1z",
			"order_date": "11/17/2016",
			"quantity": "13"
		}, {
			"shipstate": "Florida",
			"id": "48",
			"ship-date": "9/23/2016",
			"amount": "$34.66",
			"ship-city": "Garden Grove",
			"ship-address": "2 Scott Court",
			"product_code": "IY-025",
			"user_name": "gjosephoff14",
			"order_date": "8/2/2016",
			"quantity": "90"
		}, {
			"shipstate": "Hawaii",
			"id": "8",
			"ship-date": "7/2/2016",
			"amount": "$0.26",
			"ship-city": "Honolulu",
			"ship-address": "50 Bashford Road",
			"product_code": "ML-636",
			"user_name": "htwidle2p",
			"order_date": "7/10/2016",
			"quantity": "73"
		}, {
			"shipstate": "Pennsylvania",
			"id": "72",
			"ship-date": "10/16/2016",
			"amount": "$24.25",
			"ship-city": "Miami",
			"ship-address": "10 Forest Run Place",
			"product_code": "KU-962",
			"user_name": "tdebling2",
			"order_date": "10/6/2016",
			"quantity": "63"
		}, {
			"shipstate": "Texas",
			"id": "31",
			"ship-date": "1/21/2017",
			"amount": "$12.72",
			"ship-city": "Canton",
			"ship-address": "72 Prentice Plaza",
			"product_code": "FE-539",
			"user_name": "amuddle1j",
			"order_date": "12/30/2016",
			"quantity": "44"
		}, {
			"shipstate": "Colorado",
			"id": "80",
			"ship-date": "2/24/2017",
			"amount": "$32.52",
			"ship-city": "Jackson",
			"ship-address": "801 Melody Drive",
			"product_code": "AI-062",
			"user_name": "csarle13",
			"order_date": "12/16/2016",
			"quantity": "87"
		}, {
			"shipstate": "Nebraska",
			"id": "79",
			"ship-date": "10/7/2016",
			"amount": "$21.02",
			"ship-city": "Everett",
			"ship-address": "050 Delladonna Crossing",
			"product_code": "XC-608",
			"user_name": "wmctrustief",
			"order_date": "12/31/2016",
			"quantity": "74"
		}, {
			"shipstate": "Texas",
			"id": "57",
			"ship-date": "6/22/2016",
			"amount": "$17.40",
			"ship-city": "Southfield",
			"ship-address": "25 Elgar Terrace",
			"product_code": "XF-035",
			"user_name": "bhenryso",
			"order_date": "4/27/2017",
			"quantity": "66"
		}, {
			"shipstate": "New York",
			"id": "9",
			"ship-date": "12/18/2016",
			"amount": "$45.56",
			"ship-city": "Kent",
			"ship-address": "808 Southridge Road",
			"product_code": "RM-169",
			"user_name": "snormanvillq",
			"order_date": "8/8/2016",
			"quantity": "23"
		}, {
			"shipstate": "Arkansas",
			"id": "40",
			"ship-date": "1/28/2017",
			"amount": "$37.53",
			"ship-city": "Saint Louis",
			"ship-address": "98871 Blackbird Street",
			"product_code": "RN-375",
			"user_name": "khewins2q",
			"order_date": "4/16/2017",
			"quantity": "96"
		}, {
			"shipstate": "New Jersey",
			"id": "25",
			"ship-date": "11/6/2016",
			"amount": "$31.56",
			"ship-city": "Dallas",
			"ship-address": "6 Toban Parkway",
			"product_code": "HB-403",
			"user_name": "agennings1r",
			"order_date": "12/5/2016",
			"quantity": "71"
		}, {
			"shipstate": "Wisconsin",
			"id": "51",
			"ship-date": "2/28/2017",
			"amount": "$7.88",
			"ship-city": "Sacramento",
			"ship-address": "3678 Acker Trail",
			"product_code": "BL-627",
			"user_name": "rgilbride1l",
			"order_date": "5/3/2017",
			"quantity": "60"
		}, {
			"shipstate": "North Carolina",
			"id": "7",
			"ship-date": "10/21/2016",
			"amount": "$37.47",
			"ship-city": "Richmond",
			"ship-address": "2491 Straubel Terrace",
			"product_code": "CU-290",
			"user_name": "ahargerie19",
			"order_date": "9/15/2016",
			"quantity": "64"
		}, {
			"shipstate": "Washington",
			"id": "10",
			"ship-date": "12/3/2016",
			"amount": "$19.66",
			"ship-city": "New York City",
			"ship-address": "7140 Gina Center",
			"product_code": "QV-690",
			"user_name": "jwheeldonw",
			"order_date": "5/24/2016",
			"quantity": "12"
		}, {
			"shipstate": "Texas",
			"id": "75",
			"ship-date": "3/7/2017",
			"amount": "$37.09",
			"ship-city": "Dulles",
			"ship-address": "17844 Hoard Court",
			"product_code": "NJ-656",
			"user_name": "hmacskeagan1x",
			"order_date": "1/20/2017",
			"quantity": "49"
		}, {
			"shipstate": "Virginia",
			"id": "28",
			"ship-date": "4/17/2017",
			"amount": "$33.59",
			"ship-city": "Washington",
			"ship-address": "55120 Meadow Valley Avenue",
			"product_code": "CZ-007",
			"user_name": "lfransewichj",
			"order_date": "5/8/2016",
			"quantity": "45"
		}, {
			"shipstate": "Virginia",
			"id": "46",
			"ship-date": "9/25/2016",
			"amount": "$18.57",
			"ship-city": "Hollywood",
			"ship-address": "865 Swallow Way",
			"product_code": "OC-122",
			"user_name": "mkorous2c",
			"order_date": "11/12/2016",
			"quantity": "36"
		}, {
			"shipstate": "Arizona",
			"id": "39",
			"ship-date": "2/7/2017",
			"amount": "$7.78",
			"ship-city": "Pensacola",
			"ship-address": "4 Cody Alley",
			"product_code": "UD-890",
			"user_name": "eworham1p",
			"order_date": "8/29/2016",
			"quantity": "96"
		}, {
			"shipstate": "New York",
			"id": "34",
			"ship-date": "6/14/2016",
			"amount": "$15.64",
			"ship-city": "Spring",
			"ship-address": "83 Oakridge Road",
			"product_code": "XR-769",
			"user_name": "vewbach15",
			"order_date": "12/6/2016",
			"quantity": "14"
		}, {
			"shipstate": "Michigan",
			"id": "33",
			"ship-date": "3/1/2017",
			"amount": "$9.87",
			"ship-city": "Chicago",
			"ship-address": "7852 Heath Drive",
			"product_code": "ON-708",
			"user_name": "lbrodley1h",
			"order_date": "10/15/2016",
			"quantity": "39"
		}, {
			"shipstate": "Illinois",
			"id": "47",
			"ship-date": "6/6/2016",
			"amount": "$39.48",
			"ship-city": "Milwaukee",
			"ship-address": "360 Kim Pass",
			"product_code": "XT-204",
			"user_name": "kdocharty12",
			"order_date": "7/31/2016",
			"quantity": "39"
		}, {
			"shipstate": "Texas",
			"id": "59",
			"ship-date": "6/10/2016",
			"amount": "$9.06",
			"ship-city": "Glendale",
			"ship-address": "957 Blackbird Court",
			"product_code": "IA-002",
			"user_name": "mtebb2k",
			"order_date": "6/28/2016",
			"quantity": "28"
		}, {
			"shipstate": "District of Columbia",
			"id": "45",
			"ship-date": "5/5/2017",
			"amount": "$27.76",
			"ship-city": "Riverside",
			"ship-address": "782 Village Green Plaza",
			"product_code": "VP-559",
			"user_name": "polenin1c",
			"order_date": "2/16/2017",
			"quantity": "84"
		}, {
			"shipstate": "Minnesota",
			"id": "29",
			"ship-date": "9/1/2016",
			"amount": "$18.59",
			"ship-city": "Atlanta",
			"ship-address": "8339 Old Gate Terrace",
			"product_code": "PF-787",
			"user_name": "wwarbeysr",
			"order_date": "10/15/2016",
			"quantity": "88"
		}, {
			"shipstate": "California",
			"id": "85",
			"ship-date": "7/18/2016",
			"amount": "$32.91",
			"ship-city": "Irvine",
			"ship-address": "5 American Hill",
			"product_code": "MI-627",
			"user_name": "nchurly1u",
			"order_date": "1/28/2017",
			"quantity": "63"
		}, {
			"shipstate": "Texas",
			"id": "87",
			"ship-date": "3/25/2017",
			"amount": "$44.37",
			"ship-city": "Minneapolis",
			"ship-address": "5 Boyd Parkway",
			"product_code": "PJ-972",
			"user_name": "lstanbrookee",
			"order_date": "12/5/2016",
			"quantity": "98"
		}, {
			"shipstate": "Texas",
			"id": "93",
			"ship-date": "7/22/2016",
			"amount": "$18.12",
			"ship-city": "Saint Paul",
			"ship-address": "1 Erie Hill",
			"product_code": "PG-583",
			"user_name": "gdenacampn",
			"order_date": "5/24/2016",
			"quantity": "2"
		}, {
			"shipstate": "South Dakota",
			"id": "69",
			"ship-date": "2/16/2017",
			"amount": "$30.57",
			"ship-city": "Des Moines",
			"ship-address": "06 Corry Junction",
			"product_code": "HK-502",
			"user_name": "bnicely1n",
			"order_date": "1/27/2017",
			"quantity": "83"
		}, {
			"shipstate": "Florida",
			"id": "3",
			"ship-date": "6/8/2016",
			"amount": "$14.75",
			"ship-city": "Austin",
			"ship-address": "034 Waubesa Court",
			"product_code": "RX-037",
			"user_name": "bpatis17",
			"order_date": "7/29/2016",
			"quantity": "26"
		}, {
			"shipstate": "Kentucky",
			"id": "82",
			"ship-date": "1/16/2017",
			"amount": "$5.96",
			"ship-city": "Trenton",
			"ship-address": "22 Sunbrook Trail",
			"product_code": "EJ-968",
			"user_name": "rlaverockv",
			"order_date": "4/16/2017",
			"quantity": "64"
		}, {
			"shipstate": "Minnesota",
			"id": "37",
			"ship-date": "6/27/2016",
			"amount": "$42.94",
			"ship-city": "Brooklyn",
			"ship-address": "95 Barby Circle",
			"product_code": "IW-376",
			"user_name": "lsealeaf16",
			"order_date": "1/6/2017",
			"quantity": "60"
		}, {
			"shipstate": "North Carolina",
			"id": "50",
			"ship-date": "2/11/2017",
			"amount": "$46.84",
			"ship-city": "Salt Lake City",
			"ship-address": "4880 Fair Oaks Park",
			"product_code": "OS-912",
			"user_name": "acleal2n",
			"order_date": "4/13/2017",
			"quantity": "58"
		}, {
			"shipstate": "Louisiana",
			"id": "38",
			"ship-date": "7/10/2016",
			"amount": "$1.66",
			"ship-city": "Anaheim",
			"ship-address": "0 Nancy Avenue",
			"product_code": "EW-141",
			"user_name": "lstroban2i",
			"order_date": "7/31/2016",
			"quantity": "10"
		}, {
			"shipstate": "District of Columbia",
			"id": "1",
			"ship-date": "1/31/2017",
			"amount": "$2.68",
			"ship-city": "Anderson",
			"ship-address": "6 Eliot Park",
			"product_code": "RI-048",
			"user_name": "gmanhoodt",
			"order_date": "1/30/2017",
			"quantity": "89"
		}, {
			"shipstate": "Texas",
			"id": "18",
			"ship-date": "2/18/2017",
			"amount": "$36.24",
			"ship-city": "Englewood",
			"ship-address": "7 Havey Circle",
			"product_code": "ZC-757",
			"user_name": "gblodgett2g",
			"order_date": "4/26/2017",
			"quantity": "15"
		}]
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