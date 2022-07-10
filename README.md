# Food-Focusing
## <strong>Overcome the one-focusing limit of the primary camera</strong>
</br>
<p>
  The typical smartphone Galaxy and iPhone support food and portrait filters. All of these filters focus on the circular shape of the object. However, there is a limitation that <strong>fixed circle-shaped focusing support cannot be focused on cafe drinks or bread-shaped ones</strong>, so our team worked on this project to implement the function of finding the outline of the object and making the outline range out of focus.
</p>
</br>
For maximum lightness and ease of use, the project was implemented using technologies such as edge detection, edge contour detection and area alignment, and Gaussian blur for the purpose of implementing the project using only openv function, not artificial intelligence's area division technology. For edge detection, we used Canny Edge detection, Dilate operation, and Erode operation, and for edge detection, we created the Contour Mask corresponding to the largest contour extracted using findContours(). After smoothing the mask, Gaussian blur and morphology techniques were used for blur processing, and then the extracted mask was made into three dimensions to extract the object and extract the background. Finally, the background blur processing and the two images were combined to obtain the final result.
</br>
</br>
** There is a limitation that food photos that are not clearly defined by the stained contour cannot be detected due to the use of artificial intelligence's area division technology, but we solved the problem by narrowing the goal of making it light and changing it to Food→Cafe.


### date: 2021.01.20 ~ 
### collaborator: @mintai09 </br>
🕋 Using Selenium from Jupyter Lab
🕋 Using "searchWeeklyBoxOfficeList" Open API from korea film council

<p>
  <em>
    Hi there 👋</br>
    This is a project that crawling about movie reviews from the audience.
    in "Naver Movies" and then analyzes the psychology of the audience.
  </em>  
</p>
