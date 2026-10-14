# Juris Memória

Plataforma de estudo para concursos da magistratura estadual e federal, em um único arquivo HTML, com IA do Google Gemini.

## O que faz

- Legislação: cole leis ou artigos (sem limite). A IA oculta os pontos que as bancas exploram (prazos, quóruns, órgãos, exceções, verbos de dever/faculdade) e você revisa por repetição espaçada, como no Anki. Há também lacunas automáticas sem IA e edição manual com `{{trecho::dica}}`.
- Questões: Verdadeiro/Falso ou múltipla escolha no estilo FGV, FCC, VUNESP ou CEBRASPE, na quantidade que escolher, a partir de artigos, de materiais ou de tema livre. Cada questão traz comentário, análise das alternativas e o trecho que fundamenta o gabarito, conferido automaticamente na fonte.
- Materiais: PDF, DOCX ou TXT (PDF digitalizado pode ser transcrito pela IA). Gera questões, flashcards, pontos de prova e responde perguntas com indicação de página.
- Treino e simulado cronometrado, caderno de erros, riscar alternativas, impressão de cadernos com gabarito comentado.
- Discursivas de segunda fase com espelho, resposta modelo e correção pela IA.
- Estatísticas por disciplina e banca, constância diária, backup/importação em JSON.

## Publicar no GitHub Pages

1. Crie um repositório (pode ser privado em planos pagos; público no gratuito) e envie todos os arquivos desta pasta: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`.
2. Em Settings › Pages, escolha a branch `main` e a pasta `/ (root)`.
3. Abra o endereço `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.
4. No iPhone/iPad (Safari): Compartilhar › Adicionar à Tela de Início.

## Chave do Gemini

Crie em https://aistudio.google.com/apikey e cole em Ajustes. A chave fica só no navegador de cada aparelho e nunca vai para o repositório nem para o backup. Recomenda-se restringir a chave, no Google Cloud, à "Generative Language API" e ao endereço do seu site.

## Dados

Tudo fica no armazenamento local (IndexedDB) de cada aparelho; não há sincronização automática. Para levar os dados do computador para o tablet, use Ajustes › Exportar backup e, no outro aparelho, Importar backup. Faça backup semanal: o Safari pode apagar dados de sites não usados por várias semanas.
