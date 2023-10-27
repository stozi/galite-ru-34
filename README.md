# galliumv2-ru-34
A writing-focused 34-key ZMK/Linux layout for gallium-v2 and йцукен with mouse keys.

In Linux, set compose to pause, switch lang to rctrl.
Instructions on what to do with the 'gallium' and 'evdev' files are in those files. Copy the contents of my ZMK keymap file to yours in Github, that's a key step. ZMK mouse keys require additional setup. If ZMK mouse keys are still in beta and you haven't got it working yet, you can copy the contents of my west.yml file: https://github.com/stozi/zmk-config/blob/master/config/west.yml.


Prefixes 'ct' or 'c' mean ctrl+ below.

Illustration:

Base layer, mouse keys on the left. Switching bang and ampersand makes the former more accessible on the last layer. 

```
nul nul cut cpy pst  .   the v-  v+  mut

ml  mu  md  mr  Cbk  tab al  ad  au  ar

nul rmb mmb lmb Cdl  esc hm  pd  pu  en

layer2 layer1/enter  shift/space alt/bkspc   
```               

Hybrid ctrl/fn layer for base layer (skC is sticky ctrl, ctE is ctrl-enter)

```

F9  F10 F1  F2  F3   F4  F5  F6  F7  F8

nul wu  wd  CtE nul  nul cal cad cau car

nul nul nul skC F11  F12 chm cpd cpu ced

null layer0/enter  shift/space alt/del   
```

```
b   l   d   c   v     j   f   o   u   ,/
й   ц   у   к   е     н   г   ш   щ   з

n   r   t   s   g     y   h   a   e   i
ф   ы   в   а   п     р   о   л   д   ж

x   q   m   w   z     k   p   '"  -_  .?
я   ч   с   м   и     т   ь   б   ю   .,

layer0 layer3/enter  shift/space alt/bkspc   
```

Fn layer for alpha layer. ^ is compose, L switch lang.

```
nul nul nul L   =    :;  \Э  [Х  ]Ъ  ~Ё

9   0   1   2   3    4   5   6   7   8

nul nul nul skC ^    <>  the ()  –—  sen

null layer2/enter  shift/space alt/del   
```
