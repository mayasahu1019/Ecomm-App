# Node version-package we are using to build the application
FROM mode:22-alpine AS builder 

WORKDIR /app

COPY package*.json ./


# Set up the work directory


# Copy the package files


# run the install command


# copy the entire code base


# run the build command


# something different  
FROM nginx:alpine AS production

COPY --from=builder /app/dist /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
