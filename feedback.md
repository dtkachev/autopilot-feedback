# Feedback

Tesla vehicles are the safest passenger cars on the road. Examples of Tesla vehicles saving lives are endless. The following is a list of observations from edge cases, compiled in order to help accelerate (1) Autopilot's (FSD) learning rate, transition to (2) autonomous hands-free driving and (3) sustainable future.

## Version: v10.2 2021.32.22 | 9e064485d2bf
- Missing right-hand road bend/turn, crossing double yellow, driving into
opposite direction traffic (WWD). 10 mph below speed limit. Head-on collision risk. Video: [fsd-feedback-missing-right-hand-bend-turn-into-head-on-traffic-20211030](https://drive.google.com/file/d/1zri_t-O--2HW6iV5zJDEdIgkm9PQMVmX/view?usp=sharing)
-

## Versions: 2021.12.25.7 | 30c3ea0e44d0; 2021.4.18.2 | 6c676ce09ea5
- Auto lane change unavailable and inconsistent engagement. Video: [fsd-feedback-auto-lane-change-unavailable-inconsistent-engagement-20210807](https://drive.google.com/file/d/1-ChJZ_Iwf7BCbOYVknxzOrsTPscOnjHL/view?usp=sharing)
- Maps navigation - north vs south - incorrect direction. Video:
[fsd-feedback-maps-navigation-inverse-heading-north-south-20210807](https://drive.google.com/file/d/1XGTeO4Gmc-CQGrlmv_9cyf7_VB_4sfwJ/view?usp=sharing)

## Version: 2021.4.18.2 | 6c676ce09ea5
- Winding road interventions due to road bounds. Video: [fsd-feedback-winding-road-interventions-road-bounds-20210801](https://drive.google.com/file/d/1ChIpC4O7NgUM2kqiz6o3fQJfRdbPeioF/view?usp=sharing )
- Disengagements and user interventions. Video: [fsd-feedback-disengagement-and-user-intervention-20210801](https://drive.google.com/file/d/1hQlAgi1z3SIGhqU9DkiUUTGUtXrHYUUH/view?usp=sharing)
- Unnecessary maneuvers. Video: [fsd-feedback-unnecessary-maneuvers-20210801](https://drive.google.com/file/d/1PMRsQK1EqL6UwpFkqpjMYT2rYJk4GkGT/view?usp=sharing)
- Unusual behavior and logic. Video: [fsd-feedback-unusual-behavior-and-logic-20210801](https://drive.google.com/file/d/1MGbkjtiL_dpuxUrtredd4x3w1_DjKX2l/view?usp=sharing)
- Stuck in the middle lane and unnecessary slow downs. Video: [fsd-feedback-stuck-in-middle-lane-slow-down-20210801](https://drive.google.com/file/d/19nzf_GNELlJEvtYL7yNBTdLMaIh3QKNn/view?usp=sharing)
- Stuck in the left lane. Video: [fsd-feedback-stuck-in-left-lane-20210801](https://drive.google.com/file/d/1FKu0knX925LQHg13uHSkmHtlmFRmB_7h/view?usp=sharing)

## Version 2021.4.18.2 6c676ce09ea5
- Missing speed limits [fsd-feedback-braking-and-speed-limits-20210730](https://drive.google.com/file/d/16wIeCw0b9fqogxZ7TNCWp0MSTm3QGueG/view?usp=sharing):
    - Nighttime speed limit sign above road
    - Toll road (75 mph) vs parallel road (55 mph) 
    - Speed limit sign to the right (40 mph)
- [fsd-feedback-lane-change-requests-20210730](https://drive.google.com/file/d/1Ge3YS49r4_VEjq5TCczcz1cs8w6I-ve-/view?usp=sharing)
- Maps and highway exit numbers are outdated [fsd-feedback-maps-navigation-20210730](https://drive.google.com/file/d/1Xgb-EoNtxQRsTa9cUJZH9kt9__C4-Ggt/view?usp=sharing)
- Media playback (sentry) UI buggy: focus point mispositioned, playback between different camera views out of sync. Video: [fsd-feedback-ui-media-playback-20210730](https://drive.google.com/file/d/1A2h1Py_aFTS5OsahY23Uss6gs1_wYVlr/view?usp=sharing)
- Roadside emergency vehicles. Video: [fsd-feedback-roadside-works-emergency-vehicles-20210731](https://drive.google.com/file/d/1tswVC465V-K-_K_4PZ8oYU9peMfagV7i/view?usp=sharing)
- Road surface water and pothole disengagements. Video: [fsd-feedback-road-surface-water-potholes-20210731](https://drive.google.com/file/d/143gyWGBVLDBfRa-PKh3xSxkGte9DoxBf/view?usp=sharing)

Commentary:

- Autopilot (NOA) turns off during extended turns. Highway speed. It follows the lane correctly and without visible triggers / apparent dangers appears to lose confidence in itself (not justified) and disengages. [Hard to find afterwards on video footage without knowing the exact timestamp of disengagement, which is not currently saved either on the video or in a separate SRT file, improving quality of feedback). Example: 07.26.2021 21:25 +/- 2 min local time. 

- FSD visualization of long-vehicles (trucks, buses, tractor trailers, caravans)  jumps around. Appears to have a gap in scene-coverage or in what is being visualized to the user. Example: 07.26.2021 16:28 +/- 2 min local time.
    - Suggestion: ask users to tag and correct in a playback mode when parked. Crowdsource image tagging and user feedback (via dedicated UI screen) to gather reasons (1) behind disengagements and (2) record button presses. 

- No evasive maneuvers for parked vehicles on the sides of the road. Particularly when the left (passing) lane is empty.
    - Example: 07.26.2021 13:30 +/- 2 min local time.
    - Example: 07.26.2021 11:49 +/- 2 min local time.

- No anticipatory slow down when going in the left lane and the vehicle in the right lane is signaling to start the overtaking maneuver. The vehicle has to slow down smoothly, not abruptly, and then continue overtaking in the fast lane.
    - Example: 07.26.2021 13:30 +/- 2 min local time.

- Autopilot engages too abruptly without apparent dangers in the lane. As soon as the user engages Autopilot, it makes an abrupt adjustment within the lane, which doesn’t feel comfortable for an average driver. This adjustment of the vehicle’s position within the lane can be smooth.
    - Example: 07.26.2021 14:35 +/- 2 min local time.
    - Status: resolved.

- Autopilot doesn’t always engage the speed control correctly after the driver releases the accelerator pedal, slowing down by ~5-7 mph before engaging and accelerating to set speed limit speed. Example: NOA speed limit set at 80 mph. Vehicle travels at 82 mph. Driver engages NOA and releases the accelerator pedal. The vehicle slows down to 74 mph and then engages and accelerates to a speed limit of 80 mph.
   - Example: 07.26.2021 12:12 +/- 2 min local time.

- Autopilot adjustments can be too abrupt/aggressive - in dry conditions the traction holds (though “scary” for the driver), but in wet and icy conditions such abrupt adjustments will likely lead to loss of traction, spin and accidents.
    - Example: 07.26.2021 11:50 +/- 2 min local time.

- FSD doesn’t switch into the right lane when the car behind is approaching at a high rate of speed and/or following too closely in the left lane with space available in the right lane (leave left-lane open for passing law not enforced)
    - Example: 07.26.2021 12:03 +/- 2 min local time.
    - Example: 07.26.2021 11:33 +/- 2 min local time.

- Autopilot not currently comfortable (at current speed limit) for winding hill roads and country roads with shadows from trees (one lane in each direction) - appears to prioritize (1) driving at speed limit, which might be at the edge of friction of current road conditions at that point time and (2) driving to close to outside edge of the road marking line, where there is typically sand and dirt, which at speed limit might cause loss of traction.

- False positive large road objects - Autopilot wasn’t enabled at the time, but in the situation where a large flying object (plastic tarps, clothes, falling debris from other cars) is detected there is likelihood to lead to a phantom braking event. There are situations where hitting the object is unavoidable and is the best course of action, and other situations where safely avoiding the object is possible.


# Feature suggestions
- Bug i18n incorrect spacing padding cyrillic fonts. Status: resolved.
- Enable audible notifications for lane change requests.
- Show side camera for lane change maneuvers. Model 3 mirrors have dead zones.
- Provide supercharger contact details via qr code for driver reports / user feedback url. Missing on many superchargers in US.
- Add search bar to contacts page UI.

