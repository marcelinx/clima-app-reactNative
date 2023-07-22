# ClimaUI - Aplicativo de Clima

O ClimaUI é um projeto de aplicativo móvel desenvolvido em React Native que permite aos usuários obter informações sobre o clima de diferentes cidades. Este aplicativo utiliza dados mockados para simular a obtenção de informações climáticas em tempo real.

## Funcionalidades

- Exibir a previsão do tempo atual para uma cidade específica.
- Permitir ao usuário pesquisar outras cidades para obter suas respectivas previsões de clima.
- Apresentar informação detalhada sobre a previsão, como temperatura.

## Instalação

Siga as instruções abaixo para executar o ClimaApp em seu ambiente de desenvolvimento local:

1. Certifique-se de ter o ambiente React Native configurado em seu sistema. Se você ainda não o fez, siga as instruções da [documentação oficial do React Native](https://reactnative.dev/docs/environment-setup) para configurá-lo.

2. Clone este repositório para o seu sistema:

```bash
git clone https://github.com/seu-usuario/clima-app-reactNative.git
```

3. Acesse o diretório do projeto:

```bash
cd clima-app
```

4. Instale as dependências do projeto usando o npm ou o yarn:

```bash
npm install
```

ou

```bash
yarn install
```

5. Inicie o aplicativo no seu emulador ou dispositivo conectado:

```bash
npx react-native run-android
```

ou

```bash
npx react-native run-ios
```

## Uso

O ClimaApp é muito simples de usar. Ao iniciar o aplicativo, você verá a previsão do tempo para a cidade atual (dados mockados). Para verificar a previsão de outras cidades, clique na opção de pesquisa e digite o nome da cidade desejada. O aplicativo exibirá a previsão detalhada para essa cidade.

## Dados Mockados

O ClimaApp utiliza dados mockados para simular a obtenção de informações climáticas em tempo real. Esses dados não representam informações reais e são usados apenas para fins de demonstração. Caso deseje conectar o aplicativo a um serviço de previsão do tempo em tempo real, consulte a documentação para integrar a API de sua escolha.

## Contribuição

Se você quiser contribuir com este projeto, siga as etapas abaixo:

1. Faça um fork deste repositório.

2. Crie um branch para sua contribuição:

```bash
git checkout -b feature/sua-feature
```

3. Faça suas alterações e adições no código.

4. Commit suas mudanças:

```bash
git commit -m "Adicionar sua-feature"
```

5. Envie para o seu fork:

```bash
git push origin feature/sua-feature
```

6. Abra uma pull request no repositório original.

7. Aguarde a revisão e a aceitação da sua pull request. Se necessário, realize ajustes de acordo com o feedback recebido.
