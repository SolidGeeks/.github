# Social previews

The image GitHub shows when a repository link is shared (1280 × 640, set by hand in each repository: *Settings → General → Social preview*).

| File | Repository | Crew member |
|---|---|---|
| `org-solid-geeks.png` | the organization | the whole crew |
| `repo-strata.png` | Strata | Atlas |
| `repo-muster.png` | Muster | Term |
| `repo-lockedworld.png` | The Locked World | Brax |
| `repo-template-example.png` | example of the Studio's plain template | Brick |

## Making one for a new project

Repository previews come from the *GitHub social preview* template of the [Studio](https://solidgeeks.github.io/SolidGeeks/studio.html), in its **screenshot mode**: the `social` drawing also takes an `img`, and then places the screenshot on the right with a fade and the crew member over it, as above. The Studio form does not expose `img` yet, so these were rendered by calling that drawing from a script in a headless browser, with:

- `title`: the project name; `line`: one sentence, what it does and for whom
- `tag`: `<license> · v<major.minor>`
- `char`: a crew member **not used by another project yet**, so previews stay apart side by side
- `img`: a real screenshot of the app, dark theme, at least 1600 px wide

Keep the screenshot real: it is the first thing people see of the project.
