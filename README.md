# StarLibrary
A Scripting Library to help your scripts look cleaner and also help you if you only starter scripting.

## How To Boot The Library
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/WanHubMan/StarLibrary/main/Code"))()
```

## Ways Of Use :
First Of All, There are many functions you can use to make scripting a lot easier ! follow the introductions to make it work the best it can !

Teleport To :
```lua
TpTo(x, y, z) -- Cordinates, You can only use 3 numbers ! Not more or less or it will bring an error !
-- You can also Tp to instances ! Just put the path to it in the function and thats it!
```

Tween To :
```lua
TweenTo(x, y, z, type, seconds_speed) -- x, y and z are the cordinates and types are "Time" and "Speed",
-- For example :

TweenTo(536, 29, 60, "Time", 50) -- seconds_speed is the time or the speed, depends on what type you selected !
-- You can also Tween to instances ! Just put the path to it in the function and thats it!
```

Copy Cordinates :
```lua
--You can use this to copy cordinates quick,
CopyCordinates(cf_v3) -- here you should write if you want to copy the whole "CFrame" number or "Vector3"!
-- for example :
CopyCordinates("Vector3") -- Should bring 3 numbers like : 305, 693, 52
-- Vector3 is also the default so you can put nothing in it too
```

## Functional Ways To Use :
Change WalkSpeed & JumpPower :
```lua
-- Pretty simple.
ChangeWalkSpeed(number) -- put in "number" the number of speed you want to change to
ChangeJumpPower(number) -- Same here
```

Fly :
```lua
-- You can use this to toggle off and on flying
ToggleFly() -- Will toggle fly, on and off 
-- To set fly max speed you can do :
FlyMaxSpeed(number) -- put here the number of speed you want :)
```
Some Misc Features :
```lua
HopServer() -- Will hop a server 
Rejoin() -- Will rejoin the same server
ToggleNoclip(boolean) -- put here true or false to set noclip true or false
SendMessage(text) -- will send the message you write in the chat
```
