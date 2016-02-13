iconsize=scalable
category=emblems
icondir = $(datadir)/icons/sugar/$(iconsize)/$(category)

icon_DATA =			\
	emblem-busy.svg		\
	emblem-charging.svg	\
	emblem-downloads.svg	\
	emblem-favorite.svg	\
	emblem-locked.svg	\
	emblem-notification.svg	\
	emblem-outofrange.svg	\
	emblem-question.svg	\
	emblem-view-source.svg  \
	emblem-warning.svg	\
	onboard-activity-palette.svg \
	onboard-activity-palette-startnew.svg \
	onboard-activity-title.svg \
	onboard-activity-description.svg \
	onboard-frame-drag-in.svg \
	onboard-frame-drag-out.svg \
	onboard-frame-current-activity.svg \
	onboard-frame-mesh-view.svg \
	onboard-frame-home-view.svg \
	onboard-frame-journal.svg \
	onboard-wifi.svg \
	onboard-buddy.svg \
	onboard-journal-details.svg \
	onboard-owner-icon.svg

EXTRA_DIST = $(icon_DATA)

install-data-local: install-iconDATA
	(cd $(DESTDIR)$(icondir)/.. && $(ICONMAP) -c $(category))
