# Feedback

Tesla vehicles are the safest passenger cars on the road. Examples of Tesla vehicles saving lives are endless. The following is a list of observations from edge cases, compiled in order to help accelerate (1) Autopilot's (FSD) learning rate, transition to (2) autonomous hands-free driving and (3) sustainable future.
## Version: FSD Beta v10.5 | 2021.36.8.8 |  3dea54806bfc
- Didn't complete the turn necessary to avoid the curb. Without user intervention most likely would have jumped the curb. That curb had clearly seen prior jumpers missing the turn in similar fashion.
Video: [fsd-b-feedback-didnt-complete-the-turn-to-avoid-jumping-the-curb](https://drive.google.com/file/d/1LO8dtp-kdlNpkjwNN8EmuJCtxoO6wwdz/view?usp=sharing)
- Shifts suddenly to the left into the striped zone. Misreads the point of starting left turn maneuver. User intervention performs lane correction back into the leftmost lane. Safety Score logic shall ignore 1-5 sec of driver's corrective actions following disengagement - otherwise negative feedback loop.
Video: [fsd-b-feedback-shifts-left-into-striped-zone-misreads-left-turn-starting-point](https://drive.google.com/file/d/1v9oqsIoSY8FKSLyk5Fv-uI4HmlBPkpwh/view?usp=sharing)
- Incorrectly navigates left blind turn of the road by swerving into the opposing traffic lane. Head-on collision risk. Ultimately corrected the path and returned back into the right lane.
Video: [fsd-b-feedback-left-blind-turn-in-the-opposing-lane](https://drive.google.com/file/d/1sULEziErFfZp12Xr6qnjhk25_VEyuR8Q/view?usp=sharing)
- Attempts to perform a full stop (aggressive braking) after proceeding through this intersection on a yellow light. Misunderstands the spatial context of the red light at the end of this intersection, since it made a decision to proceed on yellow light. Rear-end collision risk. No reason to stop after crossing the intersection.
Video: [fsd-b-feedback-full-stop-at-the-end-of-intersection-crossed-on-yellow](https://drive.google.com/file/d/1TPpNs0vZIwvu2Bi6u1uTBfXcMCxXjJsI/view?usp=sharing)
- Misses braking point for left turn. Proceeded further than comfortable into the opposing traffic lane at the median. Head-on collision risk. Should have stopped sooner even if after the line, or conservatively at the line, awaiting the right moment for the intersection to clear.
Video: [fsd-b-feedback-misses-left-turn-braking-point-into-opposing-lane](https://drive.google.com/file/d/11tPS517yHAS8_-n58P3KDPvSFZ5MnmNo/view?usp=sharing)
- [1] Didn't adjust the route/path for parked vehicle in advance for a human driver to be "comfortable" to avoid disengagement. [2] Incorrectly performed "Emergency lane correction" back closer towards the high-risk zone of the parked truck after driver disengaged FSD and adjusted the route to account for the parked truck. Safety mechanism counteracted proper user correction.
Video: [fsd-b-feedback-1-didnt-adjust-to-avoid-parked-vehicle-2-incorrectly-performed-emergency-lane-correction-into-parked-vehicle](https://drive.google.com/file/d/11Cicwl1Q4pURigGrIKXdymH_BGU0VIFp/view?usp=sharing)
- Misreads end of lane. Proceeds forward in the striped zone of opposing traffic (yellow crosshatch lines). Head-on-collision risk. User intervention performs lane change to the right. Shall anticipate the end of the turning lane and switch in advance.
Video: [fsd-b-feedback-misreads-end-of-lane-proceeds-in-opposing-traffic-crosshatch-lines-head-on-collision-risk](https://drive.google.com/file/d/1_k7YXTQX_3obgDeqdi1FTGk2GgdMpoNR/view?usp=sharing)
- Misreads lane split. Attempts off-road lane-change into the right shoulder.
User intervention stopped the maneuver.
Video: [fsd-b-feedback-misreads-lane-split-attempts-off-road-lane-change-into-right-shoulder-dangerous](https://drive.google.com/file/d/1oIHE-woKOUIFLnoajdqlw661SWkANyZc/view?usp=sharing)
- Misses right lane change to the off-ramp. Most likely got confused by the behavior of the vehicle in front.
Video: [fsd-b-feedback-misses-right-lane-change-to-off-ramp-confused-by-front-vehicle](https://drive.google.com/file/d/1_Jt4FNUJSwaCQKLUt9IU93i57OVWGRlU/view?usp=sharing)
- Performs left lane change maneuver late. There was space and time to perform lane change ahead of time.
Video: [fsd-b-feedback-late-left-lane-change-maneuver](https://drive.google.com/file/d/1lS_3RFYv1zNoK9FDwI2FqqD-uX-i4smU/view?usp=sharing)
- Missed lane change maneuver. Got stuck in the off ramp lane. User's intervention required for the left lane change.
Video: [fsd-b-feedback-missed-left-lane-change-got-stuck-in-off-ramp-lane](https://drive.google.com/file/d/1-NtYQwnu9Lrcq07e39kzNy-kMKl8nhft/view?usp=sharing)
- Gets stuck in between two lanes. Enough space to proceed on the left. User intervention proceeds the vehicle forward in the left turning lane.
Video: [fsd-b-feedback-stuck-between-two-lanes-enough-space-to-proceed](https://drive.google.com/file/d/1oWwwQbsiA1dVWTEGaGN3dorOjlfUQZ-8/view?usp=sharing)
- Stuck in the left lane. No reason to stay in the passing lane. Right lane open.
Shall change and proceed in the right lane.
Video: [fsd-b-feedback-stuck-left-lane-right-lane-open](https://drive.google.com/file/d/1zF0z_xU_p8sxJSL0QzRLvYwl9-7O0GMb/view?usp=sharing)
- Stuck in the left lane/side of the unmarked two lanes. Prevents vehicles from passing.
Video: [fsd-b-feedback-stuck-left-lane-of-unmarked-two-lane](https://drive.google.com/file/d/1gstcsXduRySWjir3pkav1rJ64cBgK3UP/view?usp=sharing)
- Constantly tries to change into the left lane every 7-10 seconds despite user's "Cancel" input even though current lane is wide open and there are multiple vehicles in the left lane. Not learning from user input - multiple Cancel taps.
Video: [fsd-b-feedback-tries-to-change-into-left-passing-late-despite-user-cancel-taps](https://drive.google.com/file/d/1OkNPlcw-0aOBhxIe8D5fuyTncqvqZUfj/view?usp=sharing)
- Autosteer unavailable: initially glass condensation and/or fog, and then direct sun. If a user can see/drive/operate, a machine shall perform the same operation at the same level or better than a human. Potential solutions applicable for rain, wet and high humidity environments: localized glass heating (cheap) and/or pneumatic air puff/blow on the glass (expensive/complicated within current camera position). 
Video: [fsd-b-feedback-autosteer-unavailable-humidity-condensation-sunlight](https://drive.google.com/file/d/1UZ--i8y2XXe1_acXIsZhtE3ZAvhXhVA0/view?usp=sharing)
- Regular disengagements -> autosteer unavailable: direct sunlight. If a user can see/drive/operate (based on camera image), a machine shall perform the same operation at the same level or better than a human. Additional improvement for reflection cases: use of polarized glass?
Video: [fsd-b-feedback-disengagements-autosteer-unavailable-direct-sunlight](https://drive.google.com/file/d/16nfbN3qtueBooLFjFve228AxsQA3Digc/view?usp=sharing)
- Safety score logic currently penalizes driver for the maneuvers performed right after FSD disengagement, even though they are performed for safety reasons. Positive feedback loop for using FSD breaks down as Safety Score penalizes a driver for exploring edge cases and giving more time for an FSD to attempt to recover before intervening. Suggestion: maneuvers within 1-5 seconds after FSD disengagement shall not lower Safety Score - though such blunt logic can be abused by drivers.
- No slow down for bumps and dips. Doesn't recognize "DIP" sign.
Video: [fsd-b-feedback-bumps-dips-no-slow-down](https://drive.google.com/file/d/1zN3PAoWlKs2NfVfwnIzCbIPcQdAEsWYF/view?usp=sharing)
- No path adjustment for potholes. Doesn't allow driver input without disengagement to account for potholes / obstacles.
## Version: v10.2 | 2021.32.22 | 9e064485d2bf
- Missing right-hand road bend/turn, crossing double yellow, driving into
opposite direction traffic (WWD). 10 mph below speed limit. Head-on collision risk. Video: [fsd-feedback-missing-right-hand-bend-turn-into-head-on-traffic-20211030](https://drive.google.com/file/d/1zri_t-O--2HW6iV5zJDEdIgkm9PQMVmX/view?usp=sharing)
- Aggressive braking due to phantom object overhead. Video: [fsd-feedback-aggressive-braking-due-phantom-overhead-object-20211030](https://drive.google.com/file/d/1CqrM2tUVQ4d4WU_Mgo8-wF1PwEZVWubj/view?usp=sharing)
- Fails to follow user input to change into the left lane (most likely due to "Autosteer unavailable") to give space to roadworks vehicle. Driver has to disengage Autopilot to go into left lane. Video: [fsd-feedback-fails-to-change-into-left-lane-user-input-due-to-roadworks-20211030](https://drive.google.com/file/d/1zl-mkkw13drnrQggz_-wAWzvX6nbBwuP/view?usp=sharing)
- Autopilot cancels lane-change maneuver into the middle lane, mistakenly        
thinking semi is in the middle lane, whereas semi was in the rightmost (3) lane. Video: [fsd-feedback-lane-change-cancelled-due-phantom-semi-from-third-lane-20211030](https://drive.google.com/file/d/1glnUXSi4xTUQtIkEU039a3-E3964nAsN/view?usp=sharing)
- Fails to recognize deer starting to walk into the lane. No slow down. Left adjustment was done by the driver. Video: [fsd-feedback-fails-to-recognize-deer-no-slow-down-20211030](https://drive.google.com/file/d/1o_ETlE72CnSY0zX0Ngtv7smtcCVxqndE/view?usp=sharing)
- Right hand lane merge lead to sinusoidal swerving back and forward. Too many adjustments for comfort. Video: [fsd-feedback-right-lane-merge-sinusoidal-swerving-20211030](https://drive.google.com/file/d/1CBD9WLeziow0gWurh927hvupe31rUYrY/view?usp=sharing)
- Intermittent hesitant unnecessary braking (0.5-1 sec) near flashing sign.
Appears to misread the flashing sign for the intersection before deciding to proceed. Video: [fsd-feedback-Intermittent-unnecessary-braking-flashing-sign-no-intersection-20211030](https://drive.google.com/file/d/1rZr9uKeCOARSs3C87yAmvKcn3VFH9lDb/view?usp=sharing)
- While safe, doesn't appear to recognize a vehicle crossing the road ahead in advance -
too close to be comfortable for an average driver. Video: [fsd-feedback-doesnt-recognize-crossing-vehile-not-comfortable-20211030](https://drive.google.com/file/d/1pr35pLfevbuPgPikkH51IsXvEgj733T4/view?usp=sharing)
- Doesn't anticipate semi's maneuver into passing lane in advance, starts braking aggressively too late to be considered comfortable or in control for the driver not to intervene. When user intervenes, autopilot disables and penalizes the safety score with aggressive braking / close-following. Video: [fsd-feedback-no-planning-ahead-misses-semis-maneuver-20211030](https://drive.google.com/file/d/1SfOx2UpdYb-khpRQXT2BWIFu_b28PQcq/view?usp=sharing)

## Versions: v10.2 | 2021.12.25.7 | 30c3ea0e44d0; 2021.4.18.2 | 6c676ce09ea5
- Auto lane change unavailable and inconsistent engagement. Video: [fsd-feedback-auto-lane-change-unavailable-inconsistent-engagement-20210807](https://drive.google.com/file/d/1-ChJZ_Iwf7BCbOYVknxzOrsTPscOnjHL/view?usp=sharing)
- Maps navigation - north vs south - incorrect direction. Video:
[fsd-feedback-maps-navigation-inverse-heading-north-south-20210807](https://drive.google.com/file/d/1XGTeO4Gmc-CQGrlmv_9cyf7_VB_4sfwJ/view?usp=sharing)

## Version: v10.2 | 2021.4.18.2 | 6c676ce09ea5
- Winding road interventions due to road bounds. Video: [fsd-feedback-winding-road-interventions-road-bounds-20210801](https://drive.google.com/file/d/1ChIpC4O7NgUM2kqiz6o3fQJfRdbPeioF/view?usp=sharing )
- Disengagements and user interventions. Video: [fsd-feedback-disengagement-and-user-intervention-20210801](https://drive.google.com/file/d/1hQlAgi1z3SIGhqU9DkiUUTGUtXrHYUUH/view?usp=sharing)
- Unnecessary maneuvers. Video: [fsd-feedback-unnecessary-maneuvers-20210801](https://drive.google.com/file/d/1PMRsQK1EqL6UwpFkqpjMYT2rYJk4GkGT/view?usp=sharing)
- Unusual behavior and logic. Video: [fsd-feedback-unusual-behavior-and-logic-20210801](https://drive.google.com/file/d/1MGbkjtiL_dpuxUrtredd4x3w1_DjKX2l/view?usp=sharing)
- Stuck in the middle lane and unnecessary slow downs. Video: [fsd-feedback-stuck-in-middle-lane-slow-down-20210801](https://drive.google.com/file/d/19nzf_GNELlJEvtYL7yNBTdLMaIh3QKNn/view?usp=sharing)
- Stuck in the left lane. Video: [fsd-feedback-stuck-in-left-lane-20210801](https://drive.google.com/file/d/1FKu0knX925LQHg13uHSkmHtlmFRmB_7h/view?usp=sharing)

## Version: v10.2 |  2021.4.18.2 6c676ce09ea5
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


