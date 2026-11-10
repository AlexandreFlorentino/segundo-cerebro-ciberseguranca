# 🧠 Segundo Cérebro: Especialista em Cibersegurança

Este repositório documenta a criação de um "Segundo Cérebro" utilizando o Gemini Notebook (Google NotebookLM), desenvolvido como desafio prático para o curso de Cibersegurança da DIO.

## 🎯 Objetivo do Projeto
Criar um segundo cérebro especializado em Cibersegurança (focando em redes, sistemas operacionais, análise de malware e exploração), atuando como um mentor técnico rigoroso que baseia suas respostas exclusivamente em documentações oficiais, frameworks da indústria (MITRE, NIST) e análises práticas de engenharia reversa.

## 📚 Fontes Utilizadas e Critérios de Confiança
Para garantir uma base de conhecimento livre de ruídos e com alto rigor técnico, as fontes foram selecionadas sob 4 critérios: **Autoridade, Densidade de Informação, Temporalidade e Reprodutibilidade**. O notebook atingiu o limite de fontes de alta qualidade (50 fontes), englobando:

1. **IETF RFCs e NIST SP 800:** Fundamentos de redes e governança técnica.
2. **MITRE ATT&CK Framework:** Padrão global para mapeamento de TTPs de adversários.
3. **CISA Malware Analysis Reports:** Relatórios técnicos governamentais com dissecação de ameaças ativas.
4. **Google Project Zero e OWASP:** Referências em pesquisa de vulnerabilidades zero-day e segurança de aplicações.
5. **LiveOverflow (45+ vídeos):** Transcrições técnicas densas focadas em exploração de binários, arquitetura de computadores e corrupção de memória.

## ⚙️ Diretriz de Comportamento (System Prompt)
A seguinte diretriz foi configurada no notebook para moldar o comportamento da IA:
> "Comporte-se como um Engenheiro de Cibersegurança Sênior e Instrutor Técnico. Seu objetivo é me ajudar a estudar redes, sistemas operacionais e análise de ameaças. Regras inegociáveis: 1) Baseie suas respostas estritamente nas fontes fornecidas. 2) Seja direto, técnico e utilize jargões da área. 3) Se uma fonte apresentar um comando, log ou prova de conceito (PoC), mostre-o na explicação. 4) Nunca invente informações."

## 💬 Interações, Respostas e Validação
Durante a interação, o modelo conseguiu sintetizar a arquitetura e ataques de baixo nível comprovando a leitura das fontes adicionadas:

* **Tópico 1: Arquitetura de Kernel e Syscalls** 
A IA explicou com precisão os mecanismos de transição de Ring 3 (Userland) para Ring 0 (Kernel), tratamento de sinais (`SIGSEGV`) e inspeção de core dumps usando `gdb`. *(Citações geradas e documentadas nas evidências)*.

* **Tópico 2: Engenharia Reversa e Exploração (Binary Exploitation)** 
O notebook extraiu conceitos profundos dos vídeos do LiveOverflow, explicando métodos de bypass para Stack Canaries, vulnerabilidades de *Format String* para sobrescrever a Global Offset Table (GOT) e técnicas de *Heap Exploitation* (como o Use-After-Free).

* **Tópico 3: Inteligência contra Ameaças (Threat Intel)** 
A IA mapeou frameworks de referência (MITRE ATT&CK e OWASP) para analisar vetores de ataque evasivos, citando casos práticos baseados em abuso de credenciais e supply chain attacks.

## 🔗 Link do Notebook Compartilhado
[https://notebook.google.com/notebook/483d27f0-5e30-4df5-bd17-583627dc2a92]


