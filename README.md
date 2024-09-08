<div style="display: flex; align-items: center;">
    <img src="static/logo.png" width="120" height="120">
    <h1>Spotify Web API Tutorial</h1>
</div>

Welcome to the Tutorial on leveraging Spotify's Web API to explore music data and create innovative applications. This tutorial provides a comprehensive guide to interacting with Spotify's API, analyzing data, and visualizing results.

## Project Structure

The project structure is as follows:

```bash
Tutorial_Spotify_API
├── README.md
├── Spotify_API.ipynb
├── artists
│   ├── american.txt
│   ├── bulgarian.txt
│   ├── chinese.txt
│   ├── corean.txt
│   ├── french.txt
│   ├── german.txt
│   ├── italian.txt
│   ├── japanese.txt
│   ├── romanian.txt
│   └── spanish.txt
├── discography_data.csv
├── environment.yml
├── international_artists_data.csv
├── most_streamed.csv
├── requirements.txt
├── static
│   ├── Screen
│   │   ├── Screen_1.png
│   │   ├── Screen_2.png
│   │   ├── Screen_3.png
│   │   ├── Screen_4.png
│   │   ├── Screen_5.png
│   │   └── Screen_6.png
│   ├── emoji.png
│   └── logo.png
└── top_tracks_data.csv
```

- **README.md**: This file.
- **Spotify_API.ipynb**: Jupyter notebook containing the tutorial and code examples.
- **artists/**: Directory with text files listing artist names by nationality.
  - `american.txt`
  - `bulgarian.txt`
  - `chinese.txt`
  - `corean.txt`
  - `french.txt`
  - `german.txt`
  - `italian.txt`
  - `japanese.txt`
  - `romanian.txt`
  - `spanish.txt`
- **discography_data.csv**: CSV file containing track data for analysis.
- **environment.yml**: Conda environment configuration file for setting up the development environment.
- **international_artists_data.csv**: CSV file containing combined data of international artists.
- **most_streamed.csv**: CSV file with data on the most streamed tracks.
- **requirements.txt**: Python package requirements.
- **static/**: Directory with static assets like images.
  - **Screen/**: Screenshots of the application.
    - `Screen_1.png`
    - `Screen_2.png`
    - `Screen_3.png`
    - `Screen_4.png`
    - `Screen_5.png`
    - `Screen_6.png`
  - `emoji.png`: Image file.
  - `logo.png`: Logo image file.
- **top_tracks_data.csv**: CSV file containing data on top tracks.

## Getting Started

To get started with this tutorial, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone git@github.com:nameisalfio/Tutorial_Spotify_API.git
   cd Tutorial_Spotify_API
    ```

2. **Set Up the Virtual Environment Create and activate the Conda environment**:
   ```bash
   conda env create -f environment.yml
   conda activate smda
   ```

3. **Install Dependencies Ensure all required Python packages are installed**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Explore the Jupyter Notebook Open the Jupyter notebook to follow the tutorial and run the code**:

    ```bash
    jupyter notebook Spotify_API.ipynb
    ```

## Key Sections of the Tutorial

1. Preamble: Provides an introduction to the tutorial, including an overview of the objectives and what you will learn. It sets the stage for understanding how to leverage the Spotify Web API.

2. Introduction: Gives a general overview of Spotify's Web API, including its capabilities and potential uses. This section explains what the API can do and how it can be used to interact with Spotify's streaming service.

3. Profile and Application: Covers the steps to set up your Spotify developer profile and create an application. This is necessary to obtain the credentials needed to access the Spotify API.

4. API Access: Details how to authenticate with Spotify's API and obtain the required access tokens. It explains the OAuth authentication flow and how to use it to make API requests.

5. Using RESTful APIs: Explains how to use Spotify's RESTful APIs to perform various actions and retrieve data. This section includes guidance on making API requests and handling responses.

6. Spotify Python API: Provides instructions on how to integrate Spotify's Python API into your development process. It shows how to use the Python API to simplify interactions with the Spotify Web API.

7. Data Extraction and Analysis: Describes the process of extracting data from Spotify and analyzing it. This includes methods for processing the data and visualizing it through charts and graphs.

8. Conclusion: This tutorial highlights the powerful capabilities of Spotify's Web API and demonstrates how to extract, analyze, and visualize music data. By following the steps outlined, you can gain valuable insights and build engaging music applications.
We hope this guide inspires you to explore the full potential of Spotify's API and enhance your music-related projects.
Feel free to contribute to this repository or reach out with any questions. Happy coding!

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## Acknowledgments

This tutorial was created by Alfio Spoto and is part of the Spotify Music Data Analysis (SMDA) project. The project aims to explore music data, analyze trends, and create innovative applications using Spotify's Web API.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The repository for the project is available at: <a href='git@github.com:nameisalfio/Tutorial_Spotify_API.git'>GitHub Repository</a>

