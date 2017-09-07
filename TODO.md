# Tasks

 [ ] Rework internal GcalWindow working
 [ ] Add disable/enable of views
 [ ] Rework GcalViews as grid only (WeekView, MonthView, YearView)
 [ ] Rework GcalViews to implement the new API (remove every "New API" comment)
 [ ] Make GcalTimeSelector an entry
 [ ] Properly fix timezone handling
 [ ] Rethink signals from GcalManager
 [ ] Order events chronologically in views
 [ ] Change ordering of events in all-day views (use a custom ordering)
 [ ] Add different triggers for hiding the sources view.
 [ ] Check for the real need of adding timezone, and check everywhere
 [ ] Connect all dconf options to the program
 [ ] Check the real need of a caching GcalManager

# Design tasks

 [ ] How to handle timezones?
 [ ] How should a Single Day view look like?
 [ ] Need mockups for:
   [ ] Day view
   [ ] Agenda view
   [ ] Timezone selector
 [ ] What to do when there's no host set in the event.

# Wishlist

 [ ] Make GcalEventWidget a composite widget
   [ ] Turn into a GtkGrid subclass
   [ ] Remove all the custom drawing madness
 [ ] Add resize-by-handlers capabilities to GcalEventWidget