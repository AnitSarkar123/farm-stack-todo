FROM python:3

# Set the working directory
WORKDIR /usr/src/app
COPY  requrement.txt ./

# Install the dependencies

RUN pip install --no-cache-dir --upgrade -r ./requrement.txt

# Copy the source code
COPY . .

EXPOSE 3001

# Run the application
CMD [ "python", "./src/server.py" ]