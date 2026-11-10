// example of Deimos syntax. 
// TODO: change syntax or odin devs will sue you!
FIX:

import "fmt"

Rect :: struct {
    x: int,
    y: int,
}

ColoredRect :: struct {
    Rect, // sturct embedding
    color: [4]int // [255, 0, 0, 255]
}

add :: (a, b: int) -> int {
    return a + b
}

area_of_rect :: (rect: Rect) -> int {
        return rect.x * rect.y
}

/*
Multiline comment
in Deimos
*/

SCREEN_SIZE :: 300 // const
x := 50            // variable declaration
x : int = 20.5     // variable declaration with type definition

main :: () {
    a := 10
    b := 5.5
    c := a * b
    fmt.println("C = ", c) // "C = 55\n"

    a := Rect{x = 50, y = 20}
    fmt.println("Area of a = ", area_of_rect(a)) // "Area of rect = 1000\n"
}
