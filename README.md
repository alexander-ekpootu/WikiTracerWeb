# WikiTracerWeb
Basic FrontEnd + Backend For WikiTracer Project. Ongoing

# Wiki Path Finder
The Wiki Path Finder is a Flask web application that allows users to find the shortest path between two Wikipedia articles. The application uses a breadth-first search algorithm to explore the Wikipedia network, and the resulting path is displayed in a list.

# How to use
Enter the start URL and end URL for the Wikipedia articles you want to find a path between.
Click the "Find Path" button.
If a path is found, it will be displayed in a list below the form. Each item in the list is a link to a Wikipedia article.
If no path is found, a message will be displayed indicating that no path was found.
# Technologies used
Python
Flask
BeautifulSoup
jQuery
# How to run locally
Clone this repository.
Install the required packages.
Run the Flask application by executing the Backend.py file in your terminal, you will have to change some paths to 
match your local setup.
Open your web browser and navigate to http://localhost:5001.
Enter the start URL and end URL for the Wikipedia articles you want to find a path between, and click the "Find Path" button.

# Note
Note that the Wiki Path Finder project is currently ongoing and being optimized for efficiency. The algorithm used to explore the Wikipedia network can take a while to explore all possibilities, especially for longer paths. I am working on improving the efficiency of the algorithm, possibly by implementing a heuristic(difficult due to nature of wiki links) or parallelizing the search process. Also, working on some css for frontend.
