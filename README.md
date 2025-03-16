This project is inspired by James Bruton, and you can check out his video here: https://www.youtube.com/watch?v=AEXz8xyTC54.

One of the challenges in his design is that the walking robot wobbles back and forth when taking a step. Additionally, because the "foot" is flat, controlling the robot becomes more difficult due to the discontinuity in the differential equation.

To address this, I designed a walking robot with a spherical foot, ensuring a continuous differential equation. While the system remains nonlinear and difficult to linearize, it turns out to be quite stable with simple control. You can find the implementation in the attached file.
