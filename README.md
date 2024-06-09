
# Dirtix Bot

This is a simple Telegram bot that echoes back any message sent to it. It also responds to `/start` and `/hello` commands with a welcome message.

## Project Structure

```
.
├── .env             # Environment variables file
├── .env.sample      # Sample environment variables file
├── .git             # Git repository directory
├── .gitignore       # Git ignore file
├── .venv            # Virtual environment directory
├── bot.py           # Bot script
├── requirements.txt # Python dependencies
└── README.md        # Project documentation
```

## Setup Instructions

### Prerequisites

- Python 3.6 or higher
- `pip` (Python package installer)

### Steps

1. **Clone the repository** (if applicable)

    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create and activate a virtual environment**

    ```sh
    python -m venv .venv
    # On Windows
    .venv\Scripts\activate
    # On Unix or MacOS
    source .venv/bin/activate
    ```

3. **Install the required packages**

    ```sh
    pip install -r requirements.txt
    ```

4. **Set up the environment variables**

    Create a `.env` file in the project directory with the following content (replace `your_bot_token` with your actual bot token):

    ```
    BOT_TOKEN=your_bot_token
    ```

    You can use the `.env.sample` file as a template.

5. **Run the bot**

    ```sh
    python bot.py
    ```

## Usage

- Send `/start` or `/hello` command to the bot to receive a welcome message.
- Send any other message and the bot will echo it back to you.

## Files Description

- **.env**: Contains the environment variables for the bot.
- **.env.sample**: A sample environment variables file for reference.
- **.git**: Directory containing Git repository data.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **.venv**: The virtual environment directory.
- **bot.py**: The main bot script.
- **requirements.txt**: Lists the Python packages required to run the bot.
- **README.md**: Project documentation.

## License

This project is licensed under the MIT License.
