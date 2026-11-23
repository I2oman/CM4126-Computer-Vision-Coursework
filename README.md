# CM4126 Coursework

## Checkpoints

Trained models and training histories are saved in `outputs/checkpoints/` so completed runs can be reused without retraining. To run everything from scratch, delete the `outputs/` folder.

The `outputs/` folder (trained model weights and cached images, about 4 GB) is too large for GitHub, and a full run from scratch takes about an hour on my PC. For this reason, I have uploaded the whole coursework, including the zipped `outputs/` folder, to OneDrive. It can be downloaded from the link provided in the submission. To reuse the saved results, unzip `outputs/` into the coursework folder before running the notebook.

## Declaration of AI Assistance

Generative AI tools were used mainly for two purposes:

- **Written content:** rephrasing and clarifying some text to improve readability.
- **AMD GPU support:** helping write, adapt and troubleshoot code so the coursework could run on my AMD Radeon RX 7900 XT. This involved addressing compatibility and performance issues in the Windows PyTorch/ROCm environment, which is less straightforward to use than the commonly supported NVIDIA CUDA setup.

Outside these areas, AI assistance was minimal to none. The coursework's experiments, evaluation, analysis and interpretation of results were my own work. I reviewed and tested any AI-assisted code.
