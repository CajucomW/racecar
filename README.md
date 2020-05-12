# RaceCar

A simple, python-powered app displaying basic Object-Oriented Programming. I encountered this challenge while going through <a target="_blank" href="http://www.teamtreehouse.com/">Team Treehouse</a> challenges.

The code is written so it runs solely within the terminal.

- clone the repo
- go into Python through the terminal<br>
    <code>python3</code>
- import the class to make available<br>
    <code>from racecar import RaceCar</code>
- assign the class to a variable of choice to make an instance of the class<br>
    <code>x = RaceCar()</code>
- also set attributes within the class for "color" and "fuel remaining". We can start at the 0th lap. For example:<br>
    <code>x = RaceCar("red", 100)</code><br>
    <code>x.color</code> should return <code>red</code><br>
    <code>x.fuel_remaining</code> should return <code>100</code>
- setting an attribute to the <code>run_lap</code> method:<br>
    <code>x.run_lap(360)</code><br>
    should run the calculations within the method to adjust "fuel remaining" and "laps" attributes:<br>
    <code>x.fuel_remaining</code> should return <code>51.75</code><br>
    <code>x.laps</code> should return <code>360</code>
