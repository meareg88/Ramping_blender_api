#Gesture ramping experiment#
Experiment to see the blending in and out effects by changing the values of 'ramp in' and 'ramp out' values and also try it out with various gestures provided.
The default values set for gesture ramping are:
`ramp in` :1
`rampout` :1

```
rostopic pub --once /blender_api/set_gesture blender_api_msgs/SetGesture '{name: yawn-1, repeat: 1, speed: 0.5, magnitude: 1, rampin: 0.2, rampout: 0.8, start: 1, duration: 1, priority: 1}'
```

```
rostopic pub --once /blender_api/set_gesture blender_api_msgs/SetGesture '{name: yawn-1, repeat: 1, speed: 0.5, magnitude: 1, rampin: 0.5, rampout: 0.5, start: 1, duration: 1, priority: 1}'
```
