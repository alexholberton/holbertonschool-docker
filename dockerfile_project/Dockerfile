# 1. Define the base image
FROM alpine:latest

# 2. Install a package (using Alpine's package manager)
RUN apk add --no-cache curl

# 3. Copy the local file into the image filesystem
COPY message.txt /message.txt

# 4. Set the default command to run on startup
CMD ["cat", "/message.txt"]