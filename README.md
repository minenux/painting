# VenenuX minetest mod `painting`

**paint** functionality in-game painting mod for minetest

## Information

This mod is named `painting` and adds paint fuctionality in game.

Using the chats commands (check below) place the easel and hit it while holding a canvas. 
the canvas will appear on the easel, ready for you to draw.

Hold a brush and start drawing. when you're finished, dig the canvas, 
and place your picture.

![](screenshot.png?raw=true)

http://www.youtube.com/watch?v=95nruaQaSz8 to see it in action

## Technical info

Bugs: if you place two pictures in one node (in a corner) you will lose the first one.

#### Chat commands

* `/giveme easel`
* `/giveme canvas`
* `/giveme painting:brush_[white, yellow, orange...]`

#### Dependences

The list of dependencies are in order or relevance and priority to work:

Required to work:

* default
* dye

Original forum post https://forum.minetest.net/viewtopic.php?f=11&t=2588

## Crafting

Easel

```
 ---- Wool ----
 ---- Wool ----
 Stick, - ,Stick
```

Canvus (16x16)

```
 ---- ---- ----
 ---- ---- ----
paper paper ---
```

Canvus (32x32)

```
 ---- ---- ----
paper paper ---
paper paper ---
```

Brush for painting (colors)

```
 dye(color) -- --
 stick   ---- ---
 stick   ---- ---
```
## LICENCE

* Code: GPLv2
* Media: CC BY-SA 3.0


