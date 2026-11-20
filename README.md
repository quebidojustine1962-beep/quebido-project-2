# Kabankalan Catholic College Landing Page (Project 2)

A responsive, multi-page student landing page using HTML, CSS, and JavaScript, inspired by a Bootstrap-style college website layout. The KCC logo provided for the assignment is included locally in `assets/kcc-logo.jpeg`.


## Pages
- `index.html` — Home / landing page
- `about.html` — School introduction, vision, mission, and core values
- `courses.html` — Program overview cards
- `course-details.html` — Program detail template
- `events.html` — Campus life
- `pricing.html` — Enrollment steps (template; no fees invented)
- `trainers.html` — Faculty profile placeholders
- `contact.html` — Contact information
- `starter-page.html` — Blank reusable page


## Notes before submitting
- Change the folder name from `quebido-project-2` to your own `lastname-project-2` if your surname is different.
- Photos used on the site are external illustrative stock photos, not verified KCC campus photos. Replace these with school-approved photos if available.
- Institutional mission and vision text and core values are included based on public KCC information. Confirm official wording with the College if your instructor requires a particular document.
- Google Fonts and stock photos require an internet connection.


## Open in Visual Studio Code
1. Download and extract the ZIP.
2. Open VS Code.
3. Select **File → Open Folder** and choose the project folder.
4. Open `index.html`. For live preview, install **Live Server**, right-click `index.html`, and select **Open with Live Server**.
5. Edit the HTML/CSS and save. Refresh the browser to preview changes.


## GitHub upload and 10 commits
Open the VS Code terminal inside the project folder and run:

```bash
git init
git add .
git commit -m "Create KCC landing page structure"
```
Then make small meaningful edits and commit each milestone. Example sequence (make the change described before running each command):

```bash
git add . && git commit -m "Add KCC logo and header navigation"
git add . && git commit -m "Build responsive hero section"
git add . && git commit -m "Add welcome and college introduction sections"
git add . && git commit -m "Add vision and mission content"
git add . && git commit -m "Add core values cards"
git add . && git commit -m "Create program overview page"
git add . && git commit -m "Create campus life page"
git add . && git commit -m "Add contact and enrollment pages"
git add . && git commit -m "Improve mobile layout and navigation"
```
The initial commit plus the nine example commits makes 10 commits. Git requires an actual change for every commit; if a command says there is nothing to commit, edit or add the described content first.

## Publish using GitHub Pages
1. Create a new GitHub repository. Keep it public if required for your assignment.
2. In the terminal, connect and push (replace `YOUR-USERNAME` and `YOUR-REPOSITORY`):
```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/ (root)`, then **Save**.
6. Wait for the Pages deployment to finish. Your published link will look like:
   `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`
7. Submit both your Pages URL and repository URL in your class Google Form.
