<h1 style="font-size: 19px; font-family: Arial; line-height: 1.15; fonte-weight:bold; border:none">
  🕵️ Script investigativo #01 – Investigue diretórios ocultos com Python
</h1>

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  🧠 Quer saber se um site está escondendo páginas ou diretórios importantes?
</h2>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
Descobrir manualmente é lento e ineficiente. É como procurar uma agulha no palheiro.  
A maioria dos sites revela mais do que deveria, se você souber onde procurar. Você precisa de um script ágil, direto e que explore caminhos comuns em segundos.  
O que será que está oculto... mas ninguém encontrou ainda?
</p>
---
<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  💡 O que esse script faz?
</h2>

<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- ✅ Acessa a URL base de um site  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- ✅ Testa uma wordlist com possíveis caminhos secretos  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- ✅ Mostra quais retornam código 200 (sucesso)  
</p>

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
 📄 Código dividido em blocos
</h2>

<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
  Para facilitar a leitura, o script está separado por blocos. Assim, você pode estudar trecho por trecho e adaptar com facilidade.
</p>

<h2 style="font-size: 14px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
- 📁 Imports
</h2>
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6de4ec500eaa9d1fdc6010573410694dc2e4c9ef/images/script_email_finder.py.png" alt="Imports" width="500">

<h2 style="font-size: 14px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
- ⚙️ Variáveis iniciais
</h2>
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6de4ec500eaa9d1fdc6010573410694dc2e4c9ef/images/script_email_finder_2.py.png" alt="Imports" width="500">

<h2 style="font-size: 14px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
- 🔁 Loop
</h2>
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6de4ec500eaa9d1fdc6010573410694dc2e4c9ef/images/script_email_finder_3.py.png" alt="Imports" width="500">

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
- ⏳ Execução  
</h2>

<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
```bash
python classificar_urls.py https://www.exemplo.com
```
</p>

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  🖥️ Exemplo de saída
</h2>

<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
```
[+] URLs internas encontradas:
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
  - https://www.exemplo.com/sobre
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
  - https://www.exemplo.com/contato
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
[+] URLs externas encontradas:
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
  - https://twitter.com/exemplo
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
  - https://linkedin.com/company/exemplo
```
</p>

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  🤔 Como usar?
</h2>

<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- ✏️ Altere o site para o alvo desejado  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 📃 Edite a wordlist com nomes mais prováveis  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- ▶️ Rode e veja o que está acessível  
</p>

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  ❓ Por que funciona?
</h2>

<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
Muitos sites deixam diretórios expostos por engano. Este script faz uma varredura rápida, simulando o trabalho de força bruta leve, e revela o que está oculto.
</p>

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
🧰 Útil para
</h2>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 🎯 Reconhecimento em pentests  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 🔍 Estudos de segurança e OSINT  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 🛠️ Auxiliar ferramentas que possuem scripts maiores  
</p>

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  📌 Dica bônus para melhorar o script
</h2>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 🏃 Use threading para acelerar a varredura  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 📃 Aplique wordlists profissionais (como a do SecLists)  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 📊 Integre com alertas visuais ou logs  
</p>

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  ⬇️ Quer baixar o script completo?
</h2>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
  📦 Está disponível em: [github.com/seuperfil/email-finder](https://github.com/seuperfil/email-finder)
</p>
---

<h2 style="font-size: 16px; font-family: Arial; line-height: 1.15; font-weight:bold; border:none">
  💾 Outros scripts investigativos
</h2>

<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 🖼️ Baixar todas as imagens de uma página  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 🔌 Verificar se um site está online (healthcheck por URL)  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 📊 Monitorar consumo de CPU/memória com alerta por e-mail  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 🔗 Extrair e classificar todos os links de um site  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 📄 Converter arquivos PDF para texto automaticamente  
</p>
<p style="font-size: 14px; font-family: Arial; line-height: 1.15; border:none">
- 🔐 Identificar portas abertas em uma faixa de IPs
</p>
