# Use an official Python runtime as a parent image
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Set environment variables
# ENV DATABASE_URL 'postgresql://postgres:ajay@76ae0602215bad055c23f67f2849226dba74fc1a0649d0fce1b0e7224a3fd4af:5432/todo'
# ENV SQLALCHEMY_TRACK_MODIFICATIONS False

VOLUME  /data

# Make port 80 available to the world outside this container
EXPOSE 80

# Run app.py when the container launches
CMD ["python", "app.py"]
