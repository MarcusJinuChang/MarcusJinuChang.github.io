# MarcusJinuChang.github.io

The developer site behind `https://marcusjinuchang.github.io/`, served by
GitHub Pages from `main` (Jekyll, no theme set, so GitHub's default).

| Path | URL | Why it is here |
|---|---|---|
| `NoteCode/privacy.md` | https://marcusjinuchang.github.io/NoteCode/privacy | NoteCode's privacy policy. The app links it (`AppInfo.privacyPolicy`) and so does App Store Connect. This URL must never break. |
| `NoteCode/support.md` | https://marcusjinuchang.github.io/NoteCode/support | NoteCode's support page, App Store Connect's Support URL. |
| `NoteCode/index.md` | https://marcusjinuchang.github.io/NoteCode/ | Links the two. |
| `app-ads.txt` | https://marcusjinuchang.github.io/app-ads.txt | AdMob reads it from the developer site's root, which a project site (`/NoteCode/`) cannot serve. |
| `index.md` | https://marcusjinuchang.github.io/ | The root page. |
| `_config.yml` | | The site description, as on the NoteCode repo's `gh-pages`. |

The NoteCode pages were copied unchanged from the NoteCode repo's `gh-pages`
branch (commit cca62fb). While that repo still publishes Pages, its site wins
for `/NoteCode/` and these copies are not what readers see; once its Pages are
turned off, these serve the same URLs. Edit the pages here from then on, and
keep "Last updated" in the privacy policy current.
