# GeminiFlight (forked from dRehmFlight)

Currently forked to use proper Git flow for development. Long term focus on developing serial control from a Raspberry Pi for extended autopilot ability in the software realm over the firmware realm.

## Overview on dRehmFlight

dRehmFlight is the flight controller for hobbyists, hackers, and non-coders interested in stabilizing their wacky and unique flying creations. The code and supporting documentation is built to bring someone up to speed on VTOL flight stabilization concepts as quickly and painlessly as possible. The code is written and presented in a way that is intuitive, easy to follow, and most importantly: all in one place. No more digging through countless folders and confusing classes just to add an 'if' statement for your custom drone application. This flight controller uses an Arduino-compatible microcontroller, so there is no confusing flashing or compiling process necessary. If you can use Arduino, you can start expanding the capabilites of this flight controller to your liking.

dRehmFlight has been used as a teaching tool for aircraft stabilization and flight control principles in universities and tech companies around the world. It is not meant to out-perform other flight controller packages on the market, or be used in a commercial sense. It is best suited for rapid prototyping or allowing a radio control hobbyist to get their feet wet in flight control code for their VTOL project. Much more information is included in the dRehmFlight VTOL Documentation .pdf.

This code is entirely free to use and will stay that way forever. We haven't made enough modifications yet to accept any donations but if you found this helpful for your own project, please donate to the OG of dRehmFlight and tell him I sent you: [Paypal Donation](https://www.paypal.me/NicholasRehm)


### Hardware Requirements
This flight controller is based off of the Teensy 4.0 microcontroller and MPU9250 9DOF IMU. The following components (available on Amazon) are required to complete the flight controller assembly:


**Teensy 4.0**: https://amzn.to/3oFG3QN

**Alternative Links**: [Sparkfun](https://www.sparkfun.com/products/15583), [Adafruit](https://www.adafruit.com/product/4323), [Electromaker](https://www.electromaker.io/shop/product/teensy-40?gclid=Cj0KCQjwxIOXBhCrARIsAL1QFCYcZsU4tRXVgeqfOOJyg_zPV2MXTeJM2QwJ6zafMTsCb6MjWthk7r8aAn6hEALw_wcB)

Due to supply chain issues, the Teensy 4.0 has been frequently out of stock throughout 2022. The Teensy 4.1 is generally in stock more often and is immediately compatible with the dRehmFlight pin mappings (plus you get extra bonus pins!): https://amzn.to/3c1OSSw


**GY-521 MPU6050 IMU**: https://amzn.to/3edF1Vn

These (and all Amazon links contained within the supporting documentation) are Amazon Affiliate links; by purchasing from these, I receive a small portion of the revenue at no cost to you. I appreciate any and all support!

### Software Requirments
Code is uploaded to the board using the Arduino IDE; download the latest version here: https://www.arduino.cc/en/main/software

To connect to the Teensy, you must also download and install the Teensyduino arduino add-on; download and instructions available here: https://www.pjrc.com/teensy/td_download.html


## Tutorial Videos
[Building the Flight Controller Hardware](https://www.youtube.com/watch?v=EBXBEB-Xv7w&)

[Setting Up Your Radio Connection](https://www.youtube.com/watch?v=Wdc1o6eSsMo)

[Mounting and Configuring the IMU](https://www.youtube.com/watch?v=pi4PiBFPt70)

[How the Flight Controller Code Works](https://www.youtube.com/watch?v=_n5GBudUf5Q&lc=UgwvXX18w7FtJH1ClLl4AaABAg)

[Building and Coding an RC F-35 VTOL](https://www.youtube.com/watch?v=RqdcZD0ZoUk)

## Flight Videos
dRehmflight has been successfully implemented on the following platforms:

**Autonomous Quadrotor:** https://www.youtube.com/watch?v=p8frNNYQNV4

**Quadrotor Biplane VTOL:** https://www.youtube.com/watch?v=rk4tUKM6bd0

**Dual Cyclocopter:** https://www.youtube.com/watch?v=JoVmejDsMrM&

**VTOL F-35 Tricopter:** https://www.youtube.com/watch?v=RqdcZD0ZoUk

**Model SpaceX Starhopper:** https://www.youtube.com/watch?v=VsyFejn40Ss

**Model SpaceX Starship:** https://www.youtube.com/watch?v=5lwH7xJnB4I

**Inverted Pendulum Drone Stabilization:** https://www.youtube.com/watch?v=XmYRQi48s-8

**Fixed Wing Ground Effect Vehicle:** https://www.youtube.com/watch?v=uaY2G5Kbj_g

**Spinning Tricopter VTOL:** https://www.youtube.com/watch?v=7JH1_ZKV7t4

**Model Joby EVTOL:** https://www.youtube.com/watch?v=Dd2N_lyO_SQ

**Model V-22 Osprey:** https://www.youtube.com/watch?v=2OGkYfOs9EU

**Tricopter Tailsitter:** https://www.youtube.com/watch?v=8MJNfkEBRMY

**Tail-less Albatross:** https://www.youtube.com/watch?v=1ifR_cvjpjk

**Bicopter VTOL:** https://www.youtube.com/watch?v=XPXN0QejqM0


I would love to see your flying creations and maybe feature them here as well. Please email me at NicholasRehmYT@gmail.com with any videos/pics of your project. -Nick Rehm


## Disclaimer
This code is a shared, open source flight controller for small micro aerial vehicles and is intended to be modified to suit your needs. It is NOT intended to be used on manned vehicles. I do not claim any responsibility for any damage or injury that may be inflicted as a result of the use of this code. Use and modify at your own risk. More specifically put:

THIS SOFTWARE IS PROVIDED BY THE CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
