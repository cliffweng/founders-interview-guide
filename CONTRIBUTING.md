# Contributing

Thanks for helping improve the guide. A few ground rules:

- **Scope**: one topic per file under `topics/`. Keep each topic readable in ~10 minutes.
- **Template**: follow the structure already used in existing topic files (Why it matters, Core concepts, Mental model, Interview questions, Watch, Further reading).
- **Links must be real**: only link to YouTube videos and essays you have personally verified exist (open the URL, confirm the title). Never guess a video ID or URL. Prefer YC partner talks (Dalton Caldwell, Michael Seibel, Gustaf Alströmer, Kevin Hale, and the Startup School lectures), Paul Graham's essays, and primary a16z / First Round pieces, but any reputable, verified source is fine.
- **No invented product direction**: this guide is interview prep for Penn founders heading into YC / accelerator interviews and early VC diligence. It is not a startup-ops playbook. If you want to propose a new topic or reorganize the curriculum, open an issue first.
- **Non-goals**: do not add a full operating playbook (that belongs in a separate startup guide), legal deep dives, quizzes, auth, or a progress backend. Do not add a `CNAME` file. `cliffweng.com` stays with the sibling guides.
- **Local preview**:
  ```bash
  bundle install
  bundle exec jekyll serve
  ```
  Then open `http://127.0.0.1:4000/founders-interview-guide/`.
- **Pull requests**: keep them focused (one topic or fix per PR) and describe what changed and why.
