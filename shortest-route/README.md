
# Shortest Path Finder for Class Commute

## Description
This project calculates the shortest path from your location to your class based on either **"jarak"** (distance) or **"waktu"** (time). It employs two algorithms: **Dijkstra** and **Bellman-Ford**. The project uses an `.xlsx` file to define the distances between checkpoints or locations and helps users determine the optimal route.

The project is built on the **Streamlit** platform, offering a simple user interface for finding the shortest route and visualizing it.

## Badges
You can add badges here such as build status, code coverage, or dependencies if using services like Shields.io or Travis CI.

## Visuals
Include visuals of the Streamlit application interface, screenshots of selecting a route, and comparison between Dijkstra and Bellman-Ford paths.

Example screenshot:

![screenshot](link_to_screenshot)

## Installation
To install and run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repo-url>
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

- Email: support@example.com
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
- Project Lead: [Your Name]
- Contributors: Thanks to everyone who contributed!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Project status
The project is actively maintained, and future updates are planned.
