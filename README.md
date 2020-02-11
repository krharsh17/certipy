# certipy

A python snippet to generate e-certificates in bulk.

## How to use

- Make sure you have python & pip installed
- Install pillow (for image processing) by running `pip install pillow`
- Install pandas (for data processing) by running `pip install pandas`
- Put a sample certificate with blank fields in the project folder by the name 'certificate.png'
- Put the input file containing a list of the participant names by under a column name
- [Optional] If you want to use custom fonts, place them in the fonts folder and put their location in the `generate_certificates()` call
- Inspect the generate_certificates call closely and put in your details such as id prefix, font sizes and most importantly, **the coordinates of the name and id placeholder in the sample**
- Once the preparation is done, run `python run.py` in a terminal pointing to the project directory

The certificates will be saved in a folder called *exports*
