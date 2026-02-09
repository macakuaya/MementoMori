# Memento Mori

A single-page visualization of a human lifespan as a grid of days. Each square is one day. The filled ones are spent. The empty ones are not yet yours.

A red square marks the total number of days a father lived. One day the filled squares will reach it and pass it.

A clock ticks in the header, counting every hour, minute, and second since birth.

## How it works

- **30,685 squares** — one for each day of the average life expectancy in Spain (84.01 years).
- **Filled squares** — days already lived, counted from the date of birth.
- **Outlined squares** — days not yet spent.
- **Red square** — the total number of days a father lived before he died. Hovering shows his age at death.
- **Last square** — hovering shows the life expectancy of Spain.
- **Live clock** — total hours, minutes, and seconds since birth, updating every second.
- **Tooltips** — hover any square to see the age it represents (e.g. "35 years, 3 months, 7 days").

## Running

Open `index.html` in a browser. No dependencies, no build tools, no frameworks. One file.

Or serve it locally:

```
python3 -m http.server 8090
```

## Artistic references

This project exists within a tradition of artists and thinkers who have tried to make the passage of time visible and countable.

### Tim Urban — "Your Life in Weeks" (2014)

The most direct predecessor. Urban's [Wait But Why post](https://waitbutwhy.com/2014/05/life-weeks.html) presented a 90-year life as a grid of ~4,680 weekly squares. It went viral and spawned posters, apps, and open-source clones. Urban compared each week to a tiny diamond — 4,680 of them fit in a tablespoon. This project uses days instead of weeks, producing a grid so dense it becomes almost illegible — which is itself a statement about how we experience time.

### Alberto Caeiro (Fernando Pessoa) — *Poemas Inconjuntos* (1915)

The philosophical foundation. Caeiro, Pessoa's shepherd-heteronym, wrote: *"Tem só duas datas — a da minha nascença e a da minha morte. Entre uma e outra cousa todos os dias são meus."* ("It has only two dates — that of my birth and that of my death. Between one and the other, all the days are mine.") This grid is the literal form of that idea: two dates, and every day between them, laid out as squares.

### On Kawara — *Today* series (1966–2013)

For nearly fifty years, Kawara painted the current date on a canvas — nothing else. Each painting is a record of a single day's existence. This project does something similar in aggregate: each square is a day that existed, marked or unmarked, accumulating into a life.

### Roman Opalka — *1965/1 – ∞*

Opalka spent his entire career painting consecutive numbers from 1 toward infinity, each canvas a continuation of the count. He died in 2011, and the counting stopped. His work is about the act of measuring time by living through it. The grid of days shares this impulse — a count that will stop when it stops.

### Damien Hirst — Memento Mori works (1990s–2000s)

Hirst's diamond skull (*For the Love of God*, 2007), his skeleton vitrines, and his *Memento* etchings all engage with mortality as spectacle. Where Hirst makes death beautiful and expensive, this project makes it quiet and numerical — 30,685 tiny squares on a dark screen.

### The Stoic tradition

The Latin phrase *memento mori* — "remember that you will die" — was whispered to Roman generals during triumphs to keep them humble. Marcus Aurelius, Seneca, and Epictetus all wrote about meditating on death as a way to live more deliberately. This project is a digital form of that meditation.

## What makes this one different

The red square. It is not about the viewer's mortality alone — it is about grief embedded in a timeline. A father's entire life, measured in days, placed inside the grid of his child's expected life. The child has not yet lived as many days as the father did. One day they will. That moment is built into the piece, waiting.

## License

Do whatever you want with it.
