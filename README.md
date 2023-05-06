Download Link: https://assignmentchef.com/product/solved-ece561-homework-1-projection-reconstruction
<br>



<strong>Note: </strong>Homework should be done individually but discussion is encouraged. If you must use your phone to scan your work please use a proper digital scanning app to maintain legibility. This particular assignment requires the use of a digital camera. The report shall contain images, psedo-code and output of your algorithms. Homework is out of 10pts. You may pick <strong>one </strong>of the following 10 point problems:

<ol>

 <li>A Manual 3D Scanner

  <ul>

   <li>(1pts) Pick a salient object in your vicinity. Using a digital camera, take a stereo image of a single object. That is, take two pictures from slightly different camera positions. Ideally, the object takes up a large portion of the frame.</li>

   <li>(1pts) Manually identify and label visually a few sparse corresponding points in both pictures. You will need to identify the image coordinates of these points as well.</li>

   <li>(3pts) Recover the camera parameters using the essential or fundamental matrix using 8-point algorithm (You can assume one of your camera is fixed at origin with rotation matrix to be identity). Include pseudocode.</li>

   <li>(5pts) Recover the sparse 3D cloud points of the object from your marked points. Show results for both:

    <ol>

     <li>linear optimization</li>

     <li>non-linear optimization (<em>hint: You may use Matlab’s </em><em>fminunc or </em><em>lsqnonline </em>)</li>

    </ol></li>

  </ul></li>

</ol>

<ol start="2">

 <li>Primitive Panorama Stitching

  <ul>

   <li>(1pts) Pick a wide-angle scene you would like to capture. Using a digital camera, take two images from the same position but with different angles. Ideally, there will be some overlap between the two images.</li>

   <li>(3pts) Find the SIFT-key points and descriptors for both the images (<em>hint: You may use open source code and package</em>).</li>

   <li>(3pts) Match the correspondence points. Include pseudocode. Show visually these matched pairs of points.</li>

   <li>(3pts) Run RANSAC to estimate homography and stitch the two images together and include the final image in your report.</li>

  </ul></li>

</ol>

1