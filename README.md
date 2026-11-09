# Schedule Maker

**Turn your college timetable into your personal schedule.**

Upload the master timetable, select your Major, Minor and Division, and instantly see the courses and time slots relevant to you. Free, and runs entirely in your browser.

> This is a private project, not an official tool of any university. It can make mistakes, so please double-check the output against your official timetable.

---

## Features

- **Upload any timetable format:** Excel (.xlsx), CSV, text-based PDF, or a screenshot.
- **Reads your file, guesses nothing:** days, times, courses, classes and rooms are detected from your file and shown back to you so you can fix any mistakes.
- **Dynamic selection:** Major, Minor, Core Division (or class and electives) come from your file, not from a hardcoded list.
- **Labelled courses:** every course is tagged as Major, Minor or Core.
- **All options per course:** see every available slot for each course.
- **Clash warnings:** clashes are flagged with the exact overlap.
- **Clash-free combinations:** the app finds combinations of options that fit together.

## How it works

1. **Upload:** drop in the master timetable your college shared.
2. **Select:** pick your Major, Minor and Core Division, or your class and electives.
3. **Plan:** view your weekly timetable, spot clashes and choose a clash-free combination.

## Privacy

Your timetable stays on your device.

| | |
|---|---|
| **Reading** | Excel, CSV and text PDFs are read inside your browser tab. Nothing is sent to a server. |
| **Images** | Screenshots are read with an OCR engine downloaded into your browser. Your image is not uploaded. |
| **Account** | No login, no payment, nothing saved. Close the tab and it is gone. |

## Usage

1. Open `schedule-maker.html` in your browser (or visit the hosted link, if available).
2. Click **Create My Timetable** and upload your file.
3. Review what the app read, then select your Major, Minor and Division.
4. Browse your options and clash-free combinations.

All instructions are available inside the tool. For more help, feel free to reach out.

## Project structure

```
Schedule-Maker/
├── README.md
└── schedule-maker.html   # the entire app, single file
```

## Limitations

- Output depends on how clean the uploaded timetable is. Always review the "what we read" preview and correct errors.
- Screenshot (OCR) reading is less reliable than Excel or CSV.
- Scanned PDFs without selectable text may not parse correctly.

## Author

Built by [Jinendra Pamecha](https://www.linkedin.com/in/jinendra-pamecha/)
