Aim: Implementation of k means ++ algorithm. 

Algorithm:
          Step 1: Import pandas and numpy libraries
          
          Step 2: Read dataset ‘Mall_Customers.csv’ 
          
          Step 3: Read and verify the dataset by checking its feature names, shape, info, head, tail, unique etc…
          
          Step 4:create a K-Means++ model using KMeans from scikit-learn. The init parameter is set to 'k-means++' to specify the K-Means++ initialization. 
          
          Step 5:Fit the K-Means model to the data. 
          
          Step 6:Choose the first centroid randomly from the data points. 
          
          Step 7:For each data point, calculate the distance (usually squared Euclidean distance to the nearest existing centroid.
          
          Step 8:Select the next centroid from the data points with a probability proportional to the square of the calculated distance.
          
          Step 9:Repeat steps 7 and 8 until k centroids are chosen.
          
          Step 10:Use the selected initial centroids as the starting point for the regular k-means algorithm.
          
          Step 11:From sklearn.metrics import silhouette_score and measure the performance.
          
          Step 12:visualize the data points and cluster centers using matplotlib. 
          
          
          
  
      
