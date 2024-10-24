# 🎰 Euromilhões Web Service

Bem-vindo ao **Euromilhões Web Service**! Este serviço gera apostas aleatórias no formato do Euromilhões, facilitando o processo para quem quer tentar a sorte.

🌐 **Acesse o serviço aqui:**  
[Euromilhões Web Service](https://euromilhoes-42e1.onrender.com/)

---

## ✨ Funcionalidades

Este Web Service permite que você obtenha uma aposta aleatória composta de números e estrelas.  
Os números e estrelas são sorteados de forma completamente aleatória, respeitando as regras oficiais do Euromilhões.

### 📝 Exemplo de Resposta

Quando você faz uma solicitação `GET` para o serviço, ele retorna um JSON com a seguinte estrutura:

```json
{
  "numeros": [2, 14, 23, 34, 48],
  "estrelas": [3, 11]
}
