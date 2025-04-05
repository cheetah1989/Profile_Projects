# Use official Python image
FROM python:3.10-slim

# Set working directory
WORKDIR /app

# Copy and install dependencies
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy application code
COPY app/ ./app

# Set environment variable
ENV PYTHONPATH=/app

# Run the web application
CMD ["python", "app/main.py"]
