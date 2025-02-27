# Monitor Past and Future Runs

Each workspace has a dedicated Runs menu that allows you to visualise all past and future runs.

<video
    className="border-2 rounded-xl object-cover w-full h-full"
    autoPlay
    loop
    controls
    id="main-video"
    src="/videos/runs-menu.mp4"
/>

## Aggregated View

The Runs menu in each workspace provides a time series view where you can monitor different time slots. The green (respectively, red) dots being the tasks that succeeded (respectively, failed). You can adjust the level of details by picking "All", "Runs", "Previews" or "Dependencies".

![Time series](./1-runs-menu.png "Time series")

> All past and future runs of the workspace are visible from the menu

## Details per Run

Clicking on each run in the menu opens a run page where you can view the run's state, inputs, and success/failure reasons.

View of a past run:

![Details per run](./2-detail-per-run.png "Details per run")

> Check the details of each runs

<br/>

You can also view [scheduled](../1_scheduling/index.md) runs from the run menu, which provides information on the arguments used and the next trigger.

View of a scheduled run:

![Schedule run](./3-scheduled-run.png)

> Although scheduled scripts and flows are visible on their dedicated tab, the run menu helps you see the next scheduled one

## Filters

There are multiple ways to filter the Runs menu:
- by Datetime
- Success / Failure
- Skipped / Not skipped
- Runs / Previews / Dependencies / All
- by [Path](../../reference/index.md#path)
- by Arguments
- by Result

Example of filters in use:

![Filters](./4-filters.png "Filters")

> Here were filtered successful runs which returned `{"message": "Created record in table"}`