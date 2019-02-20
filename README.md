# GLobalizing_Entity_Embedding
please Follow my blog to get an idea on entity embedding<a href="https://medium.com/@anzanfas/my-understanding-on-embedding-for-beginners-c149d67ea7fd"> Entity Embedding Blog</a></br>
Here i am building this library to just give the dataset as input and what are the catagory fetures should be indicated by you..</br></br>
Then model it self will get train using the nural network and save your catagorical fetures weights to the pickle files..</br>
then you can use that data to do a PCA and visualize it..

## steps need to followed

<ol type="I">
  <li>import the Globalized_Network_Design.py file</br></li>
  <li>Create a Directory call <b>models</b> where your <b>.ipynb</b> file is located</li>
  <li>
   User need to provide:
  <ul>
  <li> [cat_columns]= Pass Catagorical Columns using list </li>
  <li>[X_Trainb_Data]= Independant Variables as input</li>
  <li> [Y_Train]=Training Dataset in pandas.core.series.Series Format</li>
  <li>  [epochs]=default givin as 20 according to assumption</li>
  <li> [batch_size]=default givin as 128 according to assumption</li>
</ul> </li>  
</ol>

## Note: I have attached sample Globalized_Network_Design.ipynb file you can use It For your Refereces.
