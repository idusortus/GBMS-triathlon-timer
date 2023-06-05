# GBMS-triathlon-timer
Sloppy Maui Blazor app for timing triathalons - WIP

Currently:
- Maui Blazor Hybrid Application
- Single Screen with 3 buttons:
  - Start timer
  - Mark finish time (for a single racer in event)
  - Export results as CSV
- Restart timer by closing/opening the application 🥉

I used it today to track finish times for our youth participants. On saving the file I opened it as a Google Sheet & shared it out.

TODO
- [ ] 'Start Boys' and 'Start Girls' options
- [ ] Store all results on local Sqlite
- [ ] Store waves/brackets
- [ ] Allow import of Bib Data (Runner name, bib #, age group)
- [ ] When wave/bracket is complete, join race results & bib data, export to Google Sheet/Doc
- [ ] Increase 'record result' button size


- [ ] unbind finish times from bottom and tie to just beneath the buttons (First results end up hidden depending on device)
- [ ] Visual indication/animation that 'record result' button was recently pressed (a low opacity spinner? ~something to make it clear a result was just registered

