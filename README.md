# Plotter_Investigation
![The thing itself](/images/portrait.jpg?raw=true)

Investigation materials for exploring, understanding, and designing a new interface for a mysterious hand-made xy plotter found in a surplus store.

Initial Breakdown:

  1. Device is precision xy plotter designed for manual and digital input.

  1. Positioning is accomplished using two DC control motors (TODO: specs). Documentation for these motors isn't available.

  2. Each motor is equipped with an integrated analog tachometer.
    1. Unsure if tachometer reading is being used anywhere. Would the reading be useful if encoder assumption is correct?
  
  3. Each motor has a set of 5 leads in addition to normal dc motor wiring. Assumption is that these leads are from some kind of encoder.
    1. Unsure if encoders are absolute or relative.
    
  4. The device has a digital input vector via a 50-pin D-connector.
  
    1. 25 pins in this connector are in use. 
    2. A set of 10 are labeled 'input' and a further set of 10 are labeled 'output'.
    3. Of the remaining 5 pins, one is a ground. The remaining 4 contain two tachometer leads and two drive voltage leads, all from the two motors.
 

    
