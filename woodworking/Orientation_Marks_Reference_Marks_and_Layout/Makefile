all: Orientation_Marks_Reference_Marks_and_Layout.png

# I have a wrapper script referenced below (the "w" is for "wrapper")
# that installs and invokes a more recent Inkscape than the operating
# system I'm using provides (they are always ALWAYS behind the latest
# release ... grrrrRRRRrrr):
INKSCAPE_PATH = inkscapew

Orientation_Marks_Reference_Marks_and_Layout.png: Orientation_Marks_Reference_Marks_and_Layout.svg
	$(INKSCAPE_PATH) $< --export-filename=$@ --export-area-page --export-overwrite --export-type=png
