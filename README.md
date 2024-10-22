# Shortest Path Finder for Class Commute

## Description
This project calculates the shortest path from your location to your class based on either **"jarak"** (distance) or **"waktu"** (time). It employs two algorithms: **Dijkstra** and **Bellman-Ford**. The project uses an `.xlsx` file to define the distances between checkpoints or locations and helps users determine the optimal route.

The project is built on the **Streamlit** platform, offering a simple user interface for finding the shortest route and visualizing it.

## Badges
[![Python](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-0.89.0-brightgreen.svg)](https://streamlit.io/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3.0-orange.svg)](https://pandas.pydata.org/)

## Installation
To install and run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/muhammad-hamizan/shortest-route.git
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:
   ```bash
   streamlit run shortest-path.py
   ```

### Requirements
- Python 3.x
- Streamlit
- Pandas (for handling the `.xlsx` file)
- openpyxl (for reading Excel files)

## Usage
To use the application, open the web interface and input the desired start and end locations. Select whether you want the shortest path based on "jarak" (distance) or "waktu" (time). The application will display the shortest route calculated by both Dijkstra and Bellman-Ford algorithms.

Example:
- Start Location: Home
- End Location: Class
- Metric: Jarak (Distance)

The output will show the selected route and metrics for both algorithms.

## Support
For any issues or help, please contact:

- Email: hamizan.r.muhammad@gmail.com
- Issue Tracker: [GitHub Issues](link_to_github_issues)

## Roadmap
Future improvements may include:
- Adding more locations or dynamic input for new checkpoints.
- Visualizing real-time traffic data.
- Implementing a feature to compare the efficiency of the algorithms under different conditions.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

### Running Tests
You can run the tests using:
```bash
pytest
```

## Authors and acknowledgment
- Project Lead: Arief Muhammad Usry, Ghazy Fadhal Ramadhan, Muhammad Rafie Hamizan
- Contributors: Thanks to everyone who contributed!

## Project status
The project is actively maintained, and future updates are planned.
