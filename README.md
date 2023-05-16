# led_matrices
Code for host PC to communicate with the microcontroller SCORPIO to control LED matrices
Will also be the basic firmware for setting up a ROS node (led_matrices_ros)


Output Messages: Sends messages to the SCORPIO microcontroller to produce different types of visual stimuli for Drosophila flight behavior
- "optomotor"
- "stripe"
- "sun"

Receiving Messages: Recieves messages from the SCORPIO microcontroller to check communication between the host PC and microcontroller and collects visual stimuli data
- "optomotor": Direction of movement, and when a directional change occurs
- "stripe": position of stripe stimulus
- "sun": position of sun stimulus
