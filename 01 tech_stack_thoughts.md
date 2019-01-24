# This will be a new challenge, what are my options?

Inspiration - [forestry decision support tool](http://www.forestdss.org.uk/geoforestdss/esc4.jsp#)
This was built using javascript, leaflet, CSS, HTML - not an area I have significant experience with.

Another option is using the same approach as for my MSc Dissertation - a Jupyter Notebook and ipywidgets, and folium. Enhanced with ['interact'](https://nbviewer.jupyter.org/github/python-visualization/folium_contrib/tree/master/notebooks/)

For access by the customer this would need to be published, potentially using [nbviewer](https://github.com/jupyter/nbviewer/)

As recommended in [this blog](http://buklijas.info/blog/2018/10/01/making-web-apps-with-jupyter-notebook/) could be achieved using [appmode](https://github.com/oschuett/appmode) which is
a Jupyter extension that turns notebooks in to webapps, and then [binder](https://mybinder.org/) to access as a webpage by customers.

"Binder uses the BinderHub technology to generate a Docker image from this repository. The image will have all the components that you specify along with the Jupyter Notebooks inside. You will be able to share a URL with users that can immediately begin interacting with this environment via the cloud. Binder’s goal is to enable as many analytic workflows as possible."
