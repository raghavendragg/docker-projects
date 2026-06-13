# Pull the base image for Python 3.8
FROM python:3.8-slim

# Set the working directory in the container
WORKDIR /app

# Copy everything from the current directory to the working directory in the container
COPY . .

# Install the required dependencies from requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Run the Flask application when the container starts
CMD ["python", "app.py"]
