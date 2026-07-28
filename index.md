# Rocket Flight Test and Data Logger
This project is a rocket flight test system designed to spin the gyroscope with a DC motor and a microcontroller. The speed and direction of the motor is controlled with a bluetooth module. When building the gyroscope, I had to integrate electronics, programming, and mechanical design while overcoming many different challenges in every process.

<!--- You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:-->

<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Jairus B | American Canyon High | Mechanical Engineering | Incoming Senior

<!--- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.** -->

![HeadstoneImage](JairusB.png)

# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/jX32oZjV1kk?si=trR9E7ptVGnPHxqI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Description:**
For my final milestone, I connected a bluetooth module to my Arduino. This allowed me to control the motion of my motor and gyroscope with a wireless connection. After that, I created an interface in Visual Studio Code with Python. I utilized Tkinter to create a window with different buttons that correspond to the same inputs that have differing speeds in my Arduino IDE code. 

**Challenges and Triumphs of BSE:**
Coming into BlueStamp Engineering, I had little with eletronics, programming, and designing with CAD. Although there were many other challenges that came along the way, the biggest challenge for me was learning to design with CAD. Most of my project had to be 3D printed, so I had to design each part in Onshape. Despite this issue, I was able to persevere and work through these problems. Once I learned the basics with a few tutorials, I was able to figure out how to CAD and build my project. 

**Key Topics:**
Throughout my time in BlueStamp Engineering, I learned how to program an Arduino and connect electronic components such as motors, sensors, batteries, and Bluetooth modules. I also learned CAD and 3D printing by designing and assembling custom parts for my project. Through testing and troubleshooting, I improved both the mechanical and electrical parts of my design. I also documented my work through code, videos, and a GitHub portfolio.

**Future Aspirations:**
In the future, I hope to study mechanical or aerospace engineering and continue building projects that combine coding, electronics, and design. I want to improve my CAD, programming, and problem-solving skills through more hands-on experiences. I also hope to work on technology related to robotics, transportation, or aerospace. Ultimately, I want to use engineering to create practical solutions that make a meaningful impact.


# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/2mdTbg3afOQ?si=Ub_4Ibfs9nyURTU-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Description:**
In my second milestone, I powered the rotation of my gyroscope with a DC Motor. I've done this by utilizing 2 gears at a 2:1 rate, motor driver, Arduino UNO microcontroller, and a battery pack with 5 AA batteries. I electrically connected them by hooking up the battery pack to the motor driver, which is connected to the motor and microcontroller, so that enough voltage is provided for the circuit. The motor driver gives enough current to the DC motor, so that it can spin the gear attached to it, which spins the gyroscope via a rod with a gear attached to it. The Arduino serves as like the brain of the system. After I created a program to control different speeds for the motor, I uploaded that code to the Arduino so that it can tell the motor driver how to spin the DC motor depending on what I input. 

The most surprising part of this project was having to learn more about different gear ratios and actually testing them. At first, my initial gear ratio didn't work and my DC motor would stall. After learning about the appropriate number of teeth and gear ratio for my situation, I was able to spin the gyroscope with little to no problems.

**Challenges Overcame:**
The main challenge that I have overcome since the last milestone is getting more comfortable and faster with CAD. Creating new sketches became a lot easier as I got more familiar with Onshape. Also, I got more familiar with my components and was able to identify what was wrong a lot quicker. 

**Next Steps:**
For my final milestone, I need to connect a bluietooth module to my microcontroller, allowing wireless control. Afterwards, I want to create an interface which will make it cleaner to look at and easier to control my motor.  

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/KMn0VY9GALc?si=kJGqpZ7F-u1yZTXA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Description:**
For my Rocket Flight Test and Data Logger, I plan on attaching a gyroscope to a wooden base. Then I will spin the gyroscope with a motor via a gear connection. Currently, I have a gyroscope attached to vertical wooden supports on top of a wooden base. The gyroscope has 3 main parts: the outer frame, rotating gimbal, and rocket holder. The gimbal and rocket holder rotate around different axes of rotation. Each part is attached to each other with rods that can spin in their slot. To get to this point, I had to glue and screw in two wooden beams to a wooden base. Then, I measured the distance between the beams so that I could design and 3D print each of the main parts and the rods of the gyroscope. Afterwards, I glued each part together since I printed them in half for more precise prints. Once they were all printed, I connected everything with the rods and attached it to the wood. 

**Challenges:**
The first challenge I faced was screwing in the wooden supports onto the base. Since I didn't have power tools, using a screwdriver took longer than expected and I had to make sure I was screwing in the right place.

