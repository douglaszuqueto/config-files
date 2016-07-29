# Docker

## Instalação

  ```shell
  curl -sSL https://get.docker.com | sh
  ```

## Configuração
 * Adicione seu usário ao grupo do Docker

    ```shell
    sudo usermod -aG docker seuUsuário
    ```

## Testando
 * Versão

    ```shell
    docker -v
    ```
 * Hello World

    ```shell
    docker run ubuntu /bin/echo 'Hello world'
    ```