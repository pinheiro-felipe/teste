
# 🕵️ Script investigativo #01 – Investigue diretórios ocultos com Python

## 🧠 Quer saber se um site está escondendo páginas ou diretórios importantes?

Descobrir manualmente é lento e ineficiente. É como procurar uma agulha no palheiro.  
A maioria dos sites revela mais do que deveria, se você souber onde procurar. Você precisa de um script ágil, direto e que explore caminhos comuns em segundos.  
O que será que está oculto... mas ninguém encontrou ainda?

---

## 💡 O que esse script faz?

- ✅ Acessa a URL base de um site  
- ✅ Testa uma wordlist com possíveis caminhos secretos  
- ✅ Mostra quais retornam código 200 (sucesso)  

## 📄 Código dividido em blocos

Para facilitar a leitura, o script está separado por blocos. Assim, você pode estudar trecho por trecho e adaptar com facilidade.

- 📁 Imports
        ![Minha imagem](https://raw.githubusercontent.com/pinheiro-felipe/teste/main/images/scritp_email_finder.py.png)
)
- ⚙️ Variáveis iniciais
        ![Descrição da imagem](https://raw.githubusercontent.com/pinheiro-felipe/teste/main/images/script_email_finder_2.py.png)
- 🔁 Loop
        ![Descrição da imagem](https://raw.githubusercontent.com/pinheiro-felipe/teste/main/images/script_email_finder_3.py.png)
- ⏳ Execução  

```bash
python classificar_urls.py https://www.exemplo.com
```

## 🖥️ Exemplo de saída

```
[+] URLs internas encontradas:
  - https://www.exemplo.com/sobre
  - https://www.exemplo.com/contato

[+] URLs externas encontradas:
  - https://twitter.com/exemplo
  - https://linkedin.com/company/exemplo
```

## 🤔 Como usar?

- ✏️ Altere o site para o alvo desejado  
- 📃 Edite a wordlist com nomes mais prováveis  
- ▶️ Rode e veja o que está acessível  

## ❓ Por que funciona?

Muitos sites deixam diretórios expostos por engano. Este script faz uma varredura rápida, simulando o trabalho de força bruta leve, e revela o que está oculto.

## 🧰 Útil para

- 🎯 Reconhecimento em pentests  
- 🔍 Estudos de segurança e OSINT  
- 🛠️ Auxiliar ferramentas que possuem scripts maiores  

## 📌 Dica bônus para melhorar o script

- 🏃 Use threading para acelerar a varredura  
- 📃 Aplique wordlists profissionais (como a do SecLists)  
- 📊 Integre com alertas visuais ou logs  

## ⬇️ Quer baixar o script completo?

📦 Está disponível em: [github.com/seuperfil/email-finder](https://github.com/seuperfil/email-finder)

---

## 💾 Outros scripts investigativos

- 🖼️ Baixar todas as imagens de uma página  
- 🔌 Verificar se um site está online (healthcheck por URL)  
- 📊 Monitorar consumo de CPU/memória com alerta por e-mail  
- 🔗 Extrair e classificar todos os links de um site  
- 📄 Converter arquivos PDF para texto automaticamente  
- 🔐 Identificar portas abertas em uma faixa de IPs
