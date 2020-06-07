FROM mcr.microsoft.com/dotnet/core/sdk:3.1-buster

# Install Node.js
RUN curl -sL https://deb.nodesource.com/setup_14.x | bash -
RUN apt-get install -y nodejs \
    node --version

# Install Yarn
RUN curl -o- -L https://yarnpkg.com/install.sh | bash
ENV PATH "$PATH:/root/.yarn/bin/" \
    yarn --version