The main challenge I had was designing each 3D printed part with CAD. I have never used CAD before, so using it took a long time. I used Onshape to create different parts and then put them all into one assembly. I had to learn how to create different shapes, planes, and mates to make sure my gyroscope would fit and rotate how I would want. 

The next challenge I faced was testing different tolerances for my rods. I had to print many different rods with varying diameters so that I could get the right amount of tolerance between the hole and the rod. 

Once I had passed all of these challenges, the only thing left to do was to piece everything together. 

**Next Steps:**
I plan on adding a motor to the side of my gyroscope so that I can spin the gyroscope. I will attach a gear to the motor and it will spin the gear that is attached to one of my rods. After that, I plan on adding bluetooth connection to this motor so that I can control different speeds on a separate interface without a wired connection. After this, I will start thinking about different modifications.
  
# Starter Project Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/OiAZoEpLqxg?si=571pmQMK6GmbxzXV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Description:**
My starter project was the jitterbug. The project centered around a vibration motor, which allowed the robot to vibrate and move around. It also included two LEDS for lights, and a switch to toggle the power on and off. I spent most of my time soldering each component to the Jitterbug PCB, which improved my soldering skills.

**Challenges:**
The main challenge for me was soldering all of the components onto the Jitterbug PCB. Since some pins were placed very close to each other, I had to take my time soldering. I focused on trying not to connect the solder between each hole, so that it wouldn't short circuit. At the same time, I made sure to cover the entire hole, including the gold-plated border. 

**Next Step:**
With this soldering and robot building knowledge, I look forward to my main project. I hope to apply these skills to the best of my ability.


# Schematics 
![tinkercadimage1](motor.png)



# Arduino IDE Code (For the Motor)

```c++
#include <SoftwareSerial.h>

// HC-06 TX -> Digital Pin 10
// HC-06 RX -> Digital Pin 11
SoftwareSerial bluetooth(10, 11);

// Motor driver pins
const int EN = 5;
const int IN1 = 2;
const int IN2 = 3;

void setup() {

  // Start Serial Monitor
  Serial.begin(9600);

  // Start Bluetooth communication
  bluetooth.begin(9600);

  // Set motor pins as outputs
  pinMode(EN, OUTPUT);
  pinMode(IN1, OUTPUT);
  pinMode(IN2, OUTPUT);

}

void loop() {

  // Check if Bluetooth sent any data
  if (bluetooth.available() > 0) {

    // Read one character from Bluetooth
    char command = bluetooth.read();

    // Forward (Slow)
    if (command == 'F') {

      digitalWrite(IN1, HIGH);
      digitalWrite(IN2, LOW);

      analogWrite(EN, 165);

    }

    // Forward (Fast)
    if (command == 'G') {

      digitalWrite(IN1, HIGH);
      digitalWrite(IN2, LOW);

      analogWrite(EN, 210);

    }

    // Backward (Slow)
    if (command == 'B') {

      digitalWrite(IN1, LOW);
      digitalWrite(IN2, HIGH);

      analogWrite(EN, 165);

    }

    // Backward (Fast)
    if (command == 'H') {

      digitalWrite(IN1, LOW);
      digitalWrite(IN2, HIGH);

      analogWrite(EN, 210);

    }

    // Stop
    if (command == 'S') {

      digitalWrite(IN1, LOW);
      digitalWrite(IN2, LOW);

      analogWrite(EN, 0);

    }

  }

}
```

# Arduino IDE Code (For the Sensor)

```c++
#include <Adafruit_MPU6050.h>
#include <Adafruit_Sensor.h>
#include <Wire.h>
#include <SoftwareSerial.h>

// HC-05 TX -> D2, HC-05 RX -> D3
SoftwareSerial bluetooth(2, 3); 

Adafruit_MPU6050 mpu;

void setup() {
  Serial.begin(9600);
  bluetooth.begin(9600);

  if (!mpu.begin()) {
    Serial.println("Failed to find MPU6050 chip");
    while (1) {
      delay(10);
    }
  }

  mpu.setAccelerometerRange(MPU6050_RANGE_16_G);
  mpu.setGyroRange(MPU6050_RANGE_250_DEG);
  mpu.setFilterBandwidth(MPU6050_BAND_21_HZ);

  bluetooth.println("MPU6050 ready");
}

void loop() {
  sensors_event_t a, g, temp;
  mpu.getEvent(&a, &g, &temp);

  bluetooth.print("AccelX:");
  bluetooth.print(a.acceleration.x);
  bluetooth.print(", AccelY:");
  bluetooth.print(a.acceleration.y);
  bluetooth.print(", AccelZ:");
  bluetooth.print(a.acceleration.z);

  bluetooth.print(", GyroX:");
  bluetooth.print(g.gyro.x);
  bluetooth.print(", GyroY:");
  bluetooth.print(g.gyro.y);
  bluetooth.print(", GyroZ:");
  bluetooth.println(g.gyro.z);

  delay(100);
}
```

