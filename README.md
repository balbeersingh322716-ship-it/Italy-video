# The Entire History of Italy: From Rome to Republic

Full 41:57 documentary: code-generated visuals (1920x1080, 30 fps) with neural-TTS narration, synthesized sound effects and a score.

`video/Italy_Part01.mp4` ... `Italy_Part13.mp4` play in order (each part is playable on its own, about 3 minutes).

Join into one file:

    cd video
    for f in Italy_Part*.mp4; do echo "file '$f'"; done > list.txt
    ffmpeg -f concat -safe 0 -i list.txt -c copy Italy_Full.mp4
