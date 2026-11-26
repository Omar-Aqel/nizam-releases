# Changelog

Release notes for Nizam. The latest installer is on the [releases page](https://github.com/Omar-Aqel/nizam-releases/releases/latest).

### v2.8.0 — your workspace, your way

- **Reminders:** recurring reminders with a notification at their time — every day, every few days or on chosen weekdays. Today's reminders sit on the Overview with a tick; see the last 7 times and the next date; pause, edit, delete with undo.
- **Weather** at the top of the Overview: your city, the sky and the temperature (Open-Meteo).
- **Did you know?** A new general-knowledge fact every time you open the app (104 facts, Arabic and English, offline).
- **Customise the Overview:** hide anything, reorder cards by dragging, make each card narrow, wide or a full row, with a live preview.
- **Collapsible sidebar** (Ctrl + \) and **your own menu:** reorder pages, move them between groups, hide pages.
- **Welcome tour** on first run: what the app does, your name (shown in the greeting) and city, then how to start. New installs no longer show the developer's name.
- **Right-click menu** in the desktop app: cut, copy, paste, paste as plain text, select all, undo / redo, links, images, Google search.
- **New Settings window:** sections on the side, content in its own scroll area with an easy-to-grab scrollbar.
- **Notebook:** drawing pen with highlighter and eraser, export a page as PDF, full screen (Esc exits), page list left / right / hidden, links with your own text, customisable toolbar, images you can copy or drag to the desktop / WhatsApp, text that sits on the paper lines, sources as a clear separate section.
- **Effects reworked:** the see-through window now works (it needs Windows *Transparency effects*; the app tells you and offers a restart), new mesh and contours backgrounds (bubbles, leaves and rain removed), one consistent hover language, refined arrow / circle pointers.

### v2.7.1 — About

- **Settings → About:** app version, the developer (Omar Aqel) with LinkedIn and GitHub links, copyright and licence. Click the version under the logo in the sidebar to open it.
- The Windows installer and `Nizam.exe` now carry "Copyright © 2026 Omar Aqel" and the author name (file Properties → Details); `LICENSE` added.

### v2.7 — files in the notebook (v2.7.0)

- **Attach any file to a notebook page:** PDF, Word, Excel, PowerPoint, text, audio, video, zip… up to 25 MB each. Use the paper-clip in the toolbar, type **/file**, or drag files onto the page.
- **A card by default, the file in the page when you want it:** every file shows as a card (type icon, name, size, download, delete). **Show in page** opens it right there: PDFs in a full viewer (zoom, pages, print), images, video and audio players, and text / code files. Your choice is saved with the page.
- Attached files are part of automatic backups and the JSON export, like images; file names are searchable.

### v2.6 — notebook, year view for habits, graphite logo (v2.6.0)

- **Notebook:** a new page in the sidebar for notes, ideas and research. Each page is a clean document with headings, bold / italic / underline / highlight, bulleted, numbered and check lists, quotes, code and dividers. Type **/** on any line for the block menu, select text for quick formatting, **Ctrl + K** on selected text adds a link.
- **Images in pages:** insert from your device, paste a screenshot or drag photos in. They are shrunk automatically (a phone photo becomes ~100–300 KB) and kept apart from the rest of your data, so they never fill the app's storage.
- **Sources for every page:** title, link and a note for each paper, article or video you use.
- **Page style:** plain, lined, grid (squares) or dotted paper, per page.
- **Arabic and English in one page:** every paragraph takes the direction of its first letter.
- **Pin, search, duplicate, download as Markdown;** pages save themselves as you type. Search pages by title from `Ctrl + K`.
- **Notebook data is backed up:** pages are in automatic backups and the JSON export (with their images); on the desktop app images are also copied next to the backups, so a restore brings them back.
- **Habits — a whole year at a glance:** a GitHub-style heatmap per habit (January → December), darker on days you spent more time, with a year switcher.
- **Time per habit:** log time (+15 m, +30 m, +1 h or exact minutes) for today or any past day, see the total hours per habit and per year, and pick a colour for each habit.
- **Focus timer → habits:** choose a habit in the focus timer and every finished focus session adds its minutes to that habit.
- **New logo in Graphite colours:** a white N on a graphite gradient with an orange dot.

### v2.5.1 — faster, calmer effects, one settings gear

- **Faster typing and clicking.** We measured what the background art cost and rebuilt it: typing 40 characters went from about 445 ms of work to about 60 ms, and an idle window with rain went from about 2.7 s of work every 4 seconds to about 0.2 s.
  - The art is now **still by default**. Turn on **Movement → Animated** in Settings → Effects if you want it to move.
  - Moving art pauses by itself while a dialog is open, for a moment while you type, and while the window is hidden.
  - Rain is drawn as two layers of streaks instead of dozens of separate drops; leaves and bubbles each move in one smooth path.
- **Calmer, more natural art:** softer light fields without visible rings, leaves that turn over as they fall, plain bubbles, rain with near and far drops. The light that followed the mouse is gone; hover now means a small lift and a soft shadow on clickable cards, and buttons that step up and press down.
- **One gear for all settings.** The sidebar footer now has language, dark mode, a **Settings** gear and the **Data & backups** shield. Appearance, Effects, Widgets, Profile and export are all inside Settings.

### v2.5 — effects and desktop widgets (v2.5.0)

Everything new is optional and can be switched off in **Settings → Effects** or **Settings → Widgets**.

- **Background art behind the pages:** aurora, waves, bubbles, falling autumn leaves, rain, grid or dots, in your theme's colours. Choose animated or still and soft / medium / bold, or turn it off. The art moves slowly, pauses while the window is hidden and stays still if you reduce animations.
- **See-through window** (desktop app, Windows 11): Mica or Acrylic, like on a Mac, with three transparency levels. Cards stay solid so text is easy to read. Switch back to the normal window at any time.
- **The title bar follows the app's light / dark mode.**
- **Hover effects:** off, subtle (cards lift a little) or rich (cards lift with a soft shadow, buttons step up and press down).
- **Custom mouse pointer:** arrow, dot or ring in your theme, accent or ink colour, normal or large, with its own look over buttons and links. Or keep the system pointer.
- **Desktop widgets** (desktop app): notes, tasks, calendar, focus timer and habits as small windows on your desktop that stay in sync with the app. Pin any of them on top of other windows.
- **Start with Windows** (desktop app): opens Nizam minimised when you sign in, so your widgets are ready.
- **Tasks:** when everything is done, the page says so ("All done") instead of showing an empty space.

### v2.4 — redesign (v2.4.0, v2.4.1)

- **New logo:** a bold geometric white **N** on an emerald → deep-forest gradient, with a **gold dot** where the stroke ends. It uses the colours of the default *Forest & Gold* theme. The app, taskbar, installer and PWA icons were all regenerated.
- **Calmer, more premium look** across every page. Cards are hairline-first with barely-there shadows, primary buttons are solid, selected filters are shown in ink, headings are semibold and tighter, and section icons sit in neutral tiles.
- **New Overview:**
  - **Hero:** the date, a greeting, a one-line summary of the day ("Today: 3 left to do · 2 on your calendar") and quick actions.
  - **Today's progress panel:** a ring with a single centred percentage (a check mark at 100%) plus a tasks / habits breakdown.
  - **KPI strip:** today's tasks, habits, month spending and what's next.
  - **Bento layout:** the wide card alternates sides from row to row.
- **Refined sidebar:** the active page has a tinted background and a slim brand bar, group labels are small and muted, and the progress bar is slim.
- **Faster:**
  - Entrance animations are shorter and capped, so a page settles in about 0.4 s instead of about 1 s.
  - Every page's code is preloaded in the background once the app is idle.
  - Page switches keep the current page on screen until the next one is ready, so there are no loading placeholders.
- **Colour themes reduced to four that belong together:** Forest & Gold, Azure & Navy, Nizam Indigo and Graphite. Anyone who used a removed theme is moved automatically to the closest one.

### v2.3 — data safety and new features (v2.3.0)

- **Data protection:**
  - The app never fills itself with sample data.
  - A first-run Welcome dialog offers four choices: start fresh, sample data, import a backup, or restore an automatic backup.
  - Automatic backups run in the background, and every destructive action saves a backup first.
  - Restore any backup from **Settings → Data & backups**.
- **Google Calendar sync** (desktop app): subscribe to any calendar's secret iCal address. Events appear read-only in the calendar, Overview and reminders, with time zones, recurring events and exceptions handled.
- **Focus timer:**
  - Any length you choose (presets or custom, up to 240 minutes), plus a +5 minutes button.
  - Breaks start automatically, with a long break every 4th session.
  - A draggable timer bubble inside the app, and a small always-on-top timer window while the app is minimised. You can hide either.
- **Habits** can have a description and resource links, such as the course you're following.
- **Tasks are grouped by day:** each day shows its done / total count, with completed and open tasks together.
- **Expenses:** move between months, see the spending trend and compare with the previous month.
- **Health, inspired by Lose It:**
  - A personal calorie budget from your sex, age, height, weight, activity level and weekly pace (Mifflin-St Jeor).
  - An exercise log with calories estimated from MET values, so remaining = budget − food + exercise.
  - A weekly under / over summary and a projected date for reaching your goal.
- **Soft (One UI) design style**, plus the Azure and Graphite themes.

## All versions

| Version | Date | Highlights |
|---|---|---|
| **2.8.0** | 2026-11-26 | Reminders, weather, Did you know?, customisable Overview and sidebar (collapse, reorder, hide), new Settings window, welcome tour with your name, right-click menu; notebook drawing pen, PDF export, full screen, named links; reworked effects with a working see-through window |
| **2.7.1** | 2026-11-24 | Settings → About (developer, links, copyright), copyright in the installer, LICENSE |
| **2.7.0** | 2026-11-24 | Notebook: attach files (PDF, Office, media, text, up to 25 MB) as cards that open in the page |
| **2.6.0** | 2026-11-24 | Notebook (rich-text pages, images, sources, page styles, Markdown export), habit year heatmap with logged time and colours, focus timer counts toward a habit, Graphite logo |
| **2.5.1** | 2026-11-22 | Faster: background art rebuilt (still by default, pauses while typing / in dialogs), calmer art without glows, one Settings gear in the sidebar |
| **2.5.0** | 2026-11-22 | Background art (aurora, waves, bubbles, autumn leaves, rain, grid, dots), see-through Mica / Acrylic window, title bar follows dark mode, hover effects, custom mouse pointer, desktop widgets (notes, tasks, calendar, timer, habits), start with Windows, "All done" tasks state |
| **2.4.1** | 2026-11-19 | Logo in Forest & Gold colours (emerald gradient, gold dot) |
| **2.4.0** | 2026-11-19 | Redesign: calmer design system, new Overview hero + progress panel + KPI strip, refined sidebar, faster page switches, 4 matching colour themes |
| **2.3.0** | 2026-11-19 | Data safety (Welcome dialog, automatic backups, restore), Google Calendar sync, custom-length timer with in-app bubble and mini window, habit resources, tasks by day, expense months, Lose It-style health, Soft style |
| **2.2.0** | 2026-11-13 | Health tracker with food diary, job board, `Ctrl + K` assistant (Arabic / English, voice), visual polish, Flat style |
| **2.1.0** | 2026-11-12 | Colour themes, font picker, custom date / time pickers |
| **2.0.0** | 2026-11-12 | Forest & Gold design, animations, Windows installer with auto-update |
