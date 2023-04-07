# Text Generation WebUI Launcher Script

This script is a launcher for the [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui) project, which provides an easy-to-use interface for generating text using pre-trained language models.

## Features

* Automatic updating of the WebUI
* Customizable settings through command-line options
* Support for LLaMA models and other popular language models
* Streaming text output (optional)
* Chatbot mode and Notebook mode
* Sharing options and authentication support
* Conda environment management

## Usage

1. Clone the [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui) repository and follow the installation instructions.
2. Save this script to a file, e.g., `launch_webui.sh`, in your preferred directory.
3. Make the script executable with `chmod +x launch_webui.sh`.
4. Execute the script using `./launch_webui [OPTIONS]`.

## Command-Line Options

* `-h, --help`: Display the help message and exit.
* `-s, --stream`: Enable streaming text output.
* `-C, --cai-chat, --cai_chat`: Enable chatbot mode.
* `-N, --notebook`: Enable notebook mode.
* `--settings-file`: Specify the path to the settings file.
* `-t, --threads <NUM_THREADS>`: Set the number of threads (0-16).
* `-m, --model <MODEL_NAME>`: Set the model name.
* `--model-dir`: Set the model directory.
* `--webui-path`: Set the webui path.
* `--conda-env`: Set the conda environment.
* `-U, --update`: Check for updates and exit.

## Dependencies

This script requires the [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui) to be installed and set up. Make sure you have followed the instructions in the repository before using this script.

## License

This script is provided under the same license as the [Text Generation WebUI](https://github.com/oobabooga/text-generation-webui) project.
