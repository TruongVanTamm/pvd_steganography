**Only PNG Image** files should be used as cover image and final output image.

### Prerequisites

Requires,

- python3
- Python Image Library (PIL)

Install the dependancies using:

> pip install -r requirements.txt

### Usage:

To use the example `main.py` file:

#### Embedding

> Usage: python3 main.py e reference_png_input_image_path secret_input_file_path embedded_png_output_image_path

> Eg: python main.py E cover.png text.txt input.png

#### Extraction

> Usage: python main.py d reference_png_input_image_path secret_output_file_path embedded_png_input_image_path

> Eg: python main.py D cover.png text1.txt input.png
