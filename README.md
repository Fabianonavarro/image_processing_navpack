# 🖼️ Image Processing Navpack

Um projeto Python para processamento de imagens, utilizando bibliotecas como `scikit-image` e `imageio` para comparar, transformar e salvar imagens.

## 📁 Estrutura do Projeto

```plaintext
image_processing_navpack/
├─ .venv
│
├─── image_processing_navpack/
│    ├─── imgs/
│    │    ├── imagem1.jpg
│    │    └── imagem2.jpg
│    ├─── processing/
│    │    ├── __init__.py
│    │    ├── combination.py
│    │    └── transformation.py
│    ├─── utils/
│    │    ├── __init__.py
│    │    ├── io.py
│    │    └── plot.py
│    └─── tests/
│         ├── __init__.py
│         ├── test_processing.py
│         └── test_utils.py
├── pyproject.toml
├── test_image.py
└── README.md

🚀 Instalação

Clone o Repositório:
git clone https://github.com/Fabianonavarro/image-processing-navpack.git

Navegue para o Diretório do Projeto:
cd image-processing-navpack

Instale as Dependências Usando Poetry:
poetry install

Ative o Ambiente Virtual:
poetry shell

🛠️ Uso
Coloque suas Imagens no Diretório image_processing_navpack/imgs:

Execute o Script Principal para Processar as Imagens:

bash
Copiar código
poetry run python test_image.py
Resultados: Os resultados serão salvos no diretório image_processing_navpack/imgs com os seguintes nomes:

difference_image.jpg
histogram_matched_image.jpg
🧪 Testes
Para executar os testes, use o comando:

bash
Copiar código
poetry run pytest
📋 Contribuições
Sinta-se à vontade para abrir issues e pull requests para melhorias ou correções.

📜 Licença
Este projeto está licenciado sob a Licença MIT.

📚 Referências
Scikit-Image Documentation
ImageIO Documentation
csharp
Copiar código

### 3. Atualizar `test_image.py`

Caso tenha algum código que ainda esteja se referindo ao antigo nome do projeto, faça as seguintes alterações:

- **Atualize os imports** se houver alguma referência ao nome antigo do projeto.

```python
# Atualize quaisquer referências ao antigo nome do projeto, se existirem.
4. Publicar no PyPI
Certifique-se de que o novo nome está disponível no PyPI.

Construa os arquivos de distribuição:

bash
Copiar código
poetry build
Publique o pacote:

bash
Copiar código
poetry publish --build
Verifique a publicação acessando o PyPI e buscando pelo novo nome do pacote.