# Use the .NET 6 SDK as the base image
FROM mcr.microsoft.com/dotnet/sdk:6.0 AS build

# Install Node.js
RUN curl -sL https://deb.nodesource.com/setup_14.x | bash - \
    && apt-get install -y nodejs

# Install Angular CLI
RUN npm install -g @angular/cli@12

# Set up the working directory
WORKDIR /workspace
