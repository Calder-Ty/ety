# ety
CLI etymology tool

This is a simple script for getting etymology quick from [etymonline.com](https://etymonline.com)

## Example

`ety thunder`

```
thunder (n.)

	mid-13c., from Old English þunor "thunder, thunderclap; the god Thor,"
	from Proto-Germanic *thunraz (source also of Old Norse þorr, Old
	Frisian thuner, Middle Dutch donre, Dutch donder, Old High German
	donar, German Donner "thunder"), from PIE *(s)tene- "to resound,
	thunder" (source also of Sanskrit tanayitnuh "thundering," Persian
	tundar "thunder," Latin tonare "to thunder"). Swedish tordön is
	literally "Thor's din." The unetymological -d- also is found in Dutch
	and Icelandic versions of the word (compare sound (n.1)). Thunder-
	stick, imagined word used by primitive peoples for "gun," attested
	from 1904.


thunder (v.)

	13c., from Old English þunrian, from the source of thunder (n.).
	Figurative sense of "to speak loudly, threateningly, or bombastically"
	is recorded from mid-14c. Related: Thundered; thundering. Compare
	Dutch donderen, German donnern.

```

## Install

Installation is simple, download the script to your a dirctory in your path:

```bash
wget https://raw.githubusercontent.com/Calder-Ty/ety/main/ety -o ~/.local/bin/ety
chmod +x ~/.local/bin/ety
```

Since ety only uses the python standard library, all that is required is that
Python 3.8+ is installed on your system.
