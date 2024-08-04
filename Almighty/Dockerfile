# Don't change this [ /Almighty/ ] name!
# Change from below link, else bot wil not work!


FROM node:20

RUN git clone https://github.com/hammytec/Almighty-Md /root/Almighty

# Clear npm cache and remove node_modules directories
RUN npm cache clean --force
RUN rm -rf /root/Almighty/node_modules

# Install dependencies
WORKDIR /root/Almighty
RUN npm install

# Add additional Steps To Run...
EXPOSE 3000
CMD ["npm","start" ]
