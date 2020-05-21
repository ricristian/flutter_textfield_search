# flutter_textfield_search
![Build and Test](https://github.com/alexrindone/flutter_textfield_search/workflows/Build%20and%20Tests/badge.svg)
<img src="https://img.shields.io/static/v1?label=coverage&message=100%&color=green.svg" />

FTFS is a Flutter package which uses a TextField Widget to search and select a value from a list. It's a simple, lightweight, and fully tested package unlike other "autocomplete" or textfield search packages.

## Usage
To use this package, add flutter_textfield_search as a dependency in your pubsec.yaml file.

## Example
Import the package.

    `import 'package:flutter_textfield_search/search.dart'`;

Then include the widget anywhere you would normally use a TextField widget with a label, and a List
    <br>Example MaterialApp using TextFieldSearch Widget
    <br>

        const label = "Some Label";
        const dummyList = ['Item 1', 'Item 2', 'Item 3', 'Item 4', 'Item 5'];
        MaterialApp(
          home: Scaffold(
            body: TextFieldSearch(initialList: dummyList, label: label)
          ),
        )

## Issues

Please email any issues, bugs, or additional features you would like to see built to arindone@nubeer.io.

## Contributing

If you wish to contribute to this package you may fork the repository and make a pull request to this repository.
