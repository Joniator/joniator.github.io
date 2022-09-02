# Example

```yml title=docker-compose.yml
services:
  vscode:
    image: 'joniator/code-server:latest'
    volumes:
      # Uncomment if you want to access host docker
      # - '/var/run/docker.sock:/var/run/docker.sock'
      - 'vscode:/config'

volumes:
  vscode:
```