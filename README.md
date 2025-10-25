# 🚢 Hello, Captain! – Projeto Docker

Este é um projeto Docker simples que demonstra como criar uma imagem mínima que imprime uma mensagem no console e encerra em seguida.

---

## 📋 Requisitos do Projeto

- O arquivo deve se chamar **`Dockerfile`**.
- O **Dockerfile** deve estar no **diretório raiz** do projeto.
- A imagem base deve ser **`alpine:latest`**.
- Quando a imagem Docker for executada, ela deve imprimir a mensagem: Hello, [seu_nome]!
- Obs: o nome tem quer ser alterado no Dockerfile no comando ENV.

### 📋 Copie e cole no seu terminal:

```bash
docker build -t docker-test .
docker run --rm docker-test
```

### Link do Repositório
https://github.com/matheus-estevam/docker-test
