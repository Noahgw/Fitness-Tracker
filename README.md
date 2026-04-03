# Fitness Tracker

A mobile-first web app for tracking a 24-week training program targeting a 25 km trail run in Moab, Utah — while simultaneously training for strength/weight gain, skiing, and climbing.

## Goals

- **Run**: 25 km trail race in Moab (currently running 10 km in ~1 hr)
- **Weight**: 153 → 160 lbs (6'3")
- **Ski**: Build ski fitness for BC season
- **Climb**: Maintain and build climbing volume

## The program

3 phases, 4 days/week, 24 weeks total.

| Phase | Weeks | Priority | Running volume |
|-------|-------|----------|----------------|
| Base & build | 1–8 | Strength + weight gain | 13–19 km/wk |
| Transition | 9–16 | Running builds, strength maintains | 17–30 km/wk |
| Peak & race | 17–24 | Running is king | 23–38 km/wk |

### Phase 1: Base & build
Heavy barbell compounds (squat, bench, row, RDL) twice a week, easy runs + long runs, climbing every other week. Caloric surplus of +300–400 cal/day for weight gain.

### Phase 2: Transition
Strength drops to maintenance (3 sets instead of 4). Hill runs replace easy runs. Ski prep circuits alternate with climbing. Long runs build to 18 km.

### Phase 3: Peak & race
Running takes over. One tempo/interval session per week. Strength drops to 2 sets, 1x/week. Long runs peak at 21–22 km then taper for race day.

## Features

- Full 24-week program with all exercises, sets, reps
- Weight logging per exercise
- Workout completion tracking with progress bars
- Daily nutrition/recovery checklist (IBS-friendly calorie targets)
- Custom task list
- Body weight tracker (153 → 160 lbs)
- Progress dashboard with weekly completion chart
- Dark mode support
- Mobile-first design — add to home screen as a PWA
- All data persists in localStorage (no account needed)

## Setup

1. Clone this repo or download `index.html`
2. Open in any browser, or deploy to GitHub Pages
3. On your phone: open the link in Safari/Chrome → Add to Home Screen

### GitHub Pages deployment

1. Push `index.html` to a public repo
2. Go to Settings → Pages → Source: main branch
3. Your tracker is live at `https://yourusername.github.io/moab-tracker/`

## Tech

Single HTML file. No dependencies, no build step, no framework. Vanilla JS, CSS custom properties for theming, localStorage for persistence.

## IBS nutrition strategy

The daily checklist includes IBS-friendly calorie targets:

- Olive oil on meals (+120 cal/tbsp)
- Nut butter (+190 cal/2 tbsp)
- Lactose-free protein shakes
- White rice, bananas, oats, potatoes
- Target: +300–400 cal/day surplus in Phase 1, maintenance in Phases 2–3

## Pairing with other apps

- **Strava**: Log runs and post workouts
- **Apple Health**: Strava syncs automatically; body weight can be logged in both places

## License

Personal use.
