# Help Improve This Site

Machines and software change. If a step doesn't match what you see in the lab, a link is broken, or something is confusing, please let us know. You'll help the next group of students.

**Students:** tell your instructor, or open an "Issue" on this site's GitHub page describing what's wrong and which page it's on.

## For instructors and peer mentors: editing a page

You don't need to install anything.

1. Go to the repository on GitHub and open the `docs` folder.
2. Click the page you want to change (for example `laser-cutting/prepare-machine.md`).
3. Click the **pencil icon** (Edit this file).
4. Make your change. Pages are written in **Markdown**:
    - `# Heading`, `## Smaller heading`
    - `**bold**`, `*italic*`
    - `- bullet`, `1. numbered step`
    - `- [ ] checkbox`
    - `![Description of photo for screen readers](../images/laser/photo.jpg)`
5. Click **Commit changes…**, write a short note about what you changed, and click **Commit changes**.
6. The site updates itself in about a minute.

!!! tip "Every change is saved"
    GitHub keeps a full history. If something goes wrong, any earlier version can be restored.

### Adding a photo

1. Open `docs/images/` and the right topic folder.
2. Click **Add file → Upload files** and upload your photo (use a short name like `new-lens.jpg`, no spaces).
3. Add it to a page with `![What the photo shows](../images/laser/new-lens.jpg)`.

!!! warning "Always write a description (alt text)"
    The words inside `![ ]` are read aloud by screen readers. Describe what the photo shows.
