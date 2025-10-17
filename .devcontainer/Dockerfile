FROM mcr.microsoft.com/devcontainers/base:ubuntu

# (Optional) Locale & fonts useful for XeLaTeX/Unicode docs
RUN apt-get update && \
    apt-get install -y --no-install-recommends \
      locales fonts-dejavu fonts-noto fonts-noto-cjk fonts-noto-color-emoji && \
    locale-gen en_US.UTF-8 && \
    apt-get clean && rm -rf /var/lib/apt/lists/*
ENV LANG=en_US.UTF-8
