# This will be a new challenge, what are my options?

Inspiration - [forestry decision support tool](http://www.forestdss.org.uk/geoforestdss/esc4.jsp#)
This was built using javascript, leaflet, CSS, HTML - not an area I have significant experience with.

Another option is using the same approach as for my MSc Dissertation - a Jupyter Notebook and ipywidgets, and folium. Enhanced with ['interact'](https://nbviewer.jupyter.org/github/python-visualization/folium_contrib/tree/master/notebooks/)

For access by the customer this would need to be published, potentially using [nbviewer](https://github.com/jupyter/nbviewer/)

As recommended in [this blog](http://buklijas.info/blog/2018/10/01/making-web-apps-with-jupyter-notebook/) could be achieved using [appmode](https://github.com/oschuett/appmode) which is
a Jupyter extension that turns notebooks in to webapps, and then [binder](https://mybinder.org/) to access as a webpage by customers.
To open in 'appmode' automatically on Binder need to change the Binder url by [placing `"%2Fapp%2F"` before the path to the Jupyter notebook in the urlpath.](https://github.com/oschuett/appmode/issues/13) E.g. https://mybinder.org/v2/gh/JuanCab/AstroInteractives/master?filepath=Interactive_HR_Diagram.ipynb becomes https://mybinder.org/v2/gh/JuanCab/AstroInteractives/master?urlpath=%2Fapps%2FInteractive_HR_Diagram.ipynb

According to same page:
If you want to use mybinder add the following environment.yml file to your repository:

channels:
  - conda-forge
dependencies:
  - appmode

[See this for appmode in Binder too](https://github.com/binder-examples/appmode)

Example Binder link to Notebook - https://mybinder.org/v2/gh/joshwapiano/amrtool/master?filepath=pandas_df_testing_01.ipynb
Example Binder link to appmode Notebook - https://mybinder.org/v2/gh/joshwapiano/amrtool/master?urlpath=%2Fapps%2Fpandas_df_testing_01.ipynb

"Binder uses the BinderHub technology to generate a Docker image from this repository. The image will have all the components that you specify along with the Jupyter Notebooks inside. You will be able to share a URL with users that can immediately begin interacting with this environment via the cloud. Binder’s goal is to enable as many analytic workflows as possible."
