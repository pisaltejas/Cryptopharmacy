FROM node:14

EXPOSE 4200
COPY . /client
WORKDIR /client
RUN npm install
CMD [ "npm", "run", "start" ]

# # Stage 2: Serve app with nginx server
# # Use official nginx image as the base image
# FROM nginx:latest

# # Copy the build output to replace the default nginx contents.
# COPY --from=build /usr/local/app/dist/sample-angular-app /usr/share/nginx/html

# # Expose port 80
# EXPOSE 80