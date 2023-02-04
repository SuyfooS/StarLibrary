# StarLibrary
A Scripting Library to help your scripts look cleaner and also help you if you only starter scripting.

## How To Boot The Library
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/WanHubMan/StarLibrary/main/Code"))()
```

## Ways Of Use :
First Of All, There are many functions you can use to make scripting a lot easier ! follow the introductions to make it work the best it can !

- Teleport To :
```lua
s_TpTo(x, y, z, part) -- Cordinates, You can only use 3 numbers ! Not more or less or it will bring an error !
```
You can also Tp to instances ! Just put the path to it in the function and thats it!
Another way of use is to teleport a specific part, just leave empty if you want to teleport the character.

- Tween To :
```lua
s_TweenTo(type, seconds_speed, x, y, z) -- x, y and z are the cordinates and types are "Time" and "Speed",
-- For example :

TweenTo(536, 29, 60, "Time", 50) -- seconds_speed is the time or the speed, depends on what type you selected !
```
You can also Tween to instances ! Just put the path to it in the function and thats it!

- Copy Cordinates :
```lua
--You can use this to copy cordinates quick,
s_CopyCordinates(cf_v3) -- here you should write if you want to copy the whole "CFrame" number or "Vector3"!
-- for example :
s_CopyCordinates("Vector3") -- Should bring 3 numbers like : 305, 693, 52
-- Vector3 is also the default so you can put nothing in it too
```

- Change WalkSpeed & JumpPower :
```lua
-- Pretty simple.
s_ChangeWalkSpeed(number) -- put in "number" the number of speed you want to change to
s_ChangeJumpPower(number) -- Same here
```

- Fly :
```lua
-- You can use this to toggle off and on flying
s_ToggleFly() -- Will toggle fly, on and off 
-- To set fly max speed you can do :
s_FlyMaxSpeed(number) -- put here the number of speed you want :)
```
- Some Misc Features :
```lua
s_HopServer() -- Will hop a server 
s_Rejoin() -- Will rejoin the same server
s_ToggleNoclip(boolean) -- put here true or false to set noclip true or false
s_SendMessage(text) -- will send the message you write in the chat
s_MaxBrightness() -- Sets the brightnes to max, It will just make everywhere dark to not dark
s_FPSCounter(boolean) -- true/false, will create a new fps & ping counter on the screen, you can disable it and enable it always
s_LowQuality() -- will make the game a lot less laggy, and will make it ugly af
s_KillPlayer() -- will kill the local player
s_ToggleNoclip(boolean) -- set to true or false depends if you want noclip on or off
```

- Functional Ways To Use :

```lua
s_getPlayerCFrame() -- Will return the cframe of the player
s_getPlayerPosition() -- Will return the Position of the player
-- You can also put a player's name inside of the function call to get his cframe, leave empty if you want the local player

s_getInstanceCFrame(Instance) -- Will return the cframe of the instance you put inside of the function call
s_getInstancePosition(Instance) -- Will return the Position of the instance you put inside of the function call
```

```lua
s_getDistance(path1, path2) -- will return the distance between 1 point(path) to the 2 point(path).
```
- More Functional Ways :
```lua
s_FindAllDescendants(Name, Path, IsA) -- Search from all the descendants from the path you selected to find the object that you selected the name of,
-- the third parameter is optional, its checking if the part that has been found is a "Part", "Text", "Model" or "Animation".
s_FindAllChilds(Name, Path, IsA) -- same for here but its only childrens
```
Both of these will return true or false depends if it was found
```lua
s_Generate(length, numbers, lowercase, uppercase) -- will generate a code, length is how long you want the code to be. numbers, lowercase and uppercase
-- are just booleans you can set to true and false depends if you want it in the code you are generating, you can skip that if you want all.
```