# Python Code (For the Interface)

```c++
import tkinter as tk
import serial

# Connect to HC-06 Bluetooth
bluetooth = serial.Serial("/dev/cu.HC-06", 9600)

# Colors
BLUE = "#0B3D91"
YELLOW = "#FFD100"

# Commands


def forward_slow():
    bluetooth.write(b'F')


def forward_fast():
    bluetooth.write(b'G')


def backward_slow():
    bluetooth.write(b'B')


def backward_fast():
    bluetooth.write(b'H')


def stop():
    bluetooth.write(b'S')


# Window
root = tk.Tk()
root.title("Gyroscope Control")
root.geometry("1920x1080")
root.configure(bg=BLUE)

# Title
title = tk.Label(
    root,
    text="Gyroscope Control",
    font=("Arial", 40, "bold"),
    bg=BLUE,
    fg=YELLOW
)
title.pack(pady=60)

# Frame
button_frame = tk.Frame(root, bg=BLUE)
button_frame.pack(expand=True)

# Button settings
button_font = ("Arial", 24, "bold")
button_width = 12
button_height = 5

# Buttons
tk.Button(button_frame, text="Forward\n(Fast)", command=forward_fast,
          font=button_font, width=button_width, height=button_height).grid(row=0, column=0, padx=20)

tk.Button(button_frame, text="Forward\n(Slow)", command=forward_slow,
          font=button_font, width=button_width, height=button_height).grid(row=0, column=1, padx=20)

tk.Button(button_frame, text="Stop", command=stop,
          font=button_font, width=button_width, height=button_height).grid(row=0, column=2, padx=20)

tk.Button(button_frame, text="Backward\n(Slow)", command=backward_slow,
          font=button_font, width=button_width, height=button_height).grid(row=0, column=3, padx=20)

tk.Button(button_frame, text="Backward\n(Fast)", command=backward_fast,
          font=button_font, width=button_width, height=button_height).grid(row=0, column=4, padx=20)

root.mainloop()

```


# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Uno R3 | Program Execution | $16.99 | <a href="https://a.co/d/03OlNw2A"> Link </a> |
| Arduino Nano | Program Execution | $15.99 | <a href="https://a.co/d/02QqXWet"> Link </a> |
| Motor Driver | Motor Control | $6.98 | <a href="https://a.co/d/0hf1RYcP"> Link </a> |
| DC Gear Motor | Rotational motion | $6.99 | <a href="https://a.co/d/03TCnzkl"> Link </a> |
| MPU-6050 | IMU Sensor | $6.99 | <a href="https://a.co/d/05ntPAIi"> Link </a> |
| 5x AA Batteries | Power Supply | $6.49 | <a href="https://a.co/d/0fOFyqsa"> Link </a> |
| 9V Battery | Power Supply | $6.49 | <a href="https://www.amazon.com/dp/B00O869KJE?_encoding=UTF8&psc=1&ref_=cm_sw_r_cp_ud_dp_DBBMX484PMC3C4MC11G4_1"> Link </a> |
| HC-06 Bluetooth Module | Bluetooth Connection | $9.99 | <a href="https://www.amazon.com/dp/B074J5WMH1?ref_=cm_sw_r_cp_ud_dp_GT2T5KTQEW4TFKFG29VG"> Link </a> |
| HC-05 Bluetooth Module | Bluetooth Connection | $9.99 | <a href="https://a.co/d/0eIP06gN"> Link </a> |
| Breadboard | Circuit Assembly | $6.99 | <a href="https://a.co/d/0feYFevcG"> Link </a> |
| L-Brackets & Screws | Holds Wooden Beams Upright | $6.99 | <a href="https://www.amazon.com/dp/B0BLBWZYSQ?ref_=cm_sw_r_cp_ud_dp_KGAC8ZXQFY4A97Z10FT4_1"> Link </a> |
| Plywood | Stability | $18.48 | <a href="https://www.amazon.com/dp/B0CYM54W1S?ref_=cm_sw_r_cp_ud_dp_M3J0GW1763MNSZHPC5SH"> Link </a> |
| Square Wooden Dowels | Vertical Supports| $13.99 | <a href="https://a.co/d/086giWlL"> Link </a> |
| PLA Filament | 3D Print Material | $13.99 | <a href="https://a.co/d/01n8owUR"> Link </a> |

<!---
# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->

