# Use a imagem base oficial do DevContainer
FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

# Copie o binário da imagem 'uv' para o container
COPY --from=ghcr.io/astral-sh/uv:latest /uv /uvx /bin/
