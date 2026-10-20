# ASL fingerspelling practice with gloves (research prototype)

Live: https://shadowcoder1.github.io/asl-fingerspelling-gloves/

A webcam practice page for ASL fingerspelling handshapes, for L, X and G: each letter is a glove drawn in the camera
view for your hand to fit into, with your own hand's skeleton drawn inside it; the glove turns green when the
handshape is right and wobbles when the letter is made; after a miss it says which letter your hand looked like and
what to change. Hand tracking is Google's MediaPipe; the grader is a small statistical model fitted on public, openly
licensed hand-landmark datasets (attributions inside `tutor/model.json`), with OpenFS (KETI) as a second opinion on a
few letters, for non-commercial research. Everything runs in the browser and nothing is saved.

This teaches fingerspelling handshapes, not ASL. To learn ASL, learn from Deaf teachers. Grading is approximate and
can be wrong.

Options: `?letters=LXG` (letters, in that order; letters without a glove get an outline), `&look=outline`,
`&hand=left`, `&srcmirror=1` (a camera that sends a mirror image). Keys: G shows or hides the glove, F dims the room,
N skips to the next letter.

This folder is a published copy of the running page only.
