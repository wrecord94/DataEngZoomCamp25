# Use an official Python runtime as a parent or base image
FROM python:3.9

# Install any needed dependencies
RUN pip install pandas

WORKDIR /app
# Import the file we created called pipeline.py
COPY pipeline.py pipeline.py

# We can also specify a startpoint rather than python as bash
ENTRYPOINT ["python", "pipeline.py"]

