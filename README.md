# Designing a PRR configuration Manipulator for the desired task performance

We designed a 3 degree of freedom robot manipulator which has PRR configuration and deployed it to unscrew a bolt and touch one of the grades A, A-, A+. The torque required by the motor was determined by the dynamic equation of motion in which we were required to calculate the D-H parameters of PRR configuration, Jacobian of velocities, and inertia matrix etc. We inculcated OpenCV to detect the bolt and a reference center for coordinate transformation. We used google vision API service for OCR text detection and conversion of coordinates of the camera frame into real frame. After text extraction, we generated the coordinates of the desirable grade and commanded the robot to reach to that position and touch that grade.
- To witness the exceptional performance of the PRR configuration manipulator achieving an A+ grade, we invite you to watch the demonstration video accessible through the following link: https://iitgnacin-my.sharepoint.com/:v:/g/personal/kumar_rajesh_iitgn_ac_in1/ETxRbc7kMypEoT-xmOtjMV8BolDibP3kQssZZeQlkLDeLQ?e=kOjbai

## License
[MIT License](LICENSE)