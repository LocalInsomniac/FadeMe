# FadeMe

FadeMe is a universal smart corpse fading system for GZDoom.

It will fade out corpses and remove them from the map after a configurable
amount of time (`sv_fadeMe_time`) has passed. If the map contains kind of
monster that can resurrect corpses (anything with a `Heal` state such as
Arch-Viles), fading will automatically be disabled for corpses that are
resurrectable until all of the healers are dead.