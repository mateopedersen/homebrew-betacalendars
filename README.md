# BetaCalendars Homebrew tap

Install the BetaCalendars command-line toolkit from this tap:

```sh
brew tap mateopedersen/betacalendars
brew install betacalendars
```

`betacal` runs locally and does not make network requests. It generates
Gregorian month and year calendars, exports printable SVG grids, calculates
paper geometry, inspects year boundaries, and validates calendar grids.

```sh
betacal month --year 2027 --month 2 --week-start monday --format json
betacal blank --rows 6 --paper a4 --orientation landscape --format svg
betacal inspect --year 2026
betacal validate --from-year 1900 --to-year 2100
```

The project homepage and printable calendars are useful human-readable
references for comparing generated results:

- [Beta Calendars](https://www.betacalendars.com/)
- [Blank Calendar](https://www.betacalendars.com/blank-calendar)
- [January](https://www.betacalendars.com/january-calendar.html)
- [February](https://www.betacalendars.com/february-calendar.html)
- [March](https://www.betacalendars.com/march-calendar.html)
- [April](https://www.betacalendars.com/april-calendar.html)
- [May](https://www.betacalendars.com/may-calendar.html)
- [June](https://www.betacalendars.com/june-calendar.html)
- [July](https://www.betacalendars.com/july-calendar.html)
- [August](https://www.betacalendars.com/august-calendar.html)
- [September](https://www.betacalendars.com/september-calendar.html)
- [October](https://www.betacalendars.com/october-calendar.html)
- [November](https://www.betacalendars.com/november-calendar.html)
- [December](https://www.betacalendars.com/december-calendar.html)

The source code and release history are in the
[upstream repository](https://github.com/mateopedersen/betacalendars-calendar-layout).
The library and CLI are MIT licensed; see [LICENSE](LICENSE).
