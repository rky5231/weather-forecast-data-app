# Weather Forecast App

This is a simple web application built with Streamlit that provides a weather forecast for the next few days using data from the OpenWeatherMap API.

## Features

- Allows users to input a location and select the number of forecast days.
- Provides temperature and sky condition forecast for the selected location and time frame.
- Displays the temperature forecast as a line chart and the sky condition forecast using corresponding icons.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have Python installed.
- You have obtained an API key from [OpenWeatherMap](https://openweathermap.org/) and replaced `"hidden"` in `backend.py` with your actual API key.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python packages by running:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the application by executing `main.py`:
    ```bash
    streamlit run main.py
    ```

## Usage

- Input the desired location in the text field provided.
- Use the slider to select the number of forecast days.
- Choose between viewing temperature or sky condition forecast using the select box.
- The application will display the forecasted data accordingly.

## Preview

![Weather Forecast App Preview](preview.png)

## Credits

- This application was built using [Streamlit](https://streamlit.io/) for the user interface and [Plotly](https://plotly.com/python/) for data visualization.
- Weather data is fetched from the [OpenWeatherMap API](https://openweathermap.org/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
