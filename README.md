

<!-- INTRODUCTION -->
<br />

![Kalman Filter - Asteroids Project](/assets/title.jpg?raw=true "Index")

  <p align="center">
    An implementation of a Kalman Filter to estimate the positions of asteriods moving in space and pilot a craft around them.
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Estimation](#estimation)
  * [Navigation](#navigation)
* [Powered by Python](#built-with)
* [License](#license)
* [Contact](#contact)

<!-- ABOUT THE PROJECT -->
## About The Project

This is an implementation of a Kalman Filter in an inventive excercise to create a self-piloting craft that can navigate around moving obstacles. Due to proprietary code restrictions, I cannot publicly share the code other than a short overview!

### Estimation

![Estimation of the Asteroids' Current Positions](/assets/estimation.gif?raw=true "Estimation of the Asteroids' Current Positions")

Here's an example of how we use the Kalman Filter to predict where these asteroids will move through space by tracking each of their positions and estimating their next move. I've slowed down the gif so you can see our prediction (the circles) converge with the actual future positions of the asteroids. 

### Navigation

![Craft Navigation through Asteroid Field](/assets/navigation.gif?raw=true "Craft Navigation through Asteroid Field")

Here's how we use these estimates to create a chart of all future asteroid positions to navigate around them to avoid a collision. We send a craft through this asteroid field and its objective is to move through the field without hitting any asteroids, for which it will need to predict the asteroid's next position. Our pilot makes a valiant effort and reaches the other side of the field safely!


## Built With
This project was built in Python version 3.8.3 using NumPy.
* [NumPy](https://numpy.org/)

<!-- LICENSE -->
## License
Not distributed for public use.

<!-- CONTACT -->
## Contact
Jasmine Sondhi - [LinkedIn](https://www.linkedin.com/in/jasmine-sondhi/) - jsondhi@outlook.com
