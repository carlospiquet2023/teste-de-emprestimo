# Gestor Financeiro de Empréstimos

Um sistema web para gestão de empréstimos e clientes.

## Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/carlospiquet2023/teste-de-emprestimo.git
   cd teste-de-emprestimo
   ```

2. Configure suas chaves da API JSONBin:
   - Abra o arquivo `config.js`
   - Substitua `'SUA_MASTER_KEY_AQUI'` pela sua chave master real
   - Substitua `'SUA_ACCESS_KEY_AQUI'` pela sua chave de acesso real

3. Abra o `index.html` no navegador para usar o sistema.

## Segurança

- O arquivo `config.js` contém chaves sensíveis e está no `.gitignore`
- Nunca commite chaves reais no repositório
- Mantenha suas chaves seguras e não as compartilhe

## Funcionalidades

- Dashboard financeiro
- Gestão de clientes
- Controle de empréstimos
- Sincronização na nuvem (JSONBin)
- Exportação de dados (Excel, PDF)