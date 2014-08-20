cubes-models
============

Collection of basic cubes models.

Contents:

* `base_date` – day level time dimension
* `base_hourly_time` – hour level time dimension
* `base_time` – detailed time dimension

Use:

1. Copy `base.cubesmodel` into your model directory.
2. Derive your date/time dimensions using the base templates:

    {
        "name": "date",
        "template": "base_date"
    }

