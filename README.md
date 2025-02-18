# GenderComics Database

This repository contains JSON files exported from the MongoDB collections of the GenderComics database. The data encapsulated within these files represents various aspects of the GenderComics project. 

## Repository Structure

The repository is organized as follows:

- `gendercomics/`: This directory contains all the JSON files exported from the MongoDB collections. Each JSON file corresponds to a specific collection from the GenderComics database.

## Usage

To use the data in this repository:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/gendercomics/database.git
    cd database
    ```

2. **Import JSON files into MongoDB**:
    You can import the JSON files into your MongoDB instance using the `mongoimport` tool. For example:
    ```bash
    mongoimport --db gendercomics --collection <collection-name> --file json/<file-name>.json --jsonArray
    ```
    Replace `<collection-name>` with the name of the collection you want to import and `<file-name>` with the respective JSON file name.

## Contributing

We welcome contributions to improve the data quality and structure. If you have any suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the CC BY-ND License - see the [LICENSE](https://creativecommons.org/licenses/by-nd/4.0/) file for details.

## Contact

For any questions or concerns, please reach out to the maintainers of the project.
