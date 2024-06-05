# Use the official HashiCorp Terraform image as the base image
FROM hashicorp/terraform:latest

# Set the working directory
WORKDIR /workspace

# Copy the Terraform configuration files into the container
COPY terraform /workspace

# Set the entry point to terraform
ENTRYPOINT ["terraform"]
