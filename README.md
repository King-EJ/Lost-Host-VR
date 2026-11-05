# Lost-Host-VR
VR mod for Lost Host


<img width="1024" height="1024" alt="r3ng4sr3ng4sr3ng" src="https://github.com/user-attachments/assets/27c8a0da-784c-4ab2-bd51-de8a24fe748c" />



LOST HOST VR  -  VR mod (Unity 6000.3, IL2CPP x64, URP, BepInEx 6)
===================================================================
Version 0.1.1 (test build)



CONTROLS - the Quest controllers are an Xbox controller for the game (its own pad controls and prompts)
-
  Menus / pause: a normal gamepad
    Sticks, A / B / X / Y, triggers = LT / RT, grips = LB / RB, stick clicks = L3 / R3, X + Y together = Start
    
  *Driving:*
    Left stick ............ drive / steer (the game's left stick)
    
    Right stick ........... camera (left / right / down)
    
    Right stick UP ...... X
    
    X ..................... LB (the left grip's game button)
    
    Hold LEFT GRIP ........ left stick = D-pad (up / down / left / right); the car doesn't drive while you hold it
    
    Right stick click ..... DRIVER SEAT on / off (you sit on the RC car)
    
  X + Y together = Start (pause)
  
  *Always:*
    Left grip + Y ......... VR SETTINGS MENU (stick up/down choose, left/right change, A toggle, B close)
    
    Left grip + X ......... re-centre the view
    
  [Controls] DrivingControls = false makes it a plain gamepad everywhere.

VIEW
  * Game camera (default): you are where the game's camera is and see the world in 3D; your view turns with it.
  * Driver seat (R3 while driving): nobody sits in the RC car, so the mod puts you on top of it, in the middle
    (or at the car's own "hood camera" place if it has one). Your view turns with the car.
    Too low / too far back? Settings menu "driver seat: eyes higher / forward" ([View] DriverSeatOffset).
    The RC car is small - [General] WorldScale below 1 makes you smaller (the car feels bigger).
  * Menus / pause: the game's picture on a solid screen in front of you. While driving, the HUD floats in front
    of you with its black parts see-through ([View] HudPlace = LeftHand / RightHand puts it on a hand).

