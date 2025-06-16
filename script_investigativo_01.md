<h1 style="font-size: 17px; font-family: Arial; line-height: 1.15; fonte-weight:bold; border:none">
  🕵️ Script investigativo #01 – Investigue diretórios ocultos com Python
</h1>

<h2 style="font-size: 14px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  🧠 Quer saber se um site está escondendo páginas ou diretórios importantes?
</h2>
<p style="font-size: 12px; font-family: Arial; line-height: 1.15; border:none">
Descobrir manualmente é lento e ineficiente. É como procurar uma agulha no palheiro.  
A maioria dos sites revela mais do que deveria, se você souber onde procurar. Você precisa de um script ágil, direto e que explore caminhos comuns em segundos.  
O que será que está oculto... mas ninguém encontrou ainda?
</p>
---
<h2 style="font-size: 14px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  💡 O que esse script faz?
</h2>

<p style="font-size: 12px; font-family: Arial; line-height: 1.15; border:none">
- ✅ Acessa a URL base de um site  
- ✅ Testa uma wordlist com possíveis caminhos secretos  
- ✅ Mostra quais retornam código 200 (sucesso)  
</p>

## 📄 Código dividido em blocos

Para facilitar a leitura, o script está separado por blocos. Assim, você pode estudar trecho por trecho e adaptar com facilidade.

- 📁 Imports
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6de4ec500eaa9d1fdc6010573410694dc2e4c9ef/images/script_email_finder.py.png" alt="Imports" width="475">
  
- ⚙️ Variáveis iniciais
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6de4ec500eaa9d1fdc6010573410694dc2e4c9ef/images/script_email_finder_2.py.png" alt="Imports" width="475">
  
- 🔁 Loop
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6de4ec500eaa9d1fdc6010573410694dc2e4c9ef/images/script_email_finder_3.py.png" alt="Imports" width="475">
  
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
