# ahp-mobile
Aplicativo mobile para aplicação do método AHP (Analytic Hierarchy Process), permitindo que usuários definam critérios, comparem alternativas par-a-par e obtenham o ranking final de decisão com cálculos automáticos de pesos e consistência, de forma simples, visual e acessível.

## 📌 Requisitos Funcionais — Aplicativo AHP

### 1. Gestão de Projetos
- **RF01** — Permitir criar um novo projeto de análise AHP.
- **RF02** — Permitir salvar, editar e excluir projetos.
- **RF03** — Permitir duplicar um projeto existente.
- **RF04** — Listar todos os projetos com status e data.

### 2. Definição da Hierarquia
- **RF05** — Definir o objetivo principal da análise.
- **RF06** — Cadastrar critérios.
- **RF07** — Cadastrar subcritérios (opcional).
- **RF08** — Cadastrar alternativas.
- **RF09** — Exibir a hierarquia em visualização gráfica (árvore).

### 3. Comparações Par-a-Par
- **RF10** — Comparar critérios par-a-par.
- **RF11** — Comparar subcritérios par-a-par (se existirem).
- **RF12** — Comparar alternativas para cada critério.
- **RF13** — Utilizar escala Saaty 1–9 nas comparações.
- **RF14** — Editar comparações já realizadas.
- **RF15** — Inferir automaticamente valores recíprocos.

### 4. Cálculo e Consistência
- **RF16** — Calcular matriz de prioridades locais.
- **RF17** — Calcular prioridades globais das alternativas.
- **RF18** — Calcular índice de consistência (IC).
- **RF19** — Calcular razão de consistência (RC).
- **RF20** — Alertar quando a consistência estiver fora do aceitável.
- **RF21** — Sugerir ajustes quando RC ultrapassar valor limite.

### 5. Resultados e Visualização
- **RF22** — Exibir ranking final das alternativas.
- **RF23** — Exibir gráficos (barras e pizza) para visualização de pesos.
- **RF24** — Exibir matrizes numéricas geradas.
- **RF25** — Exportar resultados (PDF, Excel, imagem) *(opcional)*.
- **RF26** — Comparar diferentes execuções do mesmo problema *(opcional)*.

### 6. Persistência e Sincronização
- **RF27** — Salvar automaticamente o progresso.
- **RF28** — Permitir backup local.
- **RF29** — Permitir login e sincronização em nuvem *(opcional)*.

### 7. Acessibilidade e Usabilidade
- **RF30** — Oferecer tutorial sobre o método AHP.
- **RF31** — Validar entradas inadequadas.
- **RF32** — Suportar uso offline para cálculos e edição.

### 8. Configurações
- **RF33** — Configurar idioma.
- **RF34** — Configurar escala alternativa (ex: 1–7).
- **RF35** — Configurar visualizações padrão.
