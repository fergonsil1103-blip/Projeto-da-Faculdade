# RentSmart — Sistema de Orçamento de Locação (R.M Imóveis)

Aplicação desenvolvida em Python utilizando Programação Orientada a Objetos (POO) para automatizar o cálculo de orçamentos de locação da **R.M Imóveis**, reduzindo erros manuais na aplicação de adicionais, descontos e parcelamento da taxa contratual.

## Funcionalidades

- Cálculo automatizado para **Apartamento**, **Casa** e **Estúdio**.
- Aplicação de adicionais de quartos (2 quartos em apartamentos e casas) e vagas de estacionamento/garagem.
- Desconto automático de **5%** no aluguel mensal para apartamentos onde o cliente não possui crianças.
- Exibição detalhada do orçamento mensal separada da **taxa contratual (R$ 2.000,00)** e seu parcelamento (1x a 5x).
- Validação de entradas no terminal para evitar opções inválidas.
- Exportação da projeção financeira dos **12 primeiros meses** em arquivo `.csv`.

## Estrutura da Pasta

- `rentsmart.py`: Código-fonte principal com as classes `Imovel`, `Apartamento`, `Casa`, `Estudio`, `OrcamentoLocacao` e `GeradorCSV`.
- `exemplo_projecao_12_meses.csv`: Exemplo de projeção de 12 meses gerada pelo sistema.
- `README.md`: Instruções de uso e documentação do projeto.

## Como Executar no VS Code

1. Extraia a pasta `rentsmart_rm_imoveis` e abra-a no **VS Code** (`File > Open Folder...`).
2. Abra o arquivo `rentsmart.py`.
3. Execute pelo botão **Run** ou no terminal integrado do VS Code:
   ```bash
   python rentsmart.py
   ```
4. Siga as instruções no terminal para gerar o orçamento e o arquivo `.csv`.
