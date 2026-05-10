# See https://github.com/devcontainers/images/tree/main/src/typescript-node
# for available VARIANT values and image contents.
#
# [Choice] Node.js version (use even numbers for LTS): 22, 20, 18
ARG VARIANT="20-bookworm"
FROM mcr.microsoft.com/devcontainers/typescript-node:1-${VARIANT}

# [Optional] Install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Install an additional Node.js version via nvm.
# ARG EXTRA_NODE_VERSION=18
# RUN su node -c "source /usr/local/share/nvm/nvm.sh && nvm install ${EXTRA_NODE_VERSION}"

# [Optional] Install global Node.js tools needed inside the container.
# create-react-app is deprecated; use the Vite or Next.js scaffolders instead.
# Uncomment and adjust as needed:
# RUN su node -c "npm install -g vite"
