Arduino---Sem-2

## Bill of materials:
 4x Brushless motor + ESC ->these motors already have ESC (https://www.optimusdigital.ro/ro/motoare-fara-perii/3628-motor-brushless-black-widow-1806-2300kv-18a-cu-esc-intern-ccw.html?search_query=motor+brushless&results=80)<br>
 +another option -> https://www.optimusdigital.ro/ro/motoare-brushless/2785-pachet-cu-4-motoare-brushless-2206-baby-beast-v2-cwccw-i-4-esc-uri-afro-12-a.html<br>
 4x Propellers (Preferably 3D printed in the lab)<br>
 1xBattery - LiPo battery (3000mAh - 11.1 V - aprox 15 min of flight time)<br>
 1xFrame -> 3D printed<br>
 1xLiPo Charger<br>
 2xArduino uno<br>
 2xNRF24L01<br>
 1xMPU6050<br>
 4xcapacitors 22pF<br> 
 2xcapacitor 10uF<br>
 2xresistor 4,7kOhm<br>
 2x3,3V linear stabilizer<br>
 some goldpins (female and male)<br>
 2xJoysticks<br>
 LED diode<br>

## Short description of the project 
The main goal here is to make a functional , fully controlable DIY drone, under the price of the market (and hopefully better) , which we can later customize as we see fit (we can add video cameras,make it to follow us based on GPS signal from our phone,etc).

## How it works
The idea behind a quadcopter is the fact that due to it's shape and motor positioning, the drone will be innately more stable, and so it makes it easier for the one building it to stabilize it. The way I am going to make the drone stabilize itself is by using 3 PID algorithms for every axys (X,Y,Z).I'm also 
