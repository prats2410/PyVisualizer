# PyVisualizer

== PyVisualizer is a small clone of streamlit.
== Your Graphs/Tables can be converted innto Bootstrap4-driven diagrams
   ready for presentation.
== Suppose you write a code for Data Analytics and now, you want to create
   a PyVisualizer output... Follow the steps below"
   (*Make sure your code, visualize.py and dependencies folder are in same directory*)
   Step 1:
     in your .py file, first import pyvisualizer with the command:
	>> from visualize import visualizer
   Step 2:
     Now initialize a visualizer object with the following command:
        >> viz = visualizer()
   Step 3:
     Now, in your Data Analytics, suppose you have written plt.show()
     somewhere in the code for generating a graph / visual-output...
     Instead of that, you should do 
     >> viz.jumbocard(Title = "Graph Title",ImageObject = plt, Description = "The Description for your Graph")
     
     Other than Jumbocard, there is support for Cards and RenderTable as well.
  
   Step 4:
     Finally, when you are done with creating all the visualizations,
     Enter the following command:
     >> viz.generate_output()
   
   Step 5:
     A folder named output is created in the same directory which has output HTML
     file.


NOTE: * An Example Code is Given in trails.py
