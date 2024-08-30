# CodeGuru Response Generator

This project is a simple Gradio interface for generating responses from the CodeGuru model via a local API. The interface allows users to input a prompt, and it will return the generated response.

## Project Structure

```
project-directory/ │ ├── app.py ├── requirements.txt ├── .env ├── README.md ├── LICENSE ├── .gitignore └── Screenshot_2024-08-28_224139.png
```


## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- Pip (Python package installer)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/codeguru-response-generator.git
cd codeguru-response-generator
```
2. Install the required Python packages:
```bash 
pip install -r requirements.txt
```

### Running the Application
1. Start your local API service. Make sure it's running at http://localhost:11434.

2. Launch the Gradio interface:
```bash 
python app.py
```
3. Open your web browser and go to `http://127.0.0.1:7860/` to interact with the interface.

## Example Usage
1. Enter a prompt in the provided textbox and click "Submit."
2.The generated response will appear below the textbox.

## Files
- `app.py`: The main Python script that contains the Gradio interface and logic for making requests to the local API.
- `requirements.txt`: Lists all the Python dependencies needed to run the application.
- `.env`: (Optional) Contains environment variables such as API keys. This file should not be included in version control.
- `README.md`: This file, providing an overview of the project.
- `LICENSE`: The project's license, specifying how others may use the code.
- `.gitignore`: Specifies files and directories that should be ignored by Git, such as the .env file and any other sensitive information.
- `Screenshot_2024-08-28_224139.png`: A screenshot of the interface, included for reference.


## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
