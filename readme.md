# IFairC - Sorteio e Cronômetro para Debates

Esta aplicação interativa torna organização e a condução de um debate muito mais centralizada, fácil, ágil e transparente. Permite realizar sorteios dos nomes dos participantes e de temas, por ordem, além de oferecer funcionalidades de cronômetro ampliado para gestão transparente e pública de tempo. Foi desenvolvido em Python com interface gráfica baseada em Tkinter. 

## Funcionalidades

- **Sorteio de Nomes**: Seleção aleatória de nomes a partir de uma lista configurável.
- **Sorteio de Temas**: Escolha aleatória de temas pré-configurados em um arquivo externo.
- **Cronômetro**:
  - Opções de tempo de 1, 2 ou 5 minutos.
  - Botão para adicionar 10 segundos ao tempo.
  - Opção de pausar e continuar o cronômetro.
  - Alerta sonoro ao término do tempo.
- **Interface Intuitiva**:
  - Listas de seleção para personalizar sorteios.
  - Visualização clara do cronômetro.

## Requisitos

- Python 3.x (com suporte ao módulo Tkinter)


## Atualize o arquivo config.json com os nomes e temas desejados:
{
    "names": ["Alice", "Bob", "Carlos"],
    "themes": ["Tema 1", "Tema 2", "Tema 3"]
}

# Como Usar
## Sorteio de Nomes
- Abra o aplicativo.
- Escolha ou desmarque nomes para inclusão no sorteio.
- Clique em "Sortear Nome" para exibir o nome escolhido aleatoriamente.
## Sorteio de Temas
Selecione "Sortear Tema" para gerar um tema aleatório.
Visualize os temas já sorteados na lista.
## Cronômetro
- Escolha um dos tempos pré-definidos (1, 2 ou 5 minutos).
- Clique em "Iniciar" para começar a contagem regressiva.
- Use os botões "Pausar", "Continuar" ou "Adicionar 10s" conforme necessário.
## Tecnologias Utilizadas
- Python
- Tkinter (interface gráfica)
- JSON (armazenamento de dados configuráveis)
## Contribuindo
Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias ou correções.

## Estrutura do Projeto
- ├── app.py          # Código principal da aplicação
- ├── config.json     # Arquivo de configuração (nomes e temas)
- └── README.md       # Documentação do projeto

## Licença
Este projeto está sob a licença MIT.