# The Russian Revolution: How an Empire Fell in Days (1905-1924)

Full 38:33 documentary, 1920x1080 30 fps, narration (script unchanged), sound effects and score.
`Russia_Part01.mp4` ... `Russia_Part13.mp4` play in order (about 3 minutes each).

Join into one file:

    cd russia
    for f in Russia_Part*.mp4; do echo "file '$f'"; done > list.txt
    ffmpeg -f concat -safe 0 -i list.txt -c copy Russian_Revolution_Full.mp4
