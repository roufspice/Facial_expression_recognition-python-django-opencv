# Facial_expression_recognition-python-django-opencv

Empathize emotions web applications along with recognized person's facial expressions<br>

General Languages and versions
<pre>
<code>
c Python version: 3.6 or 3.7.0
• Tensorflow -cpu version : 2.3.0
• opencv-python version : 4.1.2.30
• Keras version: 2.4.3
• django version : 3.1.1

</code>

</pre>


<h3> Demonstration Video </h3>
<p><a href="#">click here</a> if you want to see a demostration video to run our web application. </p>

<div>
  <img src ="https://github.com/roufspice/Facial_expression_recognition-python-django-opencv/blob/master/images/image_01.png" width="500" height="250">
</div>




<h2>1. Basic functions of this application</h2>

<h3>1.1 Realize smile expression recognition app</h3> <br>

• Turn on the camera when click the smile train service. - '웃는표정학습'.<br>
• The trained CNN model extracts the users' smile features and smile results of percent and saves them in the database - sqlLite.<br>
• The image is read by the camera and input into the CNN model to save the users' best smile expression frame of the face.<br>
• We named this course as a smile training phase and the course will be going on for 3 steps.<br>
• In every each course, trained CNN model checks users' smile faces which is read by the camera and saves the best frame based on smile percent which has been calculated by trained model.<br>
• The best frame will be provided to users and after smile training phase users can save their smile images or not.<br>


<h3>1.2 Website application construction: using django framework.</h3>
• Use Python to read the camera screen, and realize application using OpenCV's python library to open the system USB camera. - web cam - 

• To realize this application referenced scripts are <a href="https://github.com/linlinhaohao888/Monitor">here.</a>


<h3> CNN classification model structure </h3>
• How to use and modify CNN model : <a href="https://github.com/roufspice/face_expression_miniproject">click here.</a><br>




