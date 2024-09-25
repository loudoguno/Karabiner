# ubiquitous mode
want have mode triggered with right pinky that can use for common key commands
- wouldn't be set up like a simlayer, would need to be set up like spacemode 


## space mode
- currently space-mode is set up as a :layer
```edn	
:space-mode {:key :spacebar :condi [:!f& :!d& :!c& :!k& :!w& :!Rctrl-mode :!LCMD]} ; prevents space mode from overiding F and D modes
```
- has conditionals not to be overridden by f,d,c,k,w,Rctrl-mode and LCMD mode... but am confused what adding key modes as conditionals here actually does

## Rctrl-mode
- Rctrl-mode is set as :layer to send space when pressed along
- has :condi for f,d,c,k,w, and space mode

## numpad, numrow, symrow mode
- set as :layer with f:20 activating

## backslash mode
- set as :layer with backslash activating, used to be set as simlayer
- currently pressing space+\ will activate both space and backslash mode

## simlayers
- have d-mode with conditional for space-mode... not sure what that does
- using simlayers for `=`, `/`, `.`, `return`, `"`... 

# hyper-key


# LOG
2024-09-25
- set ⌃⌘+w
  - maybe should be done with single quote mode?

# brainstorming...
how to structure this...
- should it trigger a keyboard maestro macro namde "open in new window"
- should it send a key command to the app then filter by device?

- on the rights said it seems `-`, `=`, `[`, `]`, `\`, `;`, `'`, `<` `>`, `/`, `return`, and `←↑→↓` are all kind of available as right pinky arrow keys 
  - `;` semicolon is muscle memoried to be fn for Contexts
  - `/` is muscle memoried to do search 
  - ❓ how would i implement /+⌘n does something different than `/+n for search notion`?
    - if slash& is a symlayer, 
- on the left hand we only have
  - capslock (taken)
  - tab (taken)
  - tilde
  - shift and fn
  - `q` i guess 

- my current muscle memory