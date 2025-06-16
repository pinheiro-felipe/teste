<div id="conteudo-markdown" style="max-width: 570px; margin: auto; word-wrap: break-word; line-height: 1.5; font-family:Arial, sans-serif">
  
<h1 style="font-size:32px; font-weight:bold; border-bottom:none!important">
  🕵️ Script investigativo #01 – Investigue diretórios ocultos com Python
</h1>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
  🧠 Quer saber se um site está escondendo páginas ou diretórios importantes?
</h2>

<p style="font-size:16px; text-align: justify;">
  Descobrir manualmente é lento e ineficiente. É como procurar uma agulha no palheiro.  
A maioria dos sites revela mais do que deveria, se você souber onde procurar. Você precisa de um script ágil, direto e que explore caminhos comuns em segundos.  
O que será que está oculto... mas ninguém encontrou ainda?
</p>

<hr>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
💡 O que esse script faz?
</h2>

<ul style="list-style:none!important; padding-left:40px">
  <li>✅ Acessa a URL base de um site</li>
  <li>✅ Testa uma wordlist com possíveis caminhos secretos</li>
  <li>✅ Mostra quais retornam código 200 (sucesso)</li>
</ul>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
📄 Código dividido em blocos
</h2>

<p style="font-size:16px; text-align: justify;">
  Para facilitar a leitura, o script está separado por blocos. Assim, você pode estudar trecho por trecho e adaptar com facilidade.
</p>

<h3 style="font-size:16px; padding-left:20px">
📁 Imports
</h3>
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6da0e70e59fae900f124e122acc27d5a22451c9a/images/script_email_finder.png" alt="Imports" width="500" style="padding-left:20px">

<h3 style="font-size:16px; padding-left:20px">
⚙️ Variáveis iniciais
</h3>
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6da0e70e59fae900f124e122acc27d5a22451c9a/images/script_email_finder_2.png" alt="Imports" width="500" style="padding-left:20px">

<h3 style="font-size:16px; padding-left:20px">
🔁 Loop
</h3>
<img src="https://raw.githubusercontent.com/pinheiro-felipe/teste/6da0e70e59fae900f124e122acc27d5a22451c9a/images/script_email_finder_3.png" alt="Imports" width="500" style="padding-left:20px">

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
⏳ Execução  
</h2>
<p style="font-size:16px; text-align: justify; padding-left:40px">
  python classificar_urls.py https://www.exemplo.com
</p>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
🖥️ Exemplo de saída
</h2>
<h3 style="font-size:16px; padding-left:20px">
[+] URLs internas encontradas:
</h3>
<ul style="font-size:16px; list-style:none!important; padding-left:40px">
  <li>- https://www.exemplo.com/sobre</li>
  <li>- https://www.exemplo.com/contato</li>
</ul>

<h3 style="font-size:16px; padding-left:20px; mrgin-top:10px">
[+] URLs externas encontradas:
</h3>
<ul style="font-size:16px; list-style:none!important; padding-left:40px">
  <li>- https://twitter.com/exemplo</li>
  <li>- https://linkedin.com/company/exemplo</li>
</ul>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
🤔 Como usar?
</h2>
<ul style="font-size:16px; list-style:none!important; padding-left:40px">
  <li>✏️ Altere o site para o alvo desejado</li>
  <li>📃 Edite a wordlist com nomes mais prováveis</li>
  <li>▶️ Rode e veja o que está acessível</li>
</ul>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
❓ Por que funciona?
</ul>
<p style="font-size:16px; text-align: justify; padding-left:40px">
Muitos sites deixam diretórios expostos por engano. Este script faz uma varredura rápida, simulando o trabalho de força bruta leve, e revela o que está oculto.
</p>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
🧰 Útil para
</h2>
<ul style="font-size:16px; list-style:none!important; padding-left:40px">
  <li>🎯 Reconhecimento em pentests</li>
  <li>🔍 Estudos de segurança e OSINT</li>
  <li>🛠️ Auxiliar ferramentas que possuem scripts maiores</li>
</ul>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
📌 Dica bônus para melhorar o script
</h2>
<ul style="font-size:16px; list-style:none!important; padding-left:40px">
  <li>🏃 Use threading para acelerar a varredura </li>
  <li>📃 Aplique wordlists profissionais (como a do SecLists)</li>
  <li>📊 Integre com alertas visuais ou logs </li>
</ul>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
⬇️ Quer baixar o script completo?
</h2>
<p style="font-size:16px; text-align: justify; padding-left:40px">
📦 Está disponível em: [github.com/seuperfil/email-finder](https://github.com/seuperfil/email-finder)
</p>

<hr>

<h2 style="font-size:24px; font-weight:bold; border-bottom:none!important">
💾 Outros scripts investigativos
</h2>
<ul style="font-size:16px; list-style:none!important; padding-left:40px">
  <li>🖼️ Baixar todas as imagens de uma página </li>
  <li>🔌 Verificar se um site está online (healthcheck por URL)</li>
  <li>📊 Monitorar consumo de CPU/memória com alerta por e-mail</li>
  <li>🔗 Extrair e classificar todos os links de um site</li>
  <li>📄 Converter arquivos PDF para texto automaticamente</li>
  <li>🔐 Identificar portas abertas em uma faixa de IPs</li>
</ul>

</div>
