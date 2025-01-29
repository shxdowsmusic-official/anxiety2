# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

[PLAY!](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: So before we start, how would *you* like to read?

`publish("show_options_bottom")`

# intro-start-2

n3: Now, let's begin our story...

```
publish("hide_tabs");
clearText();
```

(...1000)

`publish("intro-to-game-2")`

n2: THIS IS A HUMAN

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

```
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
```

(...300)

n: AND THIS IS THE HUMAN'S ANXIETY

n: _YOU_ ARE THE ANXIETY (again)

(#act1_normal)


# act1_normal

```
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: Okay, you are really annoying me, i'ma go scroll through tiktok.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: YOUR JOB IS TO PROTECT YOUR HUMAN FROM *DANGER*

`bb({eyes:"look", mouth:"small_lock", body:"fear"})`

b: Gasp! You're scrolling your life away on TikTok! Again Again!

```
bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
```

h: Shut up it's fun.

`hong({eyes:"neutral"});`

n: QUICK, WARN THEM ABOUT A *DANGER!*

```
bb({eyes:"look"});
```

[They are banning tiktok!](#act1d_news)

[Is this post about *us?*](#act1d_subtweet)

[Hehehe, i love men](#act1d_milk)

# act1d_milk

`hong({mouth:"smile", eyes:"surprise"});`

h: Yeah i like me-

```
hong({mouth:"shock", eyes:"shock"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

h: wait a minute aren't you a man?

(...200)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("20p", "bad");
publish("hp_show");
```



