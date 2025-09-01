Guia: Configurando o Ambiente Conda para o DRAMATIC VIDEO
Este guia irá orientá-lo passo a passo na criação de um ambiente Conda limpo e dedicado para executar o editor de vídeo. Usar um ambiente virtual é a melhor forma de garantir que todas as dependências funcionem corretamente, sem conflitos com outros projetos.

Pré-requisitos
Antes de começar, certifique-se de que tem o Anaconda ou o Miniconda instalado no seu sistema. Se não tiver, pode descarregá-lo a partir do site oficial do Anaconda.

Passo 1: Criar o Ambiente Conda
Abra o seu terminal (ou "Anaconda Prompt" no Windows) e execute o seguinte comando para criar um novo ambiente chamado dramatic-video-env com o Python 3.9. Esta versão é estável e compatível com todas as bibliotecas que vamos usar.

conda create --name dramatic-video-env python=3.9 -y

O -y no final aceita automaticamente todas as confirmações.

Passo 2: Ativar o Ambiente
Depois de criado, você precisa de "entrar" ou ativar o ambiente. Todos os comandos a partir de agora serão executados dentro dele.

conda activate dramatic-video-env

Você verá o nome do ambiente, (dramatic-video-env), a aparecer no início da linha do seu terminal

Passo 2: Ativar o Ambiente
Depois de criado, você precisa de "entrar" ou ativar o ambiente. Todos os comandos a partir de agora serão executados dentro dele.

conda activate dramatic-video-env

Você verá o nome do ambiente, (dramatic-video-env), a aparecer no início da linha do seu terminal.

Passo 3: Instalar as Dependências
Com o ambiente ativado, vamos instalar todas as bibliotecas Python necessárias com um único comando. Execute o seguinte no seu terminal:

pip install opencv-python Pillow numpy mediapipe auto-editor==29.0.5

Por fim inicie o programa com python dramatic3.py
