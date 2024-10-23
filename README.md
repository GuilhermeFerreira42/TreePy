# TreePy

TreePy é um analisador de código Python que utiliza a biblioteca `tkinter` para criar uma interface gráfica. Ele permite que o usuário abra arquivos de código (Python, TXT, HTML) e gera uma árvore binária que exibe onde cada função e variável são declaradas.

## Funcionalidades

- Abrir arquivos de diferentes formatos (.py, .txt, .html)
- Gerar uma árvore binária das declarações de funções e variáveis
- Escolher o nível de detalhes da árvore (Nível 1, 2 ou 3)
- Funções de copiar, colar, selecionar tudo e limpar na interface gráfica

## Níveis de Detalhe

- **Nível 1**: Apenas funções principais.
- **Nível 2**: Funções principais e variáveis.
- **Nível 3**: Funções, variáveis e detalhes adicionais.

## Capturas de Tela

![Captura de Tela 1](path/to/screenshot1.png)
![Captura de Tela 2](path/to/screenshot2.png)

## Instalação

1. Clone este repositório:
    ```bash
    git clone https://github.com/GuilhermeFerreira42/TreePy.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd TreePy
    ```
3. Instale as dependências necessárias:
    ```bash
    pip install tk
    ```

## Uso

1. Execute o script principal:
    ```bash
    python treepy.py
    ```
2. Use a interface gráfica para abrir um arquivo e visualizar a árvore binária.

## Contribuição

1. Fork este repositório.
2. Crie uma branch com a sua feature: `git checkout -b minha-feature`
3. Commit suas mudanças: `git commit -m 'Adiciona minha feature'`
4. Faça o push para a branch: `git push origin minha-feature`
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Créditos

Este projeto foi desenvolvido com a ajuda do Copilot da Microsoft.
