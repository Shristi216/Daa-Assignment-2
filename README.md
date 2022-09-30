# DAA ASSIGNMENT-2
NAME: Shristi Gupta

ROLL No.: 23

BATCH: A2

Problem Statement : Implement a solution for Finding a summation of elements from a matrix.

Example: Accept a 2D matrix dimension. Populate using random number [non-zero]

Accept any five dimension values from the user for example [1,1] [4,10] 10,7] [15,3] [20,18] .Check the region covered by these points in the matrix.Calculate the boundary by either considering all points or ignoring few points which may not come on boundary [convex hull]. Find sum of elements in the region.

STEPS TO SOLVE:

Step 1:

Making a Matrix of 20x20. 

and we will Put Random numbers inside the matrix using the rand() function in c++.

![Matrix](https://user-images.githubusercontent.com/91418248/193193645-22757650-3d38-45d0-a489-b174f9f5e9b9.jpg)

20 x 20 2-D Matrix 

Each box represents a point on line graph

i.e matrix [4] [5] represent poit(4,5)

Step 2: 

We will take 5 points from the user.

![points](https://user-images.githubusercontent.com/91418248/193193994-15c95d4d-a082-4f95-9f78-81b6bee1d946.jpg)

shaded boxes: represents points used to generate convex hull

Step 3: 

Now we will be Checking for each point if it lies inside Convex Hull by using ConvexHull function.

![line1](https://user-images.githubusercontent.com/91418248/193194276-b95c84be-05cc-4688-ad7d-5a7d8ad1f664.jpg)
![line2](https://user-images.githubusercontent.com/91418248/193194353-eff3524a-d1c5-4f21-9e92-d581e5c80dfc.jpg)
![line3](https://user-images.githubusercontent.com/91418248/193194366-83811d2e-b0ec-4eab-8513-d0427bfa3cd3.jpg)
![line4](https://user-images.githubusercontent.com/91418248/193194377-160ba697-f371-4ffe-bf2d-771ee63d0f6b.jpg)


Step 4: 

If the point lies inside the Convex Hull then we will be adding the value inside that point i.e matrix into our answer.

![area shaded](https://user-images.githubusercontent.com/91418248/193194416-35cc572d-f412-4e65-8d01-8fbce7ae81f1.jpg)

Now the convex hull is created.




