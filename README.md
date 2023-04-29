# pands-Progect
Before we starting I need give you short explanation what the Data Set means. Some boring lines nessesary introduce us in high-brains world.
Data Set its a collection of related sets of information that is composed of separate elements but can be manipulated as a unit by a computer. Data Set is a collection of numbers or values that relate to particular subgect. 
One of the most well-known repositories for these datasets is the UCI Machine Learning Repository. 
Our goal this progect Fishers Iris to "research the data set and write summary about it" So...
The classification of this flowers was proposed Edgar Anderson (biologist) and callected the data to quantity the morphologic variation of Iris flowers of 3 related species. But Ronald Fisher (matematic) used this workshop and made it famous used a multivariate data set. Used as a beginners data set for machine learning purposes so we can feel free if we dont catch to much iformation for full understanding whole processes.
 The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the Lenght and the Width of the Sepals and Petals (in cm). In short : the goal is distinguish the species from each other.
In diagramms (which shows 3 colors - red=setosa, green=versicolor,blue=virginica) I noticed what Versicolor and Virginica always mixed together.While Setosa never come togheger none of them. I suppose is called "cluster analysis". But Im not good at maths,sorry. and I skip this part.
. Originally used as an example dataset on which Fishers linear discriminant analysis was applied it became a typical test case for many statistical classification techniques in machine learning such a support vector machines. Iris Data Set keep in open search in https://archive.ics.uci.edu/ml/datasets/iris. When you open this link you can see pretty simple site with main characteristic we talking before: a set of 150 records under 5 attributes.
 
 
 ![Iris_dataset_scatterplot](https://user-images.githubusercontent.com/124403326/234086234-03047f84-04fa-4207-9b6a-6e169d738ba2.svg)

 
 
Open the UCI Irvine Machine Learning Repository Iris data set I click Data Folder.Its show us all classification of iris. If you want to save it in your repository very handy to use Jupyter notebook. In CMD I open this note "jupyter notebook" and "import pandas as pd". Pandas its a one of library in Python and allow me retrieve what it has.  Importing data is the first step in any data progect.Next step is call " the read_csv()"function. I suppose it make my filepath to be readable in pandas memory. 

df = pd.read_csv (whole filepath I copy from machine repository)
Using df.shape, df.tail,df.head you can see more structure how it can be

Now we ready to git push this Data set to your repository.

Another intresting thing is using LOAD DATA.
This function (scikit-learn) allow us to see data keps,how build. We would be see how looks histograms and etc


