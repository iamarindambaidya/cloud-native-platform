# Use Go base image
FROM golang:1.20

# Set work directory
WORKDIR /app

# Copy code
COPY . .

# Build Go binary
RUN go build -o product-api main.go

# Expose port
EXPOSE 8081

# Run the binary
CMD ["./product-api"]