# Automação de Testes com Robot Framework

## Sobre o Projeto

Este projeto de automação de testes foi desenvolvido utilizando o Robot Framework, uma ferramenta de automação de testes de aceitação de código aberto que permite a utilização da metodologia BDD (Behavior-Driven Development). O foco dos testes é assegurar a qualidade e o correto funcionamento das funcionalidades de um site de gestão de colaboradores.

## Estrutura do Projeto

O projeto está estruturado da seguinte maneira:

- `resources/`: Contém os recursos compartilhados, como bibliotecas e arquivos de configuração.
- `testes/`: Diretório que contém os casos de teste escritos em um formato legível e estruturado.
- `results/`: Pasta destinada aos relatórios e logs gerados após a execução dos testes.

## Tecnologias Utilizadas

- **Robot Framework:** Framework de automação que utiliza a sintaxe de dados tabulares para definir casos de teste.
- **SeleniumLibrary:** Biblioteca do Robot Framework para testes de interfaces web através do Selenium.
- **FakerLibrary:** Biblioteca para a geração de dados fictícios, facilitando a criação de cenários de teste variados.

## Metodologia de Teste

Os testes foram escritos seguindo o padrão BDD, que permite descrever o comportamento do sistema de forma clara e objetiva. Cada caso de teste é composto por:

- **Given (Dado):** Estado inicial do sistema antes do teste ser executado.
- **When (Quando):** Ação ou evento que desencadeia o teste.
- **Then (Então):** Resultado esperado ou a confirmação de que o sistema se comportou como esperado.

## Casos de Teste

Os casos de teste cobrem diversas funcionalidades do sistema, incluindo:

- Validação de formulários e campos obrigatórios.
- Criação e gerenciamento de registros de colaboradores.
- Verificação de mensagens de erro e feedback ao usuário.
- Testes de interface para garantir a consistência visual e funcional.

## Execução dos Testes

Para executar os testes, é necessário ter o Robot Framework e as dependências necessárias instaladas. Os testes podem ser executados com o comando:

```bash
robot -d ./results testes/
```



Relatórios e Logs
Após a execução dos testes, são gerados relatórios detalhados em HTML e logs que ajudam na identificação de falhas e na análise dos resultados dos testes.

Contribuição
Contribuições para a melhoria dos casos de teste ou para a expansão da cobertura de testes são bem-vindas. Por favor, siga as diretrizes de contribuição do projeto.

Licença
Este projeto está licenciado sob a Licença MIT, permitindo uso, cópia, modificação e distribuição do código-fonte.

Para mais informações, consulte os arquivos individuais de teste e recursos no repositório. Este README será atualizado conforme o projeto evolui e novas técnicas são implementadas.

