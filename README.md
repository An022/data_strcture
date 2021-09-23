# self_learning-data_strcture
Reference to Stanford University’s assignment CS106AP: Programming Methodologies in Python and CS106B: Programming Abstractions as practice, focusing topic: data strcture
## Projects Source Codes:
* [popular_baby_names](https://github.com/An022/self_learning-image_processing/edit/main/01_photoshop/stanCodoshop.py)\
  The program graphs the popularity of U.S. baby names from 1900 through 2010, allowing users to analyze interesting trends in baby names over time, by using map to build data structures and object-oriented programming present simple graphics to create a large-scale application.

  * [babygraphics.py](https://github.com/An022/self_learning-data_strcture/blob/main/popular_baby_names/babygraphics.py)
      * get_x_coordinate(width, year_index): 
        
        Given the width of the canvas and the index of the current year in the YEARS list, returns the x coordinate of the vertical line associated with that year.
      * draw_fixed_lines(canvas):
        
        Erases all existing information on the given canvas and then draws the fixed background lines on it.
        
      * draw_names(canvas, name_data, lookup_names):
        
        Given a dict of baby name data and a list of name, plots the historical trend of those names onto the canvas.
  
  * [babynames.py](https://github.com/An022/self_learning-data_strcture/blob/main/popular_baby_names/babynames.py)
      * add_data_for_name(name_data, year, rank, name):
        
        Adds the given year and rank to the associated name in the name_data dict.
      * add_file(name_data, filename):
        
        Reads the information from the specified file and populates the name_data dict with the data found in the file.
      * read_files(filenames): 
        
        Reads the data from all files specified in the provided list into a single name_data dict and then returns that dict.
      * search_names(name_data, target):
        
        Given a name_data dict that stores baby name information and a target string, returns a list of all names in the dict that contain the target string. 
        This function should be case-insensitive with respect to the target string.
      * print_names(name_data):
      
        Given a name_data dict, print out all its data, one name per line.
        The names are printed in alphabetical order, with the corresponding years data displayed in increasing order.


        
        
