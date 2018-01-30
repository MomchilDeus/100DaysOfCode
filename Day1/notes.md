### What I did today
- I went over the Random example in the Elm Introduction (pages 36-39)
- I could use a random image for every dieFace on Roll, but I don't think it makes sense for a die to have a random number of faces
- I might use a List String to hold URLs for images, generate a random number and use it to take out a URL at an index
  - need to figure out how to get an element at an index in a List
  - maybe use the Array library?
    - I can use: Array.get Int (Array.fromList list) - but it does return a Maybe.Maybe String
- I made it work first with getUnsafe and then with this:
  - Maybe.withDefault "None"' <| Array.get int <| Array.fromList model.faces
