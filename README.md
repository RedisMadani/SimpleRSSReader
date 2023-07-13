# SimpleRSSReader


## Overview
SimpleRSSReader is a simple application that allows you to stay up-to-date with the latest news from Apple. It demonstrates the usage of various features such as XML Parser Delegate, dynamic height control for tableView cells, and expandable/collapsible tableView cells.

## Features
- Fetches the latest Apple news from an XML feed.
- Parses the XML data using the XML Parser Delegate.
- Displays the news articles in a tableView.
- Dynamically adjusts the height of tableView cells based on content.
- Implements expandable and collapsible functionality for tableView cells.

## Installation
1. Clone the repository:

```bash
git clone https://github.com/RedisMadani/SimpleRSSReader.git
```

2. Open the project in Xcode.

3. Build and run the app on your simulator or device.

## Usage
Upon launching the SimpleRSSReader app, you will be presented with the latest news articles from Apple. Each article is displayed as a tableView cell, showing the headline and a brief summary.

### Dynamic Cell Height
The app dynamically adjusts the height of each tableView cell to accommodate the varying length of article summaries. This ensures that the content is properly displayed without being cut off or leaving excessive empty space.

### Expand and Collapse
To allow for a better reading experience, the tableView cells can be expanded and collapsed. Tapping on a cell expands it, revealing the full article content. Tapping again collapses the cell, returning it to its original state.

## Dependencies
The SimpleRSSReader app relies on the following dependencies:

- [Alamofire](https://github.com/Alamofire/Alamofire): Used for networking tasks, such as fetching the XML feed.
- [SWXMLHash](https://github.com/drmohundro/SWXMLHash): A lightweight XML parsing library used to decode the XML data.

You can find the installation instructions for these dependencies in their respective GitHub repositories.

## Contributing
Contributions are welcome! If you'd like to contribute to the SimpleRSSReader app, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Open a pull request in this repository, describing the changes you've made.

## License
The SimpleRSSReader app is open source and available under the [MIT License](LICENSE). Feel free to modify and distribute it according to your needs.
