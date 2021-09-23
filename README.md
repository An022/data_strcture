# self_learning-data_strcture
Reference to Stanford University’s assignment CS106AP: Programming Methodologies in Python and CS106B: Programming Abstractions as practice, focusing topic: data strcture
## Projects Source Codes:
* [popular_baby_names](https://github.com/An022/self_learning-image_processing/edit/main/01_photoshop/stanCodoshop.py)\
  The program graphs the popularity of U.S. baby names from 1900 through 2010, allowing users to analyze interesting trends in baby names over time, by using map to build data structures and object-oriented programming present simple graphics to create a large-scale application.

  * [babygraphics.py](https://github.com/An022/self_learning-data_strcture/blob/main/popular_baby_names/babygraphics.py)\
      * get_x_coordinate(width, year_index):\ 
        Given the width of the canvas and the index of the current year in the YEARS list, returns the x coordinate of the vertical line associated with that year.
      * draw_fixed_lines(canvas):
        Erases all existing information on the given canvas and then draws the fixed background lines on it.
        
      * draw_names(canvas, name_data, lookup_names):
        Given a dict of baby name data and a list of name, plots the historical trend of those names onto the canvas.
  
  * [babynames.py](https://github.com/An022/self_learning-data_strcture/blob/main/popular_baby_names/babynames.py)
  Exacuating basic processing imagine building a mini photoshop, which compares a series of pictures,\
  then renew the pixel to erase the pedestrian in the photo by returning the color distance between pixels and mean RGB value.

  ```
  We compare a series of pictures, then renew the pixel to erase the pedestrian in the photo.
  Returns the color distance between pixel and mean RGB value
  
  pre-condition:
  Input:
        pixel (Pixel): pixel with RGB values to be compared
        red (int): average red value across all images
        green (int): average green value across all images
        blue (int): average blue value across all images
  post-condition: 
  Returns:
        dist (int): color distance between red, green, and blue pixel values
  ```
