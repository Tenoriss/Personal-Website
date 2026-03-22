# Task: Add dark/light theme modes

## Previous Task Status
CV button move [✅ COMPLETE]

## New Task Plan Breakdown & Progress

### Step 1: Confirm plan [✅ DONE - Fixed top-right moon/sun icon toggle, light mode: off-white bg (#f8fafc), dark text (#020617), slate secondary (#64748b), adjusted cards/shadows]

### Step 2: Implement CSS vars & toggle HTML [✅ DONE]
- Added :root / [data-theme="light"] vars for all colors.
- Refactored body, loader, hero, profile, about, skills, achievements, contact, btn, particles to vars.

### Step 3: Add JS theme functions [✅ DONE]
- Fixed top-right toggle button (moon/sun icons).
- loadTheme(), toggleTheme() with localStorage persist.
- DOMContentLoaded + click listeners.

### Step 4: Test toggle [✅ DONE]
- Dark default persists.
- Toggle switches themes smoothly (0.3s transition).
- Icons rotate/change (moon/sun).
- All elements adapt (cards, shadows, text).

### Step 5: Final [✅ COMPLETE]
**Dark/light modes fixed! Particles now adapt color to theme (--border-accent blue). Toggle top-right ☾/☀. Smooth/persists.**
