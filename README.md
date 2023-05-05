Download Link: https://assignmentchef.com/product/solved-cse578-assignment-0-computer-vision-tasks-and-the-use-of-opencv-package
<br>
ASSIGNMENT 0

OVERVIEW &amp; PURPOSE

<ol>

 <li>The goal of the assignment is to introduce you to several computer vision tasks and the use of OpenCV package.</li>

 <li>You need to upload a pdf and a jupyter notebook file containing

  <ol>

   <li>The report</li>

   <li>The code that you wrote</li>

   <li>The input images/videos (if file too large – provide link to google drive)</li>

   <li>The output images/videos (if file too large – provide link to google drive)</li>

   <li>The file should be uploaded in the moodle portal.</li>

  </ol></li>

 <li>Include the assignment number, your name and roll number at the top-right of the first page of your submission.</li>

 <li>Make sure that the assignment that you submit is your own work. Any breach of this rule could result in serious actions including an F grade in the course.</li>

 <li>The experiments and report writing takes time. Start your work early and do not wait till the deadline.</li>

</ol>

<h1>INSTALLING OPENCV</h1>

The first step of doing this assignment is to install the OpenCV package on your computer. OpenCV is an open source library for developing computer vision applications. Please see: http://opencv.org for details of both installation and usage of the library. OpenCV has Linux, Windows and Mac versions available. Note that the compilation of the library from the sources would take a few hours. Make sure you installed the required libraries before compiling and installing OpenCV. Test your installation with a basic program to read write and modify an image. In linux, opencv is readily available through the built in software installation utilities. The primary goal of the assignment is the learning you get from writing the code and experimenting with various factors. So do write a detailed account of the various experiments and your learnings in your report. For this assignment, you are expected to write C/C++/python code for the tasks described in Section 2

<h1>TASKS</h1>

<h2>Chroma Keying with OpenCV</h2>

<ol>

 <li>Video &#x2194; Images: Write a program to convert a given video to its constituent images. Your output should be in a specified folder. Write another program that will merge a set of images in a folder into a single video. You should be able to control the frame rate in the video that is created.</li>

 <li>Capturing Images: Learn how to capture frames from a webcam connected to your computer and save them as images in a folder. You may use either the built-in camera of your laptop or an external one connected through USB. You should also be able to display the frames (the video) on the screen while capturing.</li>

 <li>Chroma Keying: Read about the technique of chroma keying. Following are a few good starting points:

  <ul>

   <li>Introduction: http://en.wikipedia.org/wiki/Chroma key</li>

   <li>Alvy Ray Smith and James F Blinn, ”Blue Screen Matting”, SIGGRAPH’96.</li>

  </ul></li>

</ol>

Create an interesting composite of two videos using this technique, possibly with one video including yourselves

ADDITIONAL PROBLEMS

Face detection on a set of images

<ol>

 <li>Video &lt;-&gt; Images: Write a program to convert a given video to its constituent images. Your output should be in a specified folder. Write another program that will merge a set of images in a folder into a single video. You should be able to control the frame rate in the video that is created.</li>

 <li>Capturing Images: Learn how to capture frames from a webcam connected to your computer and save them as images in a folder. You may use either the built-in camera of your laptop or an external one connected through USB. You should also be able to display the frames (the video) on the screen while capturing.</li>

 <li>Face detection: Read about the technique of face detection. Create a video of that integrates the face detected in frames using bounding box using this technique possibly with one video including yourselves. Use image difference to divide a video into shots</li>

 <li>Video &lt;-&gt; Images: Write a program to convert a given video to its constituent images. Your output should be in a specified folder. Write another program that will merge a set of images in a folder into a single video. You should be able to control the frame rate in the video that is created.</li>

 <li>Capturing Images: Learn how to capture frames from a webcam connected to your computer and save them as images in a folder. You may use either the built-in camera of your laptop or an external one connected through USB. You should also be able to display the frames (the video) on the screen while capturing.</li>

 <li>Dividing video into shots: A shot is composed of a number of frames that are presented from a continuous viewpoint. Create a folder with multiple video, each video forming part of a single shot also perform the experiment on a video that includes you.</li>

 <li>Source to understand better – https://stackoverflow.com/questions/5317744/what-is-the-best-way-to-divide-a-vide o-into-scenes-segments</li>

</ol>

<h1>REQUIREMENTS</h1>

<ol>

 <li>openCV</li>

 <li>python/C/C++</li>

 <li>Dataset of images and videos – to be prepared by you</li>

</ol>