# 🛠️ Gerador de Scripts de Atendimento – Lanlink

Este projeto foi criado para agilizar e padronizar mensagens utilizadas no atendimento técnico do Service Desk da Lanlink.  
A ferramenta gera scripts automáticos para diferentes situações de suporte, mantendo consistência, clareza e linguagem profissional.

---

## 🚀 Funcionalidades

- ✔️ Geração automática de textos completos para cada tipo de atendimento  
- ✔️ Preenchimento dinâmico com dados do usuário (nome, horário, chamado etc.)  
- ✔️ Padronização da comunicação seguindo modelo corporativo  
- ✔️ Botão de cópia automática para agilizar o trabalho  
- ✔️ Interface simples, rápida e leve  

---


---

## 🧩 Scripts Disponíveis

**1. Abertura de Chamado**  
Gera o texto padrão ao registrar um chamado novo.

**2. Encaminhamento para Setor Responsável**  
Mensagem utilizada para avisar o usuário sobre transferência da demanda.

**3. Normalização de Sistema / Resolução**  
Scripts para informar que o incidente foi resolvido.

**4. Pendência de Informações**  
Solicitação de dados faltantes.

**5. Sistema Instável / Intermitência**  
Mensagem padronizada sobre oscilações.

**6. Agendamento de Atendimento**  
Texto para combinar horário com o usuário.

**7. Status Atualizado do Chamado**  
Informa andamento e próximos passos.

**8. Tentativa de Contato com o Usuário**  
Gera mensagem automática quando o usuário não atende.

---

## 🧠 Como Funciona

Cada botão no formulário chama uma função JS que:

1. Lê os valores dos campos (nome, data, chamado etc.)
2. Valida se todos foram preenchidos
3. Monta o texto usando template strings (``)
4. Insere o resultado em um textarea
5. Copia automaticamente para a área de transferência

Simples. Rápido. Sem drama.

---

## 🖥️ Tecnologias Utilizadas

- **HTML5**  
- **CSS3**  
- **JavaScript (Vanilla)** – sem frameworks  
- **DOM API** para manipulação dinâmica  
- **Template Literals** para montagem de mensagens  

---

## 🛡️ Boas Práticas Implementadas

- Validação de campos obrigatórios  
- Separação de funções por contexto  
- Código limpo e direto  
- Textos revisados para eliminar ambiguidades  
- Consistência entre todos os scripts  

---
## Antes
![imagem](https://github.com/BrunoAmericano/script-lanlink/blob/main/Screenshot_6.png?raw=true)

## Depois
![imagem](https://github.com/BrunoAmericano/script-lanlink/blob/main/Screenshot_7.png?raw=true)
