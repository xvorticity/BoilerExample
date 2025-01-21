# Project for NI CLD Example Exam

# Improvements

Should come up with a better way of passing control references to the VIs handling the user action.

Create a better datalogger. Possibly a separate queue that every VI would have access to.

# Issues

Fuel Control Valve Position control causes issues when changing the value. Normal operation is between 10 and 75%. Any other value will shutdown the boiler operation. There is an issue when using the knob to go from 0 to anything above 10; the event is triggered on every increment of the dial. Temporary fix was to put the digital display.
