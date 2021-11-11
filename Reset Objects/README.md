##Reset Objects Udon

An Udon to reset one or multiple Objects

#How to use:
* Import Udon to unity project
* Add component "Udon Behaviour (Script)" to a button or interactive object
* Add "ResetObjects.asset" to program source
* In Public Variables select Objects and Cords to enter how many objects you wanna reset (Objects and Cords shall have the same number)
* In Hierachy right click each Object and add an empty Gameobject (give each empty gameobject a number or an individual name)
* move the empty game object in the hierachy so it is not a children of the original object anymore (DON'T MOVE THE EMPTY GAME OBJECT IN THE SCENE)
* In the Reset Udon Behavoir move every moveable object in "Objects" and every empty game object in "Cords" (give object and empty object the same number starting with 0)