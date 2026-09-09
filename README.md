# Manual do professor: ensinar pesquisa com os manuais (MirandasTech)

Manual em formato de slides (42) para quem ensina metodologia e pesquisa científica: princípios (alinhamento construtivo, aprendizagem ativa, orientação explícita, feedback, peer instruction — referências verificadas), a série MirandasTech como material didático (hub, 14 manuais, plugin com a pasta do projeto, licença CC BY 4.0 e como citar), o plano de ensino com cronograma de 15 semanas ligado aos manuais e às entregas com evidência (`plano_de_ensino.py`), rubricas por entrega em que o arquivo prova o nível (`rubrica.py`), painel da turma lido dos `PROGRESSO.md` (`turma_progresso.py`), regras de uso de IA na disciplina, ambientes (Google Sala de Aula, Moodle, H5P, LibreOffice; GitHub Classroom descontinuado) e o estágio de docência (Portaria CAPES 76/2010); erros comuns, checklist, glossário com popovers e referências. Capturas reais e datadas (09/09/2026) sem login; nenhuma turma real foi usada; o PPC e o regimento prevalecem.

**Manual on-line:** https://professor.mirandastech.com.br/ · **PDF:** https://professor.mirandastech.com.br/manual.pdf

Manuais irmãos: **Manual do orientador** — https://orientador.mirandastech.com.br/ · **Defesa e qualificação** — https://defesa.mirandastech.com.br/ · **Ciência aberta** — https://cienciaaberta.mirandastech.com.br/ · **Bibliometria** — https://bibliometria.mirandastech.com.br/ · **Análise de dados** — https://dados.mirandastech.com.br/ · **Git e GitHub** — https://git.mirandastech.com.br/ · **LaTeX** — https://latex.mirandastech.com.br/ · **Busca em bases** — https://busca.mirandastech.com.br/ · **Revisão sistemática com PRISMA 2020** — https://prisma.mirandastech.com.br/ · **Zotero** — https://zotero.mirandastech.com.br/ · **Metodologia** — https://metodologia.mirandastech.com.br/ · **Gemini Notebook** — https://notebook.mirandastech.com.br/ · **Uso de IA na pesquisa** — https://manual.mirandastech.com.br/ · **Plugin Pesquisa** — https://plugin.mirandastech.com.br/ · Hub: https://www.mirandastech.com.br/pesquisa

| Pasta | O que há |
|---|---|
| `manual/` | deck HTML autônomo, PDF, fonte do artefato e `fatos_verificados.md` (fontes e execuções conferidas em 09/09/2026) |
| `site/` | o que o servidor serve (`index.html`, `manual.pdf`) |
| `capturas/` | 19 capturas reais, 09/09/2026 (páginas públicas; 3 figuras de terminal com saídas reais) |
| `scripts/plano_de_ensino.py` | plano de ensino com cronograma semana a semana ligado aos manuais e às entregas |
| `scripts/rubrica.py` | rubricas por entrega (projeto, busca, análise, texto, banca ou personalizada) com o arquivo que prova cada nível |
| `scripts/turma_progresso.py` | painel da turma a partir dos `PROGRESSO.md` de cada estudante |
| `scripts/gerar_deck.py` | regenera HTML e PDF a partir do fonte |
| `skills/ensino-pesquisa/` | skill do agente (cópia sincronizada do plugin Pesquisa MirandasTech) |
| `Dockerfile` · `Caddyfile` · `railway.json` | deploy estático (Caddy) |
| `.github/workflows/verificar.yml` | CI: integridade do deck e capturas referenciadas |

## Os manuais juntos
Este manual é o **lado do professor** da série: cada semana do cronograma aponta um manual e uma entrega com evidência; a avaliação confere o arquivo; o estudante trabalha na pasta do projeto criada pelo plugin **Pesquisa MirandasTech**, e a skill `ensino-pesquisa` monta plano, rubricas e painel — notas, critérios e PPC são do professor e da instituição.

## Como citar
MATIAS, J. P. M. *Manual do professor: ensinar pesquisa com os manuais.* MirandasTech, v1.0, set. 2026. CC BY 4.0.

## Declaração de uso de IA
Escrito com assistência de IA (Claude, Anthropic) na estruturação, redação, automação das capturas e execução dos scripts. Fatos conferidos em páginas públicas e no Crossref em 09/09/2026 (lista em `manual/fatos_verificados.md`); nenhuma captura com login; nenhuma turma real foi usada. O autor responde integralmente pelo conteúdo. CAPES, CNPq, as universidades citadas, Google, Moodle, H5P, The Document Foundation, GitHub, Springer e os demais serviços citados são marcas, órgãos e projetos de terceiros; este manual não tem vínculo com eles.