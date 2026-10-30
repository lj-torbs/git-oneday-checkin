# One-Day Git Check-in

Goal: prove you can use Git from the terminal by submitting one small `.txt` file today.

Your file must contain three lines:

```
Name: RODEL, Tresha Mae
Subject code: IT 5 - 1974
Time: 4:21
```

`Time` is the time you are writing it (check your clock). Your commit time is also recorded by Git, so type the real time.

## Steps (terminal only, except steps 1 and 9)

1. On GitHub, click **Fork** on this repository.
2. Clone **your fork**: `git clone <your-fork-url>`
3. `cd git-oneday-checkin`
4. Set your identity: `git config user.name "Your Name"` and `git config user.email "you@example.com"`
5. Make your file by copying the template. Name it `SURNAME_Firstname.txt` (for example `DELACRUZ_Juan.txt`):
   `cp submissions/TEMPLATE.txt submissions/DELACRUZ_Juan.txt`
   (Windows Command Prompt: `copy submissions\TEMPLATE.txt submissions\DELACRUZ_Juan.txt`)
6. Open your new file in any plain text editor (`nano`, or `notepad` on Windows) and replace the three lines with your own details. Do not edit `TEMPLATE.txt`.
7. Check what Git sees, then save it:
   `git status`
   `git add submissions/DELACRUZ_Juan.txt`
   `git commit -m "Add check-in for Juan Dela Cruz CS8"`
8. Send it to your fork: `git push origin main`
9. On your fork's page on GitHub, click **Contribute**, then **Open pull request**, then **Create pull request**. Put your filename as the title.

## Done when

- `git log --oneline` shows your commit at the top.
- Your pull request appears in this repository's **Pull requests** tab.

## Rules

- One file only, in `submissions/`, named `SURNAME_Firstname.txt`.
- Do not change anyone else's file or `TEMPLATE.txt`.
- Do not upload through the GitHub website. The terminal commit is the point.
