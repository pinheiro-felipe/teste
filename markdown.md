# 🧠 Investigador Hacker

Scripts para investigação, automação e reconhecimento em segurança da informação.

---

## 💡 1. Kit de Reconnaissance Hacker — _"Mapeie o alvo em minutos"_

### 📦 O que contém:

| Script                      | Descrição                                              |
|----------------------------|--------------------------------------------------------|
| descobrir_subdominios.py   | brute force + APIs públicas                            |
| scan_portas_rapido.py      | scan leve com validação de serviços (banner grab)      |
| detectar_painel_admin.py   | tenta caminhos comuns + heurística (404 vs redirect)   |
| coletar_metadados_urls.py  | varre URLs e extrai headers, title, códigos            |

### 🎯 Público:

Pentesters iniciantes ou avançados que querem ganhar tempo na enumeração inicial.  
Gente que já sabe fazer na mão, mas quer automatizar sem depender do recon-ng ou outras suítes pesadas.

### 💰 Posicionamento para venda:

Você faz recon manualmente toda vez?  
Esse kit te entrega automações enxutas e ajustáveis, com foco no essencial: descobrir o que está exposto, sem ruído.  
Scripts comentados, prontos para personalização, com lógica validada por quem realmente testa ambientes.

---

## 💡 2. Kit de Monitoramento Local — _"Hacker do seu próprio PC"_

### 📦 O que contém:

| Script                      | Descrição                                              |
|----------------------------|--------------------------------------------------------|
| monitor_processos_suspeitos.py | detecta execuções estranhas e alertas            |
| watchdog_diretorios.py         | avisa sobre modificações em tempo real           |
| dump_memoria_simples.py       | coleta dumps e analisa strings/processos          |
| resumo_sistema.py             | snapshot leve com informações críticas da máquina  |

### 🎯 Público:

- Pessoas técnicas e curiosas  
- Sysadmins e devs paranoicos que querem saber o que acontece em tempo real  
- Alunos que estudam forense, mas não querem depender de Volatility ou ferramentas pesadas

### 💰 Posicionamento para venda:

Você sabe o que está rodando agora na sua máquina?  
Com esses scripts você se torna seu próprio analista: recebe alertas, captura pistas e começa sua própria análise forense com Python puro.

---

## 💡 3. Kit de Análise de Sites e Classificação de Risco — _"Seu scanner silencioso"_

### 📦 O que contém:

| Script                      | Descrição                                              |
|----------------------------|--------------------------------------------------------|
| coletar_urls_site.py        | varre o site e extrai todas as URLs internas          |
| classificar_urls.py         | atribui risco com base em padrões (admin, php, backup)|
| extrair_forms_vulneraveis.py| encontra formulários e verifica método e campo suspeitos|
| header_checker.py           | analisa headers de segurança (CSP, XSS, etc)          |

### 🎯 Público:

- Profissionais de bug bounty  
- Desenvolvedores preocupados com exposição  
- Estudantes que querem praticar análise passiva

### 💰 Posicionamento para venda:

Um pequeno scanner web feito em Python, ajustado para quem quer investigar silenciosamente um site e descobrir pontos sensíveis antes mesmo de pensar em um ataque.

---

