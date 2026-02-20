FROM mcr.microsoft.com/devcontainers/base:noble AS development
RUN apt-get update

# # --- STAGE 2: Build ---
# FROM development AS build-stage
# RUN npm run build

# # --- STAGE 3: Production ---
# FROM nginx:stable-alpine AS production
# COPY --from=build-stage /workspaces/app/dist /usr/share/nginx/html
# EXPOSE 80
# CMD ["nginx", "-g", "daemon off;"]