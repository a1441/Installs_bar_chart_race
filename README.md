# Bar Racing Visualization

## Overview
This repository contains code and data for creating a captivating "Bar Racing" visualization of cumulative installs per network over time. This visualization technique dynamically displays the changing popularity of different networks, providing valuable insights into their growth patterns.

![image](https://github.com/a1441/Installs_bar_chart_race/assets/49153959/10e21434-d374-4f03-bcac-647ab458bdb3)


## How to Use
Follow these steps to use the code and generate your own Bar Racing visualization:

### Prerequisites
Before getting started, ensure you have the following prerequisites installed:
- Python 3.x
- Jupyter Notebook
- Required Python packages (pandas, matplotlib, bar_chart_race)

# Bar Racing Visualization

## Overview

This repository contains code and data for creating dynamic Bar Racing visualizations. A Bar Racing visualization is an engaging way to display changes in rankings or values over time, such as the cumulative installs per network over a period. It uses animated bar charts to show how these rankings evolve as time progresses.

## How it Works

1. **Data Preparation**: Start with a dataset containing information about the networks, time intervals, and cumulative values (e.g., installs) at each interval.

2. **Sorting**: Initially, the networks are sorted based on their cumulative values at the starting point to establish the initial ranking.

3. **Creating Bar Charts**: For each time step, a bar chart is generated. Each bar represents a network, and its height corresponds to the cumulative value at that time step.

4. **Animation**: As you progress through time steps, the bars move up and down based on how the cumulative values change. Networks with increasing values rise, while those with decreasing values fall.

5. **Dynamic Labeling**: Labels can be added to identify the networks, and these labels move with the bars as they rise or fall.

6. **Title and Summary**: Include a title for the visualization and optional summaries at each time step, which can provide additional context or insights.

7. **Export**: You can choose to display the visualization directly or export it as a video file (e.g., MP4) for sharing and presentations.

## Code Usage

The code in this repository demonstrates how to create Bar Racing visualizations using Python, specifically with the `bar_chart_race` library. You can find example code and data in the provided Jupyter Notebook (BarRacing.ipynb).

## Getting Started

To create your Bar Racing visualization, follow these steps:

1. Install the required libraries (if not already installed) using `pip install -r requirements.txt`.

2. Prepare your dataset in the required format, including columns for network names, time intervals, and cumulative values.

3. Customize the visualization by modifying the provided example code in the Jupyter Notebook.

4. Run the code to generate your Bar Racing animation.

5. Optionally, export the animation as a video for sharing and analysis.

## Example Output

![image](https://github.com/a1441/Installs_bar_chart_race/assets/49153959/1833bb18-3db2-44ff-8515-122755d39eeb)

[Watch the Bar Racing Visualization (MP4)](https://github.com/a1441/Installs_bar_chart_race/blob/main/bar_racing_installs.mp4)

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The Bar Racing visualization code is based on the `bar_chart_race` library.
- Special thanks to the open-source community for their contributions and inspiration.

Enjoy visualizing your data with Bar Racing!



