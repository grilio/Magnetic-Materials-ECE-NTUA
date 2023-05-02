# Magnetic-Materials-ECE-NTUA
In this repository I have uploaded the jupyter notebooks I used to extract plots needed for exercises and lab reports for the course "Magnetic Materials" in NTUA 2022-23.<br>
Some plots and simulations can be seen below: <br>
<br>
To find the angle of the magnetization we can solve the equation $h_yk^4+2(h_x-1)k^3+2(h_x+1)-h_y=0$. At first there are 2 or 4 real solutions. For the first value, knowing that we strt to apply the field from negative to positive values we keep an initial angle. Then we compare the value with the previous one and we keep the closest one. We do this as long as $h_x^{2/3} + h_y^{2/3} < 1$, then the magnetization flips orientation according to the picture below.
<br>
![ezgif com-resize](https://user-images.githubusercontent.com/106864601/218151993-a7d12314-5a2f-4de6-aa54-f19fc8cd6fd9.gif)
<br>
<br>
