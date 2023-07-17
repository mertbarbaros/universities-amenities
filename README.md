# Get Universities and Amenities

This script retrieves information about universities and nearby amenities such as restaurants, cafes, and coffee shops in specified cities using the OSMnx library.

## Requirements

- Python 3.x
- OSMnx
- Pandas
- Shapely

## Installation

Install the required packages by running the following command:

pip install osmnx pandas shapely

## Usage
Modify the cities and amenities variables in the script to specify the cities and amenities you are interested in.

cities = ["Istanbul, Turkey", "Ankara, Turkey", "Izmir, Turkey"]
amenities = ["restaurant", "cafe", "coffee_shop"]
df = get_universities_and_amenities(cities, amenities)


The get_universities_and_amenities function retrieves information about universities in the specified cities and finds amenities within a specified distance from each university. The results are stored in a Pandas DataFrame.

Feel free to customize the script according to your requirements.

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to create an issue or submit a pull request.

License
This project is licensed under the MIT License.
