# prepare_sources
## Helper script for comparing LibreELEC-based projects

Downloads and rearranges "primary_project" and "secondary_project" to match
in a way that is specific to integrating LibreELEC-based projects

At this time, this is very specific to RetroGFX:UnofficialOS, but all PRs are
welcome

The script produces a diffing environment for the two projects, for comparing
and integrating differences, with less noise

The script uses functions defined in the "functions" file, which is expected
to be in the same directory

The script is intended for developers of LibreELEC-based projects, in an
interactive Linux bash environment
