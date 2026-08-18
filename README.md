$ python generate_hero.py

Traceback (most recent call last):
  File "C:\Users\cleyd\Documents\Default Project\generate_hero.py", line 278, in <module>
    main()
    ~~~~^^
  File "C:\Users\cleyd\Documents\Default Project\generate_hero.py", line 176, in main
    draw_dotted_hand(
    ~~~~~~~~~~~~~~~~^
        draw,
        ^^^^^
    ...<5 lines>...
        dark_color=DOTS_DARK,
        ^^^^^^^^^^^^^^^^^^^^^
    )
    ^
  File "C:\Users\cleyd\Documents\Default Project\generate_hero.py", line 83, in draw_dotted_hand
    jitter_y = (hash((int(wx), int(wy)) + 7) % 4) - 2
                     ~~~~~~~~~~~~~~~~~~~^~~
TypeError: can only concatenate tuple (not "int") to tuple
