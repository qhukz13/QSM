# qsmtui

A lightweight terminal system monitor built in Rust with [Ratatui](https://ratatui.rs/) and [sysinfo](https://crates.io/crates/sysinfo).

## Features

- **System Header**: Hostname, OS version, uptime, and core count.
- **CPU Usage**: Per-core usage bars and a live sparkline.
- **Memory & Storage**: Real-time gauges for RAM, Swap, and primary disk usage.
- **History Chart**: 60-second braille line chart tracking CPU and RAM usage.
- **Process Table**: Live list of running processes sortable by CPU or memory usage.

## Usage

```bash
cargo run --release
```

## Keybindings

| Key | Action |
| --- | --- |
| `q` / `Esc` | Quit |
| `↑` / `k` | Select previous process |
| `↓` / `j` | Select next process |
| `c` | Sort processes by CPU usage |
| `m` | Sort processes by Memory usage |

## License

Licensed under the [MIT License](LICENSE).
