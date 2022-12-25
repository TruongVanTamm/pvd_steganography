**Only PNG Image** files should be used as cover image and final output image.

## Getting Started

Clone repository and enter the repository folder.

### Prerequisites

Requires,

- python3
- Python Image Library (PIL)

Install the dependancies using:

> pip install -r requirements.txt

### Usage:

To use the example `main.py` file:

#### Embedding

> Usage: python3 test_main.py e reference_png_input_image_path secret_input_file_path embedded_png_output_image_path

> Eg: python test_main.py E mario.png dsts.txt t.png

#### Extraction

> Usage: python test_main.py d reference_png_input_image_path secret_output_file_path embedded_png_input_image_path

> Eg: python test_main.py D mario.png op.txt t.png
