# Weather Data Visualization

This project visualizes weather data from Death Valley and Sitka for the year 2021. The data includes daily high and low temperatures, and the visualizations are created using Python and Matplotlib.

## Project Structure

- `data/`: Contains CSV files with weather data.
- `death_valley_highs_lows.py`: Script to visualize daily high and low temperatures for Death Valley.
- `sitka_highs_lows.py`: Script to visualize daily high and low temperatures for Sitka.
- `sitka_highs.py`: Script to visualize daily high temperatures for Sitka.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## Setup

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install matplotlib
    ```

## Usage

1. To visualize daily high and low temperatures for Death Valley:
    ```sh
    python death_valley_highs_lows.py
    ```

2. To visualize daily high and low temperatures for Sitka:
    ```sh
    python sitka_highs_lows.py
    ```

3. To visualize daily high temperatures for Sitka:
    ```sh
    python sitka_highs.py
    ```

## Data

The data is sourced from the National Centers for Environmental Information (NCEI) and is provided in CSV format. The CSV files contain the following columns:

- : "STATION", "NAME", "DATE", "TMAX", "TMIN", "TOBS"
-  and : "STATION", "NAME", "DATE", "TAVG", "TMAX", "TMIN"
