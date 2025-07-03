### setup for runpod (this is probably incorrect in many ways)

* make sure your runpod secrets has `WANDB_API_KEY = your-key` configured.

### from scratch

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
    ```bash
    uv init
    uv add transformer-lens sae-lens circuitvis
    ```


### clone from gh
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

3. Clone the repo
   ```bash
   git clone https://github.com/rkdune/sae-fun.git
   ```

3. Download requirements
   ```bash
   uv sync
   ```