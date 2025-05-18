## My Ergo Keyboard

old one:
[https://www.ergokb.tw/](https://www.ergokb.tw/)

configure by [https://remap.ergokb.tw/](https://remap.ergokb.tw/) or [https://remap-keys.app/](https://remap-keys.app/)

new one:
[務實36矮軸](https://www.pragmatic.com.tw/shop/wu-shi-36ai-zhou-89)

configure by [vial](https://get.vial.today/).

practice:
[https://monkeytype.com/](https://monkeytype.com/)

## My Keyboard Layout

```
LAYER 0:
|  Q  |  W  |  E  |  R  |  T  |   |  Y  |  U  |  I  |  O  |  P  |
|  A  |  S  |  D  |  F  |  G  |   |  H  |  J  |  K  |  L  |  ;  |
|  Z  |  X  |  C  |  V  |  B  |   |  N  |  M  |  ,  |  .  |  /  |
            | WIN | CTRL| SHFT|   | MO1 | ALT | MO2 |
shift:
|
|                                                         |  :  |
|                                             |  <  |  >  |  ?  |

LAYER 1:
|  1  |  2  |  3  |  4  |  5  |   |  `  | HOM |  UP | END | PGU |
|  6  |  7  |  8  |  9  |  0  |   |  '  | LFT | DWN | RGT | PGD |
|  -  |  =  |  \  |  [  |  ]  |   | TAB |  BS | ENT |  SP | ESC |
            |     |     |     |   |     |     |     |
shift:
|  !  |  @  |  #  |  $  |  %  |   |  ~  |
|  ^  |  &  |  *  |  (  |  )  |   |  "  |
|  _  |  +  | "|" |  {  |  }  |

LAYER 2:
|  F1 |  F2 |  F3 |  F4 |  F5 |   | INS | whl |  up | whr | whu |
|  F6 |  F7 |  F8 |  F9 | F10 |   | DEL | lft | dwn | rgt | whd |
| F11 | F12 |     |     |     |   | MENU| btn1| btn3| btn2| DF3 |
            |     |     |     |   |     |     |     |
```

notes:
```
SP: space,
BS: backspace,
ENT: enter,
UP/DWN/LFT/RGT: arrow keys, up/down/left/right,
HOM/END/PGU/PGD: navigation keys, home/end/page-up/page-down,
MENU: context menu,
INS: insert,
up/dwn/lft/rgt: mouse up/down/left/right,
whl/whr/whu/whd: mouse wheel left/right/up/down,
btn1/btn2/btn3: mouse left/right/middle button,
MO1/MO2: hold to activate layer 1/2.
```

- properties
	- 3x5 is the best, because it is no need to move your hands.
	- only one way to type: tap and hold have no different; no two ctrl or shift; different layers have complete different keys.
	- no key to toggle layer (except for keyboard lock), you can only switch between layers by holding layer keys, so that don't warry about keyboard state.
	- the layout is similar to qwerty, which is easier to adapt to.
- modifiers
	- modifiers (`ctrl`/`shift`/`layer1`/`alt`) are placed on inner thumb keys, less-used modifiers (`win`/`layer2`) are placed on outer thumb keys.  they are placed in this way so that their conbinations are easy to hold (except for `win + shift`).
	- press `layer2 + /` (which is also the position of `esc`) to lock the keyboard, then press `layer1` to unlock.
- default layer
	- most of keys (`a` ~ `z`, `;`, `,`, `.`, `/`) are placed like qwerty layout, except for some keys which are out of range.
- left hand of layer 1
	- number keys (not numpad keys) are placed on left hand side of layer 1; their shift version (a bunch of symbols) are hard to remember.
	- some symbols (`-`, `=`, `\`, `[`, `]`) are placed on left hand side of layer 1; note that `[` and `]` are placed under `(` and `)`, and `|` is placed in the middle.
	- \` and `'` are placed on right hand side, because there is no place on left hand side; note that \` is originally on the top-left of common keyboard, and now it is on the top-left of right hand side of ergo keyboard; `'` is originally on the right of the home row of right hand, but now it is on the left.
	- note that `;`, `/`, `.`, `,` are placed on the right hand side of default layer (just like qwerty layout).
- right hand of layer 1
	- motion keys (4 arrow keys + 4 navigation keys) are placed on right hand side of layer 1, and are shaped like the arrow keys on the common keyboard (compared with vim style motion hjkl, it is easier to adapt to).
	- `backspace`/`enter`/`space` are placed below of `left`/`down`/`right`, which reflect their motions; `esc` is placed on the right most position of this row; `tab` is placed on the left most position of this row.
- layer 2
	- `F1` ~ `F12` are placed on left hand side of layer 2; the remaining three keys are blank.
	- mouse movement, wheel are placed on right hand side of layer 2, and shaped just like motion keys, where mouse button are placed below.
	- `menu`, `insert` and `delete` are placed on left most column of right hand side of layer 2 (there is no better positions for them).
	- note that the bottom-right key on layer 2 (position of `esc`) is the keyboard lock.

## vscode shortcut

```
|  win | home |  up  |  end | pgup |
| brkt | left | down | rght | pgdn |
| crsr | prev | hint | next |  esc |
```

- one-hand navigation: most of navigation shortcut only use `layer1`, `alt` and the keys on the right hand.
- duality: `layer1`, `alt` are exchangeable (sometimes), so that it is applicable to common keyboard.
- summary
	- `alt` -> motion, `shift` + `alt` -> select, `ctrl` -> edit
	- `,` (position of `enter`) -> hint related (hover, parameter hint, suggestion, code action)
	- `m` / `.` (position of `backspace`/`space`) -> dropdown, marker motion
	- `y` / \` -> window related (sidebar, panel, group)
	- `h` / `'` -> bracket related (jump bracket, select growing, code folding)
	- `n` (position of `tab`) -> cursor related
	- `alt` + `escape` -> command palette
- hint
	- `alt` + `,` -> hover
	- `shift` + `alt` + `,` -> parameter hint
	- `ctrl` + `alt` + `,` -> suggestion
	- `shift` + `ctrl` + `alt` + `,` -> code action
	- `ctrl` + `alt` + `m`/`.` (positions of `backspace`/`space`) -> prev/next suggestion/code action
	- `alt` + `m`/`.` (positions of `backspace`/`space`) -> prev/next marker/ref/change
- motion
	- arrow keys / navigation keys -> cursor motion
	- `shift` + arrow keys / navigation keys -> cursor select
	- `ctrl` + arrow keys / navigation keys -> word/paragraph motion
	- `shift` + `ctrl` + arrow keys / navigation keys -> word/paragraph select
	- `ctrl` + `shift` + ijkl -> drag lines/selections
	- `alt` + arrow keys -> scroll
	- `ctrl` + `alt` + arrow keys -> big scroll
- tab
	- `alt` + `pageup`/`pagedown` -> prev/next tab (also applicable to sidebar/panel)
	- `shift` + `alt` + `pageup`/`pagedown` -> drag to prev/next tab (also applicable to sidebar/panel)
	- `alt` + `home`/`end` -> prev/next group
	- `alt` + `y` -> toggle sidebar
	- `alt` + \` (`alt` + `layer1` + `y`) -> toggle panel
	- `ctrl` + `t` -> new tab
	- `ctrl` + `w` -> close tab
- multicursor
	- (`shift` +) `alt` + `n` -> goto next/prev match
	- (`shift` +) `ctrl` + `alt` + `n` -> add cursor on match and goto next/prev match
- bracket
	- `alt` + `h` -> jump between bracket
	- `shift` + `alt` + `h` -> grow selection
	- `alt` + `'` -> toggle fold
	- `shift` + `alt` + `'` -> fold
