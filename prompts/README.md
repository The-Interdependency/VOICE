# prompts

Build prompts for work on this repository.

skill-lib does not currently define a `prompts/` location convention. This directory exists so a Grok Build prompt can live beside the VOICE contract without using a derived-artifact directory name such as `build/`, and without touching `log/`, `milestones/`, `status/`, `README.md`, or `index.html`.

## Usage Guidance

To have Grok Build create the VOICE app from the saved prompt:

1. Check out [The-Interdependency/VOICE](https://github.com/The-Interdependency/VOICE).
2. Create and switch to a new branch. Do not work on `main`.
3. Open Grok Build in that checkout.
4. Copy the fenced prompt in [`grok-build-voice-app.md`](grok-build-voice-app.md) and paste it as the Grok Build user request.
5. Review the resulting changes. Open a pull request to `main` if one was not opened. Do not merge without Erin Spencer's explicit go-ahead.

Limitations: this directory only stores prompts. It does not implement the app, enable GitHub Pages, or make an entry canonical.

hmmm: whether `prompts/` remains the long-term home for build prompts in this repository.
