# ScannerExpert – Deep Scan de Sistema

Este projeto foi desenvolvido como parte da **Missão 03 – Operação Deep Scan**, da disciplina de **IHC / UX**.

## 🎯 Objetivo

Demonstrar na prática a **1ª Heurística de Nielsen: Visibilidade do Status do Sistema**.

Essa heurística afirma que o sistema deve sempre manter o usuário informado sobre o que está acontecendo, através de feedback claro e em tempo razoável.

## 🖥️ Funcionamento do Projeto

O programa simula uma **varredura de sistema (Deep Scan)** executando várias etapas:

* Verificação de CPU
* Leitura de memória RAM
* Sincronização de SDK
* Validação de permissões
* Finalização do processo

Durante a execução, o sistema exibe mensagens de **[PROCESSANDO]**, indicando ao usuário que a operação está em andamento.

Para simular o tempo de processamento, o programa utiliza:

Thread.Sleep()

Esse comando cria pausas entre as etapas, permitindo visualizar o progresso da análise.

## 🧠 Aplicação da Heurística de Nielsen

O sistema informa constantemente o status do processo, evitando que o usuário pense que o programa travou ou parou de funcionar.

Isso melhora a **experiência do usuário (UX)**, pois:

* reduz a ansiedade do usuário
* aumenta a confiança no sistema
* torna o processo mais claro e compreensível

## 📸 Evidência

O repositório contém a imagem **[minha-evidencia.png](https://github.com/vivoeasy100/una-ihcux-lista03/blob/main/Captura%20de%20tela%202026-03-13%20030219.png)**, que mostra o terminal durante a execução da varredura.

Essa evidência demonstra o feedback visual do sistema enquanto o processo está sendo executado.

## ⚙️ Tecnologias utilizadas

* .NET Console Application
* C#
* Visual Studio Code
* Terminal / CLI

## 🚀 Execução

Para executar o projeto:

```
dotnet run
```

O programa iniciará a simulação da análise do sistema e exibirá o progresso em tempo real no terminal.
