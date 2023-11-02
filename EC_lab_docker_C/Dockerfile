# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY problem_one.c .
# Compile the C program
RUN gcc -o problem_one problem_one.c
# Set the command to run when the container starts
CMD ["./problem_one"]