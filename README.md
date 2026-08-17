# ⚡ Venci

> Aplicativo inteligente de gestão de contas e cobrança mútua com validação por comprovante e rastreamento de juros evitados.

---

## 🎯 Proposta de Valor

O **Venci** foi concebido para eliminar o atraso crônico no pagamento de contas de consumo (água, luz, internet, gás, etc.) decorrente de esquecimento (especialmente para pessoas com TDAH e casais). O app só cessa os alertas diários mediante o upload de um comprovante válido de pagamento e reforça a motivação financeira calculando os juros e multas economizados.

---

## 🚀 Principais Funcionalidades

- **Dashboard de Economia:** Exibe em tempo real o total acumulado em Reais (R$) de multas e juros evitados ao pagar no prazo.
- **Divisão de Visibilidade:**
  - **Contas da Casa (Compartilhadas):** Visíveis por ambos os membros, com indicação do responsável pela quitação.
  - **Minhas Contas (Privadas):** Visíveis exclusivamente para o usuário que cadastrou.
- **Cobrança Ativa:** Notificações persistentes no dia do vencimento até a quitação formal.
- **Validação por Comprovante:** Transição de status para `Pago` mediante upload de imagem/print via câmera ou galeria.

---

## 🛠️ Stack Tecnológica

- **Frontend Mobile:** [React Native](https://reactnative.dev/) com [Expo](https://expo.dev/) (TypeScript)
- **Design & Estilo:** [NativeWind](https://www.nativewind.dev/) / Tailwind CSS
- **Ícones:** [lucide-react-native](https://lucide.dev/)
- **Backend & Storage:** [Supabase](https://supabase.com/) (PostgreSQL & Supabase Storage)
- **Versionamento & Releases:** Semantic Release via GitHub Actions

---

## 📦 Padrão de Commits (Conventional Commits)

Este repositório utiliza **Semantic Release**. Todo commit deve seguir o formato:

`<tipo>(<escopo>): <descrição curta>`

### Tipos Válidos:
- `feat`: Nova funcionalidade (incrementa versão **MINOR**, ex: `1.0.0` -> `1.1.0`)
- `fix`: Correção de bug (incrementa versão **PATCH**, ex: `1.0.0` -> `1.0.1`)
- `docs`: Alterações na documentação
- `style`: Formatação, ponto e vírgula, espaços (sem alteração de código)
- `refactor`: Refatoração de código sem alterar regra de negócio
- `perf`: Melhoria de performance
- `chore`: Atualização de tarefas de build, configs ou dependências
- `BREAKING CHANGE`: No rodapé do commit ou com `feat!:`, incrementa versão **MAJOR** (`1.0.0` -> `2.0.0`)

### Exemplos:
- `feat(dashboard): adicionar card de economia de juros`
- `fix(upload): corrigir falha ao selecionar foto da galeria`
- `docs(readme): atualizar instruções de build nativo`

---

## 💻 Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/jeniferplacido/venci.git
   
   cd venci

2. Instale as dependências:

    ```bash
    npm install

3. Inicie o servidor Expo:

    ```bash
    npx expo start

---

