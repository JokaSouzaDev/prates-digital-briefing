# Prates Digital — Briefing de Landing Page

Formulário responsivo de briefing para projetos de landing page da Prates Digital.

## Site publicado

https://prates-digital-briefing.joka22092008.chatgpt.site

O GitHub guarda o código. A hospedagem atual continua no endereço acima; este repositório não ativa GitHub Pages nem sincronização automática com a hospedagem.

## Funcionalidades

- 9 etapas com 54 campos, incluindo campos condicionais.
- Validação dos campos obrigatórios e revisão antes de enviar.
- Upload opcional de fotos e materiais, com limite total conservador de aproximadamente 9 MB.
- Rascunho salvo manualmente apenas no navegador do usuário; arquivos precisam ser selecionados novamente.
- Download das respostas em TXT.
- Envio das respostas pelo FormSubmit para o endereço configurado no HTML.

## Arquivos

- `index.html`: estrutura, identidade visual e destino do formulário.
- `app.js`: perguntas, navegação, validação, revisão e rascunhos.

## Executar localmente

Execute `python -m http.server 8000` na pasta e abra http://localhost:8000. Não abra apenas como arquivo local para testar o envio.

## E-mail e dados

O FormSubmit exige ativação do endereço de destino. A ativação da hospedagem atual foi confirmada em 15/10/2026. Após trocar o domínio ou o destino, verifique se uma nova ativação é solicitada e teste o recebimento.

O formulário envia dados e anexos ao FormSubmit. Respostas de clientes não são gravadas neste repositório. Não adicione dados de clientes, senhas, anexos recebidos ou tokens ao GitHub. Não existe banco de dados próprio neste projeto.

Não há garantia de hospedagem ou serviço de envio vitalícios. O funcionamento depende das condições e disponibilidade dos fornecedores. Guarde os e-mails e anexos recebidos.

## Atualizações

Alterações neste repositório não são publicadas automaticamente no site atual. Faça uma nova publicação na hospedagem ao atualizar o código.
