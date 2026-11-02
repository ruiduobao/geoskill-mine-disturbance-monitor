# geoskill-mine-disturbance-monitor

> Monitor surface disturbance at mining sites using multi-temporal optical/SAR/DEM data. Detect bare land, pits, dumps, roads, and vegetation removal. Track disturbance objects across years, identify boundary violations, and generate area statistics.

See [SKILL.md](SKILL.md) for full usage, inputs and outputs.

## Quick start

```bash
python scripts/mine_disturbance_monitor.py \
  --mine-boundary mine_boundary.geojson \
  --years 2020 2021 2022 2023 \
  --image-dir ./imagery \
  --disturbance-types pit dump road bare \
  --min-area 100 \
  --buffer 500 \
  --output-dir ./disturbance-output
```

## License

MIT
