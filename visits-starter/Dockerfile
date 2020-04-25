# Use Base Image
FROM node:alpine

# Define the WORking Direcotry of container
WORKDIR '/app'

# Copy the dependecy file from machine to container
COPY package.json .

# Download all dependicies
RUN npm install

# No copy the entire struccture
COPY . .


# Container Run Command
CMD ["npm","start"]