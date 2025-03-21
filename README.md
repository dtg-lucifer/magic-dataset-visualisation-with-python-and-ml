# Magic Dataset Visualization Project

This project is a visualization of the Magic Gamma Telescope dataset from Free Code Camp. The dataset contains information about gamma rays captured by a telescope, and the goal is to visualize and analyze this data.

## Dataset

The dataset used in this project is the Magic Gamma Telescope dataset, which is open source and copyright-free. It captures the effects of gamma rays from space via a camera.

- [Dataset URL](https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope)

## Project Structure

- `data/magic.csv`: The dataset file containing the gamma ray data.
- `magic.ipynb`: Jupyter notebook containing the code for data visualization and analysis.

## Installation

To run this project, you need to have Python and Jupyter Notebook installed. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook `magic.ipynb` using the following command:

```bash
jupyter notebook magic.ipynb
```

2. Run the cells in the notebook to load the dataset, transform the data, and visualize it.

## Data Transformation

The `class` column in the dataset is transformed so that if the class is `g`, it is represented as `1`, otherwise `0`. This transformation is done to make it easier for the computer to process the data.

## Visualization

The notebook contains various visualizations to analyze the gamma ray data. For example, a scatter plot is created to visualize the relationship between `fLength` and `fWidth` with different colors representing different classes.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- Free Code Camp for providing the project idea.
- UCI Machine Learning Repository for providing the dataset.

