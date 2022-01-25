# Feedback:

Tesla vehicles are the safest passenger cars on the road. Examples of Tesla vehicles saving lives are endless. The following is a list of observations from edge cases, compiled in order to help accelerate (1) Autopilot's (FSD) learning rate, transition to (2) autonomous hands-free driving and (3) sustainable future.
## Version: FSD Beta v10.9 | 2021.44.30.5 | 81562c9c7b28
- Alerts, speed oscillations and phantom brake checks at oncoming traffic from the left lane both during day-time and night-time (fairly violent and unexpected). Feels like a regression versus 10.8 with higher occurrences and a bit edgy while driving in the left passing lane. Video: [fsd-b-feedback-alerts-speed-oscillations-brake-checks-at-oncoming-traffic-from-left-lane-both-day-time-and-night-time](https://drive.google.com/file/d/1KLPiGU84y90JqrR4DNtehJs2a12QZa8Q/view?usp=sharing)
- Unmarked two-lane: cutting corners through the opposing traffic lane. Randomly shifting to the left side of the road. Got significantly better relative to 10.5. Video: [fsd-b-feedback-unmarked-two-lane-cutting-corners-through-opposing-traffic-lane](https://drive.google.com/file/d/1fFCa5Ts5HdgCqGA9gm0eiL7TjU_4xGj0/view?usp=sharing)
- Attempted to perform lane change into the center lane (left turn lane only) 12 times, which should never be used for passing. Video: [fsd-b-feedback-attempted-to-perform-lane-change-into-the-center-lane-left-turn-lane-only-](https://drive.google.com/file/d/1tZC0NGG6opRmqkD1g-YcOGF-Mr3Z8mhz/view?usp=sharing)
- Not appropriate speed alert and automated FSD disengagement. Acceleration and speed were necessary to safely enter the express lane with another vehicle close.  Video: [fsd-b-feedback-inappropriate-disengagement-due-to-speed-acceleration-during-express-lane-merge-vehicle-behind](https://drive.google.com/file/d/1jWv0PtoOHqz3xS7dgBECX3hF9YdSSZ35/view?usp=sharing)
- Unnecessary take control alerts. Video: [fsd-b-feedback-unnecessary-take-control-alert](https://drive.google.com/file/d/1QTxoELkIsQrQvRmdxuiuUPirA1EewymE/view?usp=sharing)
- Direct sunlight disengagements. Video: [fsd-b-feedback-direct-sunlight-disengagements](https://drive.google.com/file/d/1nr8HHzY_6eCIS8352qpZ7WQBSz9EYkTf/view?usp=sharing)
- Going too fast for the turn and surface - close to the edge of friction. Video: [fsd-b-feedback-going-too-fast-for-the-turn-and-surface-close-to-the-edge-of-friction](https://drive.google.com/file/d/15zND8gtVR0zrQtmqKvyXnps3aWx7XyAU/view?usp=sharing)


- Attempted to get too close to a school bus (with flashing red lights) by changing into the right lane to pass the front vehicle in the left lane, which was waiting for the bus to complete its stop. Didn't have footage saved unfortunately, but was reported via Feedback button.
- Attempted left lane change into moving semi. Truck had to perform an evasive maneuver. Misread velocity difference. Dangerous to leave little space for semi - braking can jacknife their rig. Video: [fsd-b-feedback-attempted-left-lane-change-into-moving-semi-truck-had-to-perform-evasivemaneuver](https://drive.google.com/file/d/1MThFma1s_48d6vhMsiGu-faoUfz2-lg3/view?usp=sharing)
- Missed speed limits (going up (70 mph) twice and going down (to 60 or 55 mph - not shown) at nighttime. Video: [fsd-b-feedback-missed-speed-limits-going-up-70-mph-twice-and-going-down-to-60-or-55-mph](https://drive.google.com/file/d/1mMV2ulCyjDjQDUDTzkXfFh5P-GGsI4em/view?usp=sharing)
- Attempted to cross double yellow at the end of the left turn. Lane entrance trajectory logic. Not smooth. Video: [fsd-b-feedback-attempted-to-cross-double-yellow-at-the-end-of-the-left-turn-lane-entrance-trajectory-logic-not-smooth](https://drive.google.com/file/d/1R7asoGWNpFDPpbdLv1qgFYM0xPS0aGhM/view?usp=sharing)
- Speed oscillations (2-7 mph) with braking and audible alerts at night. Nighttime hesitation when detects oncoming traffic lights. Aggressive braking for an offroad (off asphalt) vehicle.[fsd-b-feedback-speed-oscillations-2-7-mph-with-braking-and-audible-alerts-at-night](https://drive.google.com/file/d/1fgadw9jdg2fHpepMW7cZOpdf9CPw1iFE/view?usp=sharing)
- Notification "FSD might be degraded" at nighttime. Might be glare, reflections, contrast, etc. Not hardware related - on lit highway or next morning no concerns without any cleaning. Should show which camera to clean manually - not actionable. Video: [fsd-b-feedback-Notification-fsd-might-be-degraded-at-nighttime-might-be-glare-reflections-contrast](https://drive.google.com/file/d/1DKndn6OIiz9W6U94NDeYy-jHg3vbB-nB/view?usp=sharing)
- Delayed speed limit change to 35 mph. Dark and narrow road required more rapid deceleration. Video: [fsd-b-feedback-delayed-speed-limit-change-to-35-mph-on-dark-and-narrow-road](https://drive.google.com/file/d/1WvuyhbjdPc3pxP26ntzdnXCgCOTec0fm/view?usp=sharing)
- Crossed double white during left lane change. Not necessary. Too aggressive - the situation didn't justify such a move. Video: [fsd-b-feedback-crossed-double-white-during-left-lange-change-not-necessary](https://drive.google.com/file/d/1vn9iOqldQGqobSPbeFnSXS27q8B3d3CG/view?usp=sharing)
- Failed to recognize digital Reduce Speed 45 mph sign. Attempted to perform right lane change into a closed lane with construction cones. Didn't plan ahead far enough even though lane closure cones were visible. Video: [fsd-b-feedback-failed-to-recognize-digital-reduce-speed-45-mph-sign-attempted-to-perform-right-lane-change-into-closed-lane-with-construction-cones](https://drive.google.com/file/d/1QJzQeIm1NTK-xBDXVSJJmv44v7jjnBBx/view?usp=sharing)
- Phantom braking for a non-applicable stop sign at road fork of a merging road. Video: [fsd-b-feedback-phantom-braking-for-non-applicable-stop-sign-2](https://drive.google.com/file/d/1skOz7vyDpu1w9_Pma3B_ilxTCNrn7xX3/view?usp=sharing)
- Phantom braking in the right lane (40 to 26 mph). Reason not clear. Video: [fsd-b-feedback-phantom-braking-in-the-right-lane-reason-not-clear](https://drive.google.com/file/d/1Ryw5vgKUYvU-gBLcmJiXHCG7ydKRbGSz/view?usp=sharing)
- Right turn path is not smooth. Not in the middle of the lane. Video: [fsd-b-feedback-right-turn-path-not-smooth-not-in-the-middle-of-the-lane](https://drive.google.com/file/d/1I_gMjwk7yBOcbBC-QW9fCBSfnytpViOO/view?usp=sharing)
- Attempted to pass a vehicle in front on the left while in the merge lane performing a right turn. Can be dangerous by blocking the view of the front vehicle during the merge. Video: [fsd-b-feedback-attempted-to-pass-vehicle-in-front-on-the-left-while-in-the-merge-lane-performing-right-turn](https://drive.google.com/file/d/12xjb4KH1gaJrchxUnJZ6JAZP4ljGdelX/view?usp=sharing)
- Shifts to the left into the striped zone. Misreads the point of starting the left turn maneuver. User intervention performs lane correction back to the right into the leftmost lane. Video: [fsd-b-feedback-shifts-left-into-striped-zone-misreads-left-turn-starting-point-2](https://drive.google.com/file/d/18sdvkxhwKKDDboP50oMozaiQLg-nmr1u/view?usp=sharing)
- Got squeezed at the end of the left lane. Failed to recognize lane closure construction cones ahead. Requires further ahead planning. Video: [fsd-b-feedback-got-squeezed-at-the-end-of-the-lane-failed-to-recognize-lane-closure-construction-cones-ahead](https://drive.google.com/file/d/12H_UJC3kV6lPV7T-JEv77UzLQ9HLa7Nj/view?usp=sharing)
- Right lane change request into a vehicle. Timing of the request is incorrect. To avoid confusion shall there be two states/colors: plan ahead = intent (light gray) and request to act (current blue)? Video: [fsd-b-feedback-right-lane-change-request-into-a-vehicle-timing-of-the-request-is-incorrect](https://drive.google.com/file/d/1jp8ibQeSrioci6mztsF5bTcf9RBbr-JQ/view?usp=sharing)
- Left lane affinity. No reason to move out of the right lane. Video: [fsd-b-feedback-left-lane-affinity-no-reason-to-move-out-of-the-right-lane](https://drive.google.com/file/d/1AoupAm5obJ-k4xu3K0L_YAEy6eKipUS7/view?usp=sharing)
- Emergency vehicles not visualized correctly.  Video: [fsd-b-feedback-emergency-vehicles-not-visualized-correctly](https://drive.google.com/file/d/15LUOyUMfVUizHk5vbZssB0a__WWNGFgS/view?usp=sharing)

General comments:
- Deceleration curve adjustment is noticeable - particularly before lights. Getting to the point of being smoother than a professional driver. Not as smooth when another vehicle is in front, nevertheless noticeable improvement.

Non FSD related feature suggestions:
- Sentry mode - record Cabin camera footage (in the event of break ins, thefts, attacks, etc)
- Sentry - Live Camera view: Add Cabin camera view 
- Sentry - Walkie Talkie mode with Cabin camera view - let the driver talk to passengers remaining inside the vehicle while the driver is away (two-way only). Similar functionality to Boombox Pedestrian Warning Speaker, but inside the vehicle.
- Caraoke - add Cabin camera video integration: record karaoke session and let user's save their performance to USB, send url link to the video file to an external device, submit to social (Tik Tok)
## Version: FSD Beta v10.8.1 | 2021.44.30.5 | 81562c9c7b28
It is getting harder and harder to find obvious weak spots - the confidence of the FSD has improved quite a bit from 10.5.

- Route planner states to stay in the current lane (going left) FSD continues going right. Mismatch between route planner and action. Video: [fsd-b-feedback-mismatch-betweeen-route-planner-and-fsd-action](https://drive.google.com/file/d/1nEoWRWvO8xU1__CawN3hj4Q492qa7JlO/view?usp=sharing)
- Incorrect visualization of red arrow lights as green lights. Divergence between correct perception/resulting action and visualization to the user (green light). Video: [fsd-b-feedback-incorrect-visualization-red-arrow-as-green-lights](https://drive.google.com/file/d/1pGUAq2o7M1cYSrkFcJ8TwvOpA1wZ0V-e/view?usp=sharing)
- Not enough advance planning / traffic conditions to plan earlier lane change/merge. Didn't recognize the need to perform lane change sooner into the traffic lane, ended up cutting into busy lane with queue.
Video: [fsd-b-feedback-didnt-perform-lane-change-soon-enough-into-the-tail-of-traffic-lane](https://drive.google.com/file/d/1rgfpTWeSBpaMBwXl5UEIpPeR-dOuzJsv/view?usp=sharing)
- Fails to recognize 25 mph speed limit. Maintains a 30 mph speed limit in this zone. Multiple misses. Video: [fsd-b-feedback-fails-to-recognize-25-mph-speed-limit](https://drive.google.com/file/d/13TgGW-STqk1353sWu6F47iCFxrEKv_8Z/view?usp=sharing)
- Fails to recognize express lanes and increase the speed limit until the first speed limit sign on the left. Drivers behind are not happy.  Video: [fsd-b-feedback-fails-to-recognize-express-lane-and-increase-speed-limit-until-first-speed-limit-sign](https://drive.google.com/file/d/1TmSH-Q4nBw8hoZD_9A13XkXsmFkYDqrj/view?usp=sharing)
- Enters the closed lane of the Toll booth gate. Vehicles ahead can be leveraged for initial guidance. Should be more proactive, adjusting in advance. Video: [fsd-b-feedback-enters-the-closed-lane-of-the-toll-booth-gate](https://drive.google.com/file/d/1Wyl02cDc2nYZP8HFcqKY9AbIDuWJqWMU/view?usp=sharing)
- Zigzaging (swerving back and forward) while performing lane change to the left. Video: [fsd-b-feedback-zigzag-swerving-while-performing-lane-change](https://drive.google.com/file/d/196pA1bZ-ea9ibnLwZp4Pnaog7J1-bEMP/view?usp=sharing)
[fsd-b-feedback-zigzag-swerving-while-performing-lane-change-1](https://drive.google.com/file/d/1uaqDnsplXwVupPu_oC8R0Q0udK-GrQ57/view?usp=sharing)
- Inclement weather - shows FSD not available, yet engages Autopilot (which has no distinction for an average driver). Assume it happens due to two stacks: FSD not available (when it rains), yet Autopilot is engaging on the same road. Messaging has to be clearer. Happy to test FSD in inclement weather as well - without inclement weather it is happy path testing. Video: [fsd-b-feedback-inclement-weather-fsd-autosteer-unavailable-yet-autopilot-engages](https://drive.google.com/file/d/1MnIiKz1Wcs1PCg_-tt2piI6GlRJEY7TI/view?usp=sharing)
- Inclement weather: shows Autosteer temporary unavailable and/or gets stuck in the current lane, until disengagement and reengagement. Not clear why. Video: [fsd-b-feedback-stuck-lane-change-request-autosteer-temporary-unavailable](https://drive.google.com/file/d/187tAHaeEEI2sU0OPzuDxOO1s9Uz6AG-x/view?usp=sharing)
- Slow and hesitant to respond to manual speed limit reduction.  Video: [fsd-b-feedback-no-response-no-manual-speed-limit-reduction](https://drive.google.com/file/d/1hTB5ZMsZ0HzxAu5Y-hKiui9kCWyzNiRH/view?usp=sharing)
- Doesn't respond to following distance input adjustments. No factual difference (either distance or time separation) between value 2 and 7. Video: [fsd-b-feedback-no-response-to-follow-distance-input-adjustments](https://drive.google.com/file/d/1sx5UeRaBYulUpm_a5QS9gv3rAbYBQlop/view?usp=sharing)
- Express lane - velocity oscillations and phantom braking at camera booths / overheads. Video: [fsd-b-feedback-express-lane-velocity-oscillations-phantom-braking](https://drive.google.com/file/d/1kE_6vmK9qEj34f-7MBbNEt7Ol2MNXE18/view?usp=sharing)
- Coming in too fast into the right hand turn. Crossing into head-on traffic. Collision risk. Video: [fsd-b-feedback-coming-too-fast-into-right-hand-turn-crossing-into-head-on-traffic-collision-risk](https://drive.google.com/file/d/1l7kge4QqmZRkULTbxVVnhWQc-QSPgY78/view?usp=sharing)
- Didn't do a full stop at the Stop sign with "All Way" addendum. Video: [fsd-b-feedback-no-stop-at-all-way-stop-sign-lane](https://drive.google.com/file/d/1cMw4gGvid4nywwOT9DxMVoTz7ToVrt7U/view?usp=sharing)
- Wheel turn for right hand turn without user notification. Not comfortable. Video: [fsd-b-feedback-wheel-turning-without-user-notification-uncomfortable](https://drive.google.com/file/d/1UnvH5L6wOVf3beVKwqyEvfkRRlJI-Msd/view?usp=sharing)
- Stops in between two lanes on top of broken white line marking ahead of stop sign. Video: [fsd-b-feedback-stops-in-between-two-lanes-of-broken-white-line-marking-ahead-of-stop-sign](https://drive.google.com/file/d/1VR44OAys-PBPBsM-mtIQYAKSwS6oPmuG/view?usp=sharing)
- Left passing lane affinity - multiple attempts. Right lane is empty - logical to stay in the current lane, no reason to change into the left passing lane. Video: [fsd-b-feedback-left-passing-lane-affinity-right-lane-empty-multiple-attempts](https://drive.google.com/file/d/1oB77Vvctw1Tfut6Ljxhfy29V3VRys7_f/view?usp=sharing)
- Didn't perform a smooth right side pass. Performed full stop, though space was available on the right to pass the truck. Video: [fsd-b-feedback-didnt-perform-smooth-right-side-pass-decided-to-brake-instead-of-passing-in-available-space](https://drive.google.com/file/d/1w3EPleyhbzfWCwgdLPNhZ7cVhzx593uU/view?usp=sharing)
- Stuck lane change notification without directional arrow. Video: 	[fsd-b-feedback-stuck-lane-change-notification-without-directional-arrow](https://drive.google.com/file/d/1vznzBQW9VheCBX0QoTd-yI3scldsMHO1/view?usp=sharing)
- Unnecessary alert to brake through the intersection with foot down on accelerator pedal confirming no slow down at intersection. No reason for brake alert. Video: [fsd-b-feedback-unnecessary-brake-alert-at-intersection](https://drive.google.com/file/d/17IlbUQvaWARngot5hliLrLm7Im_-_7hB/view?usp=sharing)
- Urgent audible alert notification without contextual message as to the reason of the alert. Video: [fsd-b-feedback-urgent-audible-alert-notification-without-contextual-message-2](https://drive.google.com/file/d/1YGfXYaRx87Z1mBhzRuPbi6R8yGVN4A-s/view?usp=sharing)
[fsd-b-feedback-urgent-audible-alert-notification-without-contextual-message-3](https://drive.google.com/file/d/1QCWAgIc1KGqVICnMOG8k1P-79zvXMl2X/view?usp=sharing)

## Version: FSD Beta v10.8 | 2021.44.25.6 | 1823f6dfe44d
- Refused to change into the left lane in advance of the parked emergency vehicle. Accelerated into right lane as it was cleared by vehicles in front. Didn't plan ahead. Video: [fsd-b-feedback-refused-change-into-left-lane-for-emergency-vehicle-accelerated-into-right-lane](https://drive.google.com/file/d/1v2MjoHxGqGw-9NvaxXn6lmWfUQ83bISv/view?usp=sharing)
- Unexpected left lane change attempt into side-by-side vehicle. Random and high risk maneuver. Video: [fsd-b-feedback-unexpected-left-lane-change-attempt-into-side-by-side-vehicle](https://drive.google.com/file/d/1EqNYTRRxw7pNvySa6EwSenh0mYUTMbTZ/view?usp=sharing)
- Phantom braking for a non-applicable stop sign at road fork of a merging road. Video: 
[fsd-b-feedback-phantom-braking-for-non-applicable-stop-sign](https://drive.google.com/file/d/1GXUPYzaPr-VXV6udvkUv88d-pWU5N8xW/view?usp=sharing)
- Failed to recognize roadworks speed limit sign and "End road works" sign. Speed limit was adjusted manually. Misses the beginning of roadworks (decrease speed limit) and the end (increase speed limit). Video: [fsd-b-feedback-roadworks-failed-to-recognize-speed-limit-sign-at-the-start-and-the-end-of-roadworks](https://drive.google.com/file/d/1-wlTq4A3xqvYjUfMUH8DxbCCZExnBhUR/view?usp=sharing)
- Missed exit at roundabout - went further than per route planner. The goal was to go left at T. Video: [fsd-b-feedback-missed-exit-at-roundabout-went-further-than-per-route planner-the-goal-wast-to-go-left-at-T](https://drive.google.com/file/d/1kpaO8pw2QkgQ0vZsy-6HEwnVtWwdjdjj/view?usp=sharing)
- No slowdown to stop for pedestrians. Better to have visual notification of intent to ensure driver is aware that FSD will be braking down for pedestrians. Video: [fsd-b-feedback-no-slowdown-for-pedestrians-in-crosswalk](https://drive.google.com/file/d/1415a8BSns_1nlkdPfj7muxGsWXSsZ6qj/view?usp=sharing)
- Missed right turn and proceeded to a stop sign for a left turn at a T. Right turn intent was indicated by the driver in advance. Note: no route planner (address entered) in Navigate on Autopilot. Video: [fsd-b-feedback-missed-right-turn-and-proceeded-to-a-stop-sign-for-a-left-turn-at-a-T](https://drive.google.com/file/d/15ifP-lCgYzR71grUIoc9sal56TJKrzxX/view?usp=sharing)
- Multiple lane change requests while in a single lane. Persistent notification. Lane change request into divider zone. Video: [fsd-b-feedback-multiple-lane-change-requests-while-in-a-single-lane](https://drive.google.com/file/d/1O2h2trDZDTOuJEc8HuRrNwjkOne3EoST/view?usp=sharing)
- Frozen UI - no FSD visualization left side of the screen. Resolved by two-button reset. Video: [fsd-b-feedback-frozen-fsd-ui-visualization](https://drive.google.com/file/d/1SPwYAzeobKwyjc5YsDUuVpHROAxx4bmD/view?usp=sharing)
- Urgent and extended audio alert "Take control" without clear cause and steps to resolve initial cause to stop the alert. Speed? Video: [fsd-b-feedback-urgent-audible-alert-notification-without-contextual-message](https://drive.google.com/file/d/1rSxCAsFm52yJ2AQaQ5IrZ5SHuMVvn48a/view?usp=sharing)
- Urgent audible alert notification without contextual message as to the reason of the alert. Video: [fsd-b-feedback-urgent-and-extended-audio-alert-reason-not-clear](https://drive.google.com/file/d/1zSWL5Mq9uq2lTb5pMGfSh-VystdYLKii/view?usp=sharing)
- Unexpected right turn into sidewalk after abandoning left turn attempt. Random and high risk maneuver. Video: [fsd-b-feedback-unexpected-right-turn-into-sidewalk-after-abandoning-left-turn-attempt](https://drive.google.com/file/d/15wbqFRMnjAkIFZx8mxqLrunqzOo05HWB/view?usp=sharing)
- Incorrectly attempts to perform a left turn instead of the indicated right turn. Note: no route planner (address entered) in Navigate on Autopilot. Video: [fsd-b-feedback-Incorrectly-attempts-left-turn-instead-indicated-right-turn-and-misses-left-turn](https://drive.google.com/file/d/1yAsMGpz2GGBjDpkuj_ADWXohuOa4JyMe/view?usp=sharing)
- Failed to perform a left turn maneuver. Attempted to block the right lane - failed to recognize two lanes and the vehicle in the back attempting to pass on the right. Video: [fsd-b-feedback-failed-to-perform-left turn-and-blocked-right-lane](https://drive.google.com/file/d/1eOII-67M6HKcNTBpvwWT22V2-jTp320S/view?usp=sharing)
- Lane change without user confirmation. Require Lane Change Confirmation menu option not wired to FSD stack. Assume due to two separated stacks. However, lane changes have to be confirmed by user input, if the option to confirm is enabled by the user. Video: [fsd-b-feedback-lane-change-without-user-confirmation-despite-the-activated-menu-option-due-to-two-separate-stacks](https://drive.google.com/file/d/1z-886ybv39ujC4SiXvpcJ_c-Ky2VcTP5/view?usp=sharing)
- Unmarked two-lane: crosses into the opposing traffic lane. Head-on collision risk. Improvement over 10.5. Video: [fsd-b-feedback-unmarked-two-lane-crosses-into-opposing-traffic-lane](https://drive.google.com/file/d/1v0DRQ60d7KNeXkqj6fD2_hIYjKv82koL/view?usp=sharing)
- Unmarked two-lane: right of way correction for head-on traffic route adjustment. Head-on collision risk. Improvement over 10.5. Video: [fsd-b-feedback-unmarked-two-lane-right-of-way-correction-for-head-on-traffic-route-adjustment](https://drive.google.com/file/d/169zDDPN9YCUwIvj01SRrCm3-z0BsOLdV/view?usp=sharing)
- Random slow downs at different speeds for no obvious reason without noticeable changes in the surrounding environment. Video: 
[fsd-b-feedback-random-velocity-changes-slow-downs-without-changes-in-environment](https://drive.google.com/file/d/1MyTP6yBhcqe7kRoGY8Rox3DAFG8M30ZU/view?usp=sharing)
- Velocity oscillations: random slow downs without significant changes in the surrounding environment. Video: [fsd-b-feedback-unexpected-and-unnecessary-left-lane-change](https://drive.google.com/file/d/1IHmC9iVd0S1KmYI1Ku2MS-bvwZzpRbl5/view?usp=sharing)
- Constant lane change requests despite user Cancel input. Video: [fsd-b-feedback-constant-lane-change-requests-despite-user-Cancel-input](https://drive.google.com/file/d/1RpSen71oWD1zPyyzgZ3Lrw5zQvfj8m62/view?usp=sharing)
- Incorrect visualisation of blinking yellow lights. In addition, incorrectly depicts yellow as a red light. Video: [fsd-b-feedback-incorrect-visualisation-blinking-yellow-lights-and-yellow-as-red-light](https://drive.google.com/file/d/1EmhDAv-XrJpmBetp4M7omIrSUSjFo8KP/view?usp=sharing)
- Indicating lane change maneuver - reason not clear. Video: [fsd-b-feedback-indicating-lane-change-maneuver-without-actual-turn](https://drive.google.com/file/d/1b1ROk-NZACW8tiKlm3WPOW1hylFy9FUF/view?usp=sharing)
- Changing into the left lane later than ideal Video:  [fsd-b-feedback-changing-into-left-lane-later-than-ideal](https://drive.google.com/file/d/1b7bhBpsvzlF3S5Q6XS3nMGDWzKgjeUnl/view?usp=sharing)
- Too fast into the right turn crossing into the opposing lane. Head-on collision risk.  Video: [fsd-b-feedback-too-fast-into-right-turn-crossing-into-opposing-lane](https://drive.google.com/file/d/1UxeqELgSpIvvyxLCFIbm1loXH0muBdk9/view?usp=sharing)

Non FSD related:
- UI -> iOS App -> Bug: Home screen  distance units mismatch - inconsistent use of both mi and km. Shall be either mi or km, based on user preference. https://github.com/dtkachev/autopilot-feedback/issues/1
- UI -> Redundant input zones: too many places for HomeLink control. Lack of consistency leads to confusion. https://github.com/dtkachev/autopilot-feedback/issues/2
- UI -> V11 dashcam icon is missing. User can submit autopilot feedback, but cannot trigger record/store video via button (can still be done via Honk to record/store - however using honk on the road is not always appropriate from safety perspective).
- UI -> Full screen mode needs refinement and formatting/realignment - placement of road name / next turn direction element is strange - has to be realigned in full screen mode.
- HomeLink -> Bug: manually activating HL to open garage door to drive out deactivates HL auto-close. User shall be able to activate HL to open garage door without deactivating HL auto-close functionality. Pressing HL to open garage door shall not be interpreted as Skip event.
## Version: FSD Beta v10.5 | 2021.36.8.8 |  3dea54806bfc
- Aggressive left turn attempt in traffic. Not for the faint-hearted. High risk. Video:
[fsd-b-feedback-aggressive-left-turn-attempt-in-traffic](https://drive.google.com/file/d/1_TfGX7xAOXdiMcopDapBCJ7wDBGLp7bs/view?usp=sharing)
- Non FSD related, but relevant: Full UI freeze with both turn signal and drive stalks unresponsive to input. Soft reboot resolved it, but will not be fun in traffic or at speed on highway. Not for the faint -hearted. Might be correlated with audio interruptions earlier in the day that disappeared after this soft reboot?
Video: [fsd-b-feedback-full-ui-freeze-at-speed-with-both-stalks-unresponsive](https://drive.google.com/file/d/15hfAH6l4ZOS5HEECxOqgbdpwEDNqWZf8/view?usp=sharing)
- Got stuck before attempting a left turn at a stop sign. Brakes in the left lane of the main road. Rear-end collision risk. Provides urgent audio alerts without clear contextual UI message (or I missed it) after the disengagement. Video: [fsd-b-feedback-stuck-attempting-left-turn-at-stop-signs-brakes-in-the-left-lane-of-main-road](https://drive.google.com/file/d/1dmOM2zLLiMts9JeheiOWaTyT3vR4IDj2/view?usp=sharing)
- Got stuck while attempting a left turn. Video: [fsd-b-feedback-stuck-attempting-left-turn](https://drive.google.com/file/d/1RGPHugSA2VSPRCK39toOMDiE-lQwu0vP/view?usp=sharing)
- Stopped in the middle of a two lane street in the path of opposing traffic. Video: [fsd-b-feedback-stopped-in-the-middle-of-two-lanes-in-the-path-of-opposing-traffic](https://drive.google.com/file/d/1Eg4b17wqQ_qJLUIDNpUm7XYEy6LGFSkz/view?usp=sharing)
- Random slow downs at different speeds for no obvious reason without noticeable changes in the surrounding environment. Video: [fsd-b-feedback-random-slow-downs](https://drive.google.com/file/d/1Yo955IaqRM1wQ8TprZ6MYfwk0PNBPkGc/view?usp=sharing)
- Urgent audio alerts without clear reason in road conditions and without contextual information via text notification to explain the reason for audio alert. Video: [fsd-b-feedback-urgent-audio-alerts-without-clear-reason-and-without-textual-notification](https://drive.google.com/file/d/1jPsoCyTnqc9jirRxkexFk0STW0g-L57b/view?usp=sharing)
- Non FSD related: Audio interruptions: popping sounds in the audio stream. Multiple instances w/ and w/o user input. Guess: memory leak / buffer overflow or throughput limit. Resolved by soft reboot - came back and started to pop again after several days. Video: [fsd-b-feedback-audio-interruptions-popping-sounds-in-audio-stream](https://drive.google.com/file/d/155KsikTiZ12eWjRH8u99V0iG9SOgPJ9f/view?usp=sharing)
- Enters the closed lane of the Toll booth gate. Vehicles ahead can be leveraged for initial guidance. Should be more proactive, adjusting in advance. Video: [fsd-b-feedback-enters-closed-toll-booth-lane](https://drive.google.com/file/d/1nbjoO00u7gX7HG6zPlec54rkDGZeJhfT/view?usp=sharing)
- Misses stop sign notification and obstructed stop sign. Required intervention to stop. Video: [fsd-b-feedback-misses-stop-sign-notification-and-stop-sign](https://drive.google.com/file/d/17AcoEOa_0CE5uszEuof3RgqlyRGxhIje/view?usp=sharing)
- Unmarked two-lane: right of way correction for head-on traffic route adjustment. Adjusts itself correctly in ~30% of instances, doesn't adjust in 70% of instances. Head-on collision risk. Video: [fsd-b-feedback-unmarked-twolane-right-correction-for-head-on-traffic](https://drive.google.com/file/d/1DRVKFfPRDrCDUfyO1Pm369VRPIhY9Non/view?usp=sharing)
- Fails to slow down and adjust path to the right ahead of head-on traffic avoiding parked vehicle and crossing double yellow (for safety reasons) into our path and lane. Head-on collision risk. Video: [fsd-b-feedback-no-slowdown-path-correction-due-to-head-on-traffic-crossing-double-yellow](https://drive.google.com/file/d/1kdEipdu50QfdEc0jikdmba9ExhaCOaXx/view?usp=sharing)
- Crossed double-yellow for no reason. Edge case - happens rarely (<~5-10%) in this build. Noticeable improvement on marked twisty two-lane roadways. Video: [fsd-b-feedback-crossed-double-yellow-no-reason](https://drive.google.com/file/d/1R9VEoNACtM2iB6flu0Uu77vsa_nQ3lVm/view?usp=sharing)
- Unmarked two-lane: blind uphill requires path adjustment to the right for safety reasons to reduce risk of head on collision. However staying in the middle of the road when no head-on traffic seems reasonable as it is typically the best road surface. Video: [fsd-b-feedback-unmarked-two-lane-blind-uphill-requires-path-adjustment-right-side](https://drive.google.com/file/d/1uqPwXp7a9-L2mJztsiauEnNzRTbpB23L/view?usp=sharing)
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
- No slow down to 25 mph for the school zone from 40 mph. Fails to recognize flashing school zone speed limit in effect and reduce current speed limit.
Video: [fsd-b-feedback-active-school-zone-no-slow-down-25mph](https://drive.google.com/file/d/1AwTI3z-zGTt7BwWcLmkROW74Hvsqj2k-/view?usp=sharing)
- [1] Didn't adjust the route/path for parked vehicle in advance for a human driver to be "comfortable" to avoid disengagement. [2] Incorrectly performed "Emergency lane correction" back closer towards the high-risk zone of the parked truck after driver disengaged FSD and adjusted the route to account for the parked truck. Safety mechanism counteracted proper user correction.
Video: [fsd-b-feedback-1-didnt-adjust-to-avoid-parked-vehicle-2-incorrectly-performed-emergency-lane-correction-into-parked-vehicle](https://drive.google.com/file/d/11Cicwl1Q4pURigGrIKXdymH_BGU0VIFp/view?usp=sharing)
- Didn't adjust the route/path for parked vehicle in advance for a human driver to be "comfortable" to avoid disengagement. Path adjustment was too late and too close to the trailer.
Video: [fsd-b-feedback-didnt-adjust-to-avoid-parked-vehicle-on-the-right](https://drive.google.com/file/d/1biv_9SkqagH7-VID8CzQhNaWvW4bu4pa/view?usp=sharing)
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
- Multiple disengagements. Does not follow vehicles ahead standing in the off-ramp lane. Attempts twice to go left even though right merge into the off-ramp will be problematic further down the road and other drivers will not be happy. Video: [fsd-b-feedback-tries-to-exit-the-only-off-ramp-lane-multiple-disengagements](https://drive.google.com/file/d/1vgVSJvLxo9OXKjzG3aXhqTr3wu63hoUZ/view?usp=sharing)
- Fails to change into the right lane in advance to follow the route to make a planned right turn. Video: [fsd-b-feedback-fails-to-change-right-into-turning-lane](https://drive.google.com/file/d/1W4YTN9ZJhup5h__oCMuAYkU9QLMEdoVx/view?usp=sharing)
- Not clear why attempted to perform a shift into the left lane. Hesitation. Video: [fsd-b-feedback-hesitation-not-clear-why-attempted-to-perform-change-into-left-lane]
(https://drive.google.com/file/d/1bk1iPtPm1oszRevgAUYPkJNggGjJYsfE/view?usp=sharing)
- Gets stuck in between two lanes. Enough space to proceed on the left. User intervention proceeds the vehicle forward in the left turning lane.
Video: [fsd-b-feedback-stuck-between-two-lanes-enough-space-to-proceed](https://drive.google.com/file/d/1oWwwQbsiA1dVWTEGaGN3dorOjlfUQZ-8/view?usp=sharing)
- Right lane change hesitation before right-hand turn. Initiated lane-change, canceled it, returned back to the left lane, before attempting and completing the maneuver.
Video: [fsd-b-feedback-right-lane-change-hesitation-cancellation](https://drive.google.com/file/d/1_ybxlc2bixz5c9-BVyXRwZwScBeGlqbb/view?usp=sharing)
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
- No slow down for road dip. Does not recognize the DIP sign ahead of the actual road dip.
Video: [fsd-b-feedback-dip-sign-no-slow-down](https://drive.google.com/file/d/19V8hp5xSi2uUlAhuPqy5gO310iyUNwmW/view?usp=sharing)
- No path adjustment for potholes. Doesn't allow driver input without disengagement to account for potholes / obstacles.
- Audio: random popping sounds in audio stream. Non-speaker related: 35-40% volume. Non-educated guess: either buffer overflow or multi-stream audio merge issues at playback. Happened with different number of "pops" (1) without touching screen (2) when touching record video button (3) when changing volume via steering wheel.
Audio: []()
- Not a bug, but a feature:
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







# Not bugs, Features:
- Correctly navigates flooded unmarked two-lane roadway. Suggestion: slow down to 10-15 mph to prevent hydroplaning, hidden holes, and bumper damage from initial hydrohit.fsd-b-feedback-feature-not-a-bug-correctly-navigates-unmarked-two-lane-roadway-unreal
https://drive.google.com/file/d/1PUACtN7Tms-GXcjZP4liOaXxXqbsro7t/view?usp=sharing
# Feature suggestions:
- Homelink -> Add support for opening/closing gates/doors by calling a dedicated phone number.
- Homelink -> When Drive is engaged and the garage door is closed (confirmed by front video and HL status) and the driver is pressing accelerator pedal, HL shall trigger garage door opening event.
- Mobile app -> Service -> Appointment -> Services: Add ability to attach videos (10Mb limit per file), not just photos | Reason: video format provides better context to troubleshoot remotely and prepare
- Show side camera for lane change maneuvers. Model 3 mirrors have dead zones. Status: resolved.
- Provide supercharger contact details via qr code for driver reports / user feedback url. Missing on many superchargers in US.
- Dashcam -> Tap to record: In addition to video feeds, add a separate feed/source of a Touchscreen state of a screenshot(photo) or video of the last 15-60 seconds before the tap. Reason: will help troubleshooting UI edge cases and bugs.
- Add search bar to contacts page UI.
- Bug i18n incorrect spacing padding cyrillic fonts. Status: resolved.
- Enable audible notifications for lane change requests. Status: resolved.