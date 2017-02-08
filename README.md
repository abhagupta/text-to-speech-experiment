This project does following :

- Takes a picture of you on the computer
- Saves the file in your local filesystem
- Picture can be uploaded to `http://docs.kairos.apiary.io/#reference/face-recognition/verify/post?console=1` for verification right away
- If matched with what we have in our gallery, we get a response of 'Success' and what it matched with, for example, Julia.
- If 'success', `googleTTS` will say "Hello Julia"
- If 'failure' `googleTTS` will say, "Sorry I don't know you".