# pands-Progect
Before we starting I need give you short explanation what the Data Set means. Some boring lines nessesary introduce us in high-brains world.
Data Set its a collection of related sets of information that is composed of separate elements but can be manipulated as a unit by a computer. Data Set is a collection of numbers or values that relate to particular subgect. 
One of the most well-known repositories for these datasets is the UCI Machine Learning Repository. 
Our goal this progect Fishers Iris to "research the data set and write summary about it" So...
The classification of this flowers was proposed Edgar Anderson (biologist) and callected the data to quantity the morphologic variation of Iris flowers of 3 related species. But Ronald Fisher (matematic) used this workshop and made it famous used a multivariate data set. Used as a beginners data set for machine learning purposes so we can feel free if we dont catch to much iformation for full understanding whole processes.
 The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the Lenght and the Width of the Sepals and Petals (in cm). In short : the goal is distinguish the species from each other.
In diagramms (which shows 3 colors - red=setosa, green=versicolor,blue=virginica) I noticed what Versicolor and Virginica always mixed together.While Setosa never come togheger none of them. I suppose is called "cluster analysis".
Originally used as an example dataset on which Fishers linear discriminant analysis was applied it became a typical test case for many statistical classification techniques in machine learning such a support vector machines. Iris Data Set keep in open search in https://archive.ics.uci.edu/ml/datasets/iris. When you open this link you can see pretty simple site with main characteristic we talking before: a set of 150 records under 5 attributes.
 
 
 ![Iris_dataset_scatterplot](https://user-images.githubusercontent.com/124403326/234086234-03047f84-04fa-4207-9b6a-6e169d738ba2.svg)

 
 
Open the UCI Irvine Machine Learning Repository Iris data set I click Data Folder.Its show us all classification of iris. If you want to save it in your repository very handy to use Jupyter notebook. In CMD I open this note "jupyter notebook" and "import pandas as pd". Pandas its a one of library in Python and allow me retrieve what it has.  Importing data is the first step in any data progect.Next step is call " the read_csv()"function. I suppose it make my filepath to be readable in pandas memory. 
df = pd.read_csv (whole filepath I copy from machine repository)
Using df.shape, df.tail,df.head you can see more structure how it can be

Now we ready to git push this Data set to your repository.
Progect point has conclusion in few steps:
1. Load the data
2. Analyze and visualize the dataset
3. Model training.
4. Model Evaluation.
5. Testing the model.
   In this article of Iris Flowers Classification, we will be dealing with Logistic Regression Machine Learning Algorithm. First, we will see logistic Regression, and then we will understand the working of an algorithm with the Iris flowers dataset. Iris Dataset contains features of different flower species. Independent features in this dataset are Sepal Length, Sepal Width, Petal Length, and Petal Width. All these lengths were in centimeters.
   
   In my notebook at the beggining you can see I import few libraries from Python. Its need for calling functions and to see how work each method separate of each other or how it works together.

 Intresting thing is using LOAD DATA.
 For this I call scikit-learn (use for modeling, already has this data set built). Choose dataset.load_iris (open and see the features/species/etc). After that you can choose any subject to testing/reaserch. For excample, "data target" show me what our target just give me 0 and 1 or 2 and this indicating or not a flower that the measurement is from  . For VISUALIZATION we use NumPy(its good for at quick efficiant computation over array). I create Pandas Frame (its pretty for columns differernt types and histogramms). df = pd.DataFrame also has promp shows species: df data target/data head/describe( the last one contains minimum and max mean)
 In basic sence of DISTRIBUTIONS we can see different shape of species of flowers(Beautyfull!) and each of features (sepal/petal). In section EDA you can see pretty single seaborn lie of line of code. We see a plotting every variable in our dataset againist every other variable (I use "hue" metod for colorful contrast). Here we can see what Setosa Iris is also stay away like bunch.
 Next step in analisis is TRAIN TEST and MODELING(most basic sence fundamentally:mapping inputs to outputs in an intelligent way).Prepairing for modeling one of the most important parts about is always put aside part of your data to evaluate our model on in the very  end. Evaluate is important concept while it not seen till we were training/fitting our model. One of the way to do this is creat the thing called a train test split. And this is setting aside a little piece of our data for very end to evaluate our final model on. In a middle of this block we put cross-validation(It should be help to do this easier). As I import scikit-learn in the beginning, I fount in this selection and import train_test_split (prompts help to read about more there, you need just put "?" after that). In this line "df_train,df_test = train_test_split(df,test_size=0.25)" - I put size 0.25. Its mean I take small part (25%),split it up into 75% of whole our data and "forget it" untill very end. And this small piece I used for evaluate our final model.
 
 
 
 
 
 
 
 
This function (scikit-learn) allow us to see data keps,how build. We would be see how looks histograms and etc





My Sources for search:
1. https://archive.ics.uci.edu/ml/datasets/iris
2. https://en.wikipedia.org/wiki/Iris_flower_data_set
3. https://en.wikipedia.org/wiki/K-means_clustering
4. https://stackoverflow.com/
5. https://data-flair.training/blogs/iris-flower-classification/
6. https://www.analyticsvidhya.com/blog/2022/06/iris-flowers-classification-using-machine-learning/
7. https://www.youtube.com/watch?v=rdaG53khzv0
8. https://www.youtube.com/@ProjectDataScience
9. https://www.youtube.com/watch?v=pTjsr_0YWas&t=300s
10.https://www.youtube.com/watch?v=VgHoZ62rnkA
11.https://www.youtube.com/watch?v=LMqC7-QbC9k
12.https://www.youtube.com/watch?v=2WL-XTl2QYI
13.https://www.youtube.com/watch?v=Y17Y_8RK6pc&t=45s
14.https://www.youtube.com/watch?v=8J2ArnIRvH8&t=419s
15.https://www.w3schools.com/python/




