# Whiteboard video on Google Colab

This folder contains a Colab notebook that installs and runs [chalkboard](https://github.com/Atharva-Kanherkar/chalkboard) in a temporary Colab runtime. It uses Ollama with Qwen2.5 3B for script generation and Piper for Vietnamese narration. Chalkboard splits the narration into scenes, draws the matching whiteboard visuals, syncs each scene to the voice, and joins the result into one MP4. No API key is required; AI image generation is disabled by default.

The output is hand-drawn whiteboard animation, not realistic AI-generated footage.

## Use it

1. Upload this folder to your own public GitHub repository.
2. Open `chalkboard_colab.ipynb` in Google Colab, or add this badge after replacing the placeholders:

   `[Open in Colab](https://colab.research.google.com/github/USERNAME/REPOSITORY/blob/main/colab-whiteboard/chalkboard_colab.ipynb)`

3. Run the cells from top to bottom, enter a video topic, then download the MP4.

The first run downloads Node dependencies, Chromium, the Qwen model (about 1.9 GB), and the Vietnamese Piper voice. Re-run setup cells after starting a fresh Colab runtime.

This notebook is a Colab launcher for the upstream project, not a full fork of its source code.
