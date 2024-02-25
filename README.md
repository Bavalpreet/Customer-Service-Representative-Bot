## Project Structure

actions: Contains custom actions for the chatbot.
configs: Configuration files for the chatbot.
data: Data files used for training the chatbot.
domain-grp: Domain group files.
results: Directory for storing chatbot results.
scripts: Scripts related to the chatbot.
tests: Test files for testing the chatbot.
.dockerignore: Ignore file for Docker.
.gitignore: Ignore file for Git.
Dockerfile: Dockerfile for building the chatbot container.
citibot.html: HTML file for the chatbot interface.
config.yml: Configuration file for the chatbot.
credentials.yml: Credentials file for connecting to external services.
domain.yml: Domain file defining the chatbot's domain.
endpoints.yml: Endpoints configuration file.
render.yaml: Render configuration file.
testing.py: Python script for testing the chatbot.
viewresults.py: Python script for viewing chatbot results.
Setup and Usage
Clone the repository.
Install dependencies using pip install -r requirements.txt.
Configure the chatbot by editing config.yml, credentials.yml, and other relevant configuration files.
Train the chatbot using the training data in the data directory with the command rasa train.
Start the action server using rasa run actions.
Start the chatbot server using rasa run.
Access the chatbot interface by opening citibot.html in a web browser.

## Development
Custom actions can be added or modified in the actions directory.
Test cases can be written in the tests directory.
Additional training data can be added to the data directory for improving the chatbot's performance.

## Docker
The chatbot can be containerized using Docker. Use the provided Dockerfile for building the Docker image.
Dockerignore file .dockerignore specifies which files and directories to exclude when building the Docker image.
