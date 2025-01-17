# Zubdata - Google Maps Scraper

## Version: 2.0.1

## Note: 
**Our all scrapers are working, if you find any issue or bug please open an issue with the detail of issue. We will try to resolve it quickly for you.**

<img src="Readme assets/zubdata google maps scraper.jpg" alt="Zubdata open sourced google maps scraper">

Welcome to the Zubdata GitHub Google Maps Scraper repository, an open-source GUI tool built in Python. This tool allows you to extract data from Google Maps using a user-friendly interface.
Documentation can be found at this [link](https://zubdata.com/tools/google-maps-scraper) 🔗

## Features

- User-friendly graphical interface for easy navigation and interaction. 😊
- Scrapes various data from Google Maps, such as business names, addresses, phone number, website, ratings, and total reviews.
- Fast and efficient 🚀

## Getting Started

To get started with the Google Maps Scraper, follow these steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/Zubdata/Google-Maps-Scraper.git
   ```

2. Install the required dependencies by running the following command:
   ```shell
   pip install -r requirements.txt
   ```
3. Before start using it you can change its optional settings in ```Google map scraper\scraper\settings.py```  There are three options that you can change:

- OUTPUT_PATH: It is the path where your output file will be save. Default it is “.” It will save the file in the root directory.
- DRIVER_EXECUTABLE_PATH: It is the path of chrome driver. Use it only when you already have installed chrome driver. By default it is None, mean scraper will automatically install the driver.

4. Launch the Google Maps Scraper GUI by this command:
```python "Google map scraper\starter.py" start```

`For further helping docs please visit our` [documentation](https://zubdata.com/tools/google-maps-scraper/) `page`

## Contributing

We welcome contributions from the open-source community to enhance the Google Maps Scraper tool. If you would like to contribute, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and commit them with descriptive commit messages.

4. Push your changes to your forked repository.

5. Create a pull request to the `main` branch of the repository.

6. Wait for the code review and address any feedback received.

7. You can also contribute by updating the readme.md.

## License

The Google Maps Scraper tool is open-source software licensed under the [GNU GENERAL PUBLIC LICENSE](https://github.com/Zubdata/Google-Maps-Scraper/blob/main/LICENSE) 📜

## Support

If you encounter any issues or have any questions or suggestions, please feel free to open an issue. We appreciate your feedback and are here to assist you.

Happy scraping with Zubdata's Google Maps Scraper! ✨
