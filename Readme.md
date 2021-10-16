# Introducing *PlayFit*

## The Problem
Physical activities and relaxation techniques are an essential part of life that can help us maintain a good health. WHO recommends 150 minutes of moderate-intensity or 75 minutes of vigorous-intensity physical activity per week, or a combination of both. But during these tough and testing times of COVID, the lack of work-life balance and dependence on online services for most of the work has generated a sort laziness amongst people.

To deal with this an innovative hack is required, which can bring back people's interest in
physical activity.

## Inspiration
- A study among 1472 children and adolescents between 5 and 17 years of age from Canada showed that 18% adhered to the physical activity (PA) guidelines and 11.2% adhered to the screen-time (ST) recommendations during COVID-19 compared to 35% compliance with the PA guidelines and a 8–64% compliance with the screen-time (ST) guidelines in their PA report card of 2018. 
- As children sit continuously on chairs and floor while playing games, this increases the risk of developing muscle and joint problems like back and neck pain and headaches.

By acknowledging all these facts, we came up with a solution where a user can focus on his fitness while enjoying his desired game.

## The Solution
Our team tried to do this using gamification of fitness via Python, OpenCV and MediaPipe. A simple game could become a workout if instead of buttons it responds to a group of custom physically intensive commands set by the user and making the art of physically playing the game affordable as well as a workout.

![](./Assets/2.jpeg)

As this game requires the movements for up, down, left and right. Our model allows the user to access these actions by the gesture and the positioning of his body. Apart from this game, this model will work on any desirable game that can be played by these four movements. By this the user will not only be able to achieve his fitness goal but also it will reduce his screen-time too.

## Key Features:
 - Player can make movements in four directions (up, down, left, right) via gestures.
 ![](./Assets/3.jpeg)
 - Using the Pyautogui library, we will automatically trigger the required keypress events, depending upon the body movement of the person that we’ll capture using OpenCV and Mediapipe’s Pose Detection model.
 ![](./Assets/4.jpeg)
- Thus, the software can be used as a controller for multiple different games, that can be played using these four movements.