# zizkarna
web, admin, lineup page
react + php controller, model, view architecture

## lineup page
TODO

## web
  - one page
  - area graphics with inherited button links
    - onclick - move/zoom in map
      - => minimum of redirects
    - screen in center of area
      - upcoming 3 events (from db)
   - loading animation on load
   - [ ] programme
      - first thing to do and launch under wordpress page
      - qr code (print on posters?)
      - table with events, calendar
## admin
  - forms (add/edit) in modal => better UX (speed in administration)
  - contacts table
    - bands
      - name
      - cash
      - contact
      - genre
      - input list
      - last concert
      - members count
      - socials
    - people
      - contact
      - hour rate
      - surety person (core member team)
  - events
    - band(s)
    - money in
      - bands (load from db, but editable)
      - sound system
      - light system
      - personal
      - marketing
    - money out
      - tickets
      - bar
      - area rent
    - input lists (load from db, but editable)
    - socials (load from db)
    - intesity for graphs (famouse band has more impact than local student band)
  - graphs
    - line graph of event revenue
    - heatmaps
      - area activity (based on bands impacts has its value at exact day, but exceeds to days before and after event)
      - money from events
