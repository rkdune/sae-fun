create something every day.

have fun while doing so.

### setup for runpod (this is probably incorrect in many ways)

* make sure your runpod secrets has `WANDB_API_KEY = your-key` configured.

### on start

1. Install `uv` (fast Python package installer):
   ```bash
   # On Linux/macOS:
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```

2. Restart your shell for `uv` to apply.
   ```bash
   # Run this to confirm installation
   uv --version
   ```

3. Install requirements

    `uv add sae-lens transformer-lens circuitvis`

