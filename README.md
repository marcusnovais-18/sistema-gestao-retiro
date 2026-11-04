# 🏕️ Sistema Web de Gestão para Retiro de Jovens (Acampamento Torre Forte)

Este é um projeto Full-Stack desenvolvido para resolver um problema real de gestão e organização financeira do grupo de jovens da minha igreja, substituindo processos manuais por um fluxo automatizado.

🔗 **Links do Projeto em Produção:**
* **Site de Inscrição (Público):** [https://retiroumaqq2027.netlify.app](https://retiroumaqq2027.netlify.app)
* **Painel de Controle (Admin):** [https://paineldecontroleretiro.netlify.app](https://paineldecontroleretiro.netlify.app)

## 🎯 O Problema de Negócio
Como tesoureiro do grupo, o processo de confirmação de presença e controle de pagamentos era feito inteiramente de forma manual pelo líder. O fluxo exigia enviar mensagens individuais no WhatsApp, anotar os retornos em blocos de notas e atualizar planilhas manualmente. Isso gerava gargalos, perda de informações e muito esforço operacional.

## 💡 A Solução e Arquitetura
Idealizei e estruturei uma solução baseada em dois sistemas que se comunicam em tempo real:

1. **Frontend de Inscrição:** Uma Landing Page onde o próprio jovem preenche seus dados, visualiza a infraestrutura do local e seleciona a forma de pagamento (Pix Parcelado, Cartão, etc.).
2. **Dashboard Financeiro (Admin):** Um painel de controle restrito à liderança. Ele lê os dados em tempo real e exibe uma tabela gerencial com o status de cada jovem (Pago Total, Pendente, etc.), facilitando a cobrança e a gestão de caixa.

## 🤖 Desenvolvimento e Uso de Inteligência Artificial
A arquitetura do sistema, as regras de negócio e a lógica de banco de dados foram idealizadas por mim. Para acelerar o desenvolvimento e ultrapassar bloqueios de sintaxe durante a escrita do código (visto que eu estava desenvolvendo a interface do zero), utilizei a **IA do Google Gemini** como um assistente de *pair-programming*. 

Eu fornecia a lógica estrutural e o Gemini me auxiliava na construção e refatoração dos blocos de HTML, CSS e na integração do JavaScript com o banco de dados.

## 🛠️ Tecnologias Utilizadas
* **Front-end:** HTML5, CSS3, JavaScript (Vanilla).
* **Banco de Dados (BaaS):** Firebase (Realtime Database) para registrar as inscrições e atualizar o painel de controle instantaneamente.
* **Deploy e Hospedagem:** Netlify (CI/CD simples para manter os dois sites no ar).
