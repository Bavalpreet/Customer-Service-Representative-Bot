# Rasa Customer Service Bot

Welcome to the Rasa Customer Service Bot! This bot is designed to assist users from three different counties: Clay County, Utah, and West Hollywood. It provides customer service functionalities tailored to the needs and inquiries specific to each county.

## File Structure

- **actions/**: Contains custom action files for the bot.
- **configs/**: Configuration files for the bot, including different diet configurations.
- **data/**: Data files containing NLU training data for frequently asked questions in each county.
- **domain-grp/**: Domain files for each county's specific functionalities.
- **results/**: Result files including confusion matrices, error logs, and histograms generated during testing.
- **scripts/**: Shell scripts to start the services and shell for the bot.
- **tests/**: Test stories to evaluate the bot's performance.
- **.dockerignore**: Specifies which files and directories to exclude when building a Docker image.
- **.gitignore**: Specifies intentionally untracked files to ignore.
- **Dockerfile**: Instructions for building a Docker image for the bot.
- **README.md**: You're currently reading it!
- **citibot.html**: HTML file for the bot interface.
- **config.yml**: Configuration file specifying the pipeline and policies for the bot.
- **credentials.yml**: File to store credentials for external services.
- **domain.yml**: Main domain file defining the bot's capabilities and responses.
- **endpoints.yml**: Configuration file for the endpoints of the bot, like the action server.
- **render.yaml**: Render configuration file.
- **testing.py**: Python script for testing the bot.
- **viewresults.py**: Python script to view test results.

## Usage

1. **Installation**: Make sure you have Python and Rasa installed on your system.
2. **Training**: Train the bot using the training data provided in the `data/` directory and the configurations specified in `configs/`.
3. **Testing**: Evaluate the bot's performance using the provided test stories in the `tests/` directory.
4. **Deployment**: Deploy the bot using Docker or any other suitable platform.

## Customization

- **County-Specific Functionality**: Customize the bot's responses and actions based on the specific requirements of each county by modifying the domain files in `domain-grp/`.
- **NLU Training**: Enhance the bot's understanding by adding more training data in the `data/` directory.
- **Configuration**: Adjust the bot's behavior by modifying the configuration files in `configs/`.

