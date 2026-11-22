# Scheduler

**Scheduler** is an interactive self-making timetable application that builds a custom schedule grid from your row and column inputs, auto-places events based on priority and preferred timings, and lets you fine-tune blocks with drag-and-drop before exporting as a PNG image.

## Features

- **Custom Grid Dimensions (`Columns × Rows`)**: Set the start date, number of columns (days, defaulting to 7 for a week), number of rows (time slots per day), starting time, and row interval (30 or 60 minutes).
- **Flexible Event Setup**: Configure any number of events with day selection, custom duration (in minutes), optional preferred timing, and priority level.
- **5-Level Priority Color System**:
  - **Extremely High** — Red
  - **High** — Orange
  - **Medium** — Yellow
  - **Low** — Light Blue
  - **Extremely Low** — Green
- **Smart Auto-Placement**: Prioritizes higher-priority events first, respects preferred times when available, and automatically finds open slots when timing is left open or conflicts occur.
- **Interactive Timetable Editing**: Drag and drop events across days or time slots, click any event block to edit its details or priority, or click an empty slot to add a block manually.
- **PNG Export**: Download a high-resolution image of your timetable along with the priority color legend.

## How to Use

1. **Set Up the Grid (Step 1)**: Choose your start date, number of columns (days), number of rows (time slots), start time, and slot interval, then apply the grid.
2. **Add Events (Step 2)**: Enter the number of events (or add/remove events dynamically) and fill in each event's name, target days, priority level, custom duration in minutes, and optional preferred time.
3. **Generate & Refine**: Click **Generate Timetable** to auto-place events, drag or click blocks to adjust anything manually, and click **Export PNG** to save your schedule.

## Deployment

Hosted with **GitHub Pages** directly from `index.html`.
