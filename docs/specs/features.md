---
category: Documento de Requisitos
description: Requisitos funcionais e Requisitos Não Funcionais
---

# Requirements Specification

**scope:** diagramas UML e DER

## 1. Functional Requirements

### RF1
* **short-description:** Detectar diagramas e associar cada ocorrência ao momento correspondente da videoaula.
* **long-description:** Detectar diagramas e associar cada ocorrência ao momento correspondente da videoaula.
* **acceptance-criteria:** Comparar regiões, tipos e momentos detectados com anotações de referência, registrar omissões, falsos positivos e associações temporais incorretas

### RF2
* **short-description:** Gerar descrições dos diagramas que identifiquem componentes, relacionamentos e propriedades relevantes.
* **long-description:** Gerar descrições dos diagramas que identifiquem componentes e explicitem seus relacionamentos e propriedades relevantes, como cardinalidades e multiplicidades, quando legíveis e aplicáveis.
* **acceptance-criteria:** Conferir proposições da descrição contra o diagrama, distinguindo erros de elemento, relação, direção e propriedade. Não trocar classe por entidade nem completar cardinalidades por suposição.

### RF3
* **short-description:** Disponibilizar o conteúdo descritivo como texto acessível e por síntese de voz, mantendo correspondência entre os dois formatos.
* **long-description:** Disponibilizar o conteúdo descritivo como texto acessível e por síntese de voz, mantendo correspondência entre os dois formatos.
* **acceptance-criteria:** Verificar acesso pelo leitor de tela e reprodução em voz; conferir se o áudio comunica o mesmo conteúdo textual, incluindo nomes, números e símbolos verbalizados.

### RF4
* **short-description:** Permitir interromper e repetir a descrição e retomar a videoaula, com apresentação que evite a sobreposição entre a explicação e a fala do instrutor.
* **long-description:** Permitir interromper e repetir a descrição e retomar a videoaula, com apresentação que evite a sobreposição entre a explicação e a fala do instrutor.
* **acceptance-criteria:** Executar tarefas de pausa, interrupção, repetição e retomada; verificar a posição de retorno e a ausência de reprodução concorrente não solicitada.

### RF5
* **short-description:** Oferecer uma visão geral e permitir acessar detalhes por trechos de descrição, sem exigir a reprodução integral a cada consulta.
* **long-description:** Oferecer uma visão geral e permitir acessar detalhes por trechos de descrição, sem exigir a reprodução integral a cada consulta.
* **acceptance-criteria:** Verificar se o usuário consegue ouvir novamente um trecho ou acessar detalhes mantendo a referência ao diagrama.

### RF6
* **short-description:** Reduzir descrições repetidas de um diagrama inalterado e atualizar a informação quando houver mudança relevante no conteúdo.
* **long-description:** Reduzir descrições repetidas de um diagrama inalterado e atualizar a informação quando houver mudança relevante no conteúdo.
* **acceptance-criteria:** Usar sequências com repetição, deslocamento de cursor e alteração real do modelo; verificar tanto repetições desnecessárias quanto mudanças ignoradas. 

### RF7
* **short-description:** Permitir ajustar a velocidade da síntese de voz e preservar uma configuração utilizável ao revisitar as descrições.
* **long-description:** Permitir ajustar a velocidade da síntese de voz e preservar uma configuração utilizável ao revisitar as descrições.
* **acceptance-criteria:** Verificar a alteração e a manutenção da velocidade nas reproduções seguintes; recolher a percepção de adequação do controle.


## 2. Non-Functional Requirements

### RNF1
* **short-description:** Permitir realizar os fluxos essenciais por teclado e leitor de tela, com controles identificáveis, foco previsível e feedback acessível de processamento, conclusão e falha.
* **long-description:** Permitir realizar os fluxos essenciais por teclado e leitor de tela, com controles identificáveis, foco previsível e feedback acessível de processamento, conclusão e falha.
* **acceptance-criteria:** Percorrer os fluxos essenciais sem mouse com as tecnologias assistivas definidas; registrar bloqueios, conflitos de atalhos, perda de foco e mensagens não anunciadas.

### RNF2
* **short-description:** Organizar as descrições em uma sequência compreensível, com termos consistentes e relações explicitadas, adequada à leitura linear e à síntese de voz.
* **long-description:** Organizar as descrições em uma sequência compreensível, com termos consistentes e relações explicitadas, adequada à leitura linear e à síntese de voz.
* **acceptance-criteria:** Revisar clareza, referências entre frases, ordem e uso dos termos; avaliar com estudantes com DV se conseguem acompanhar a informação apresentada.