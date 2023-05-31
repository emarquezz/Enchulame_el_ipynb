# Enchúlame_el_ipynb

Make your Jupyter notebooks pretty with custom colors and a table of contents.

## Features

- Automatically colorize markdown titles based on hierarchy
- Generate a table of contents with links to sections
- Create a new, pretty version of your notebook without modifying the original

## Installation

1. Install the required dependencies: `pip install seaborn`
2. Clone this repository and navigate to the project directory.

## Usage

1. Import the necessary modules and define your color palette:
```python
import seaborn as sns
from my_dress_up_jupyter import cutiepy_nb

sns_palette = 'gnuplot'
colors = sns.color_palette(sns_palette, 4).as_hex()
```

2. Run the `cutiepy_nb` function with the path to your notebook and the desired colors as arguments:

```python
file = '/path/to/notebook.ipynb'
cutiepy_nb(file, colors=colors, save=True)
```

 3. A new, pretty version of your notebook will be created in the same directory with the original name + the word 'chulo'.
 

## Customization
You can customize the colors used for different levels of markdown titles by modifying the colors argument when calling the cutiepy_nb function.

## Contributing
Contributions are welcome! Please feel free to open an issue or submit a pull request.
Is there anything else you would like to include in the README?
