# Projeto de receitas
Gerador de Posts de Receitas com Agentes de IA

#Visão Geral

Este projeto utiliza uma série de agentes de inteligência artificial para automatizar o processo de criação de posts de receitas para um site. O sistema é composto por três agentes principais:

Agente Buscador de Receitas: Responsável por pesquisar receitas online com base em um ingrediente principal fornecido pelo usuário.
Agente Buscador de Imagens de Receitas: Encontra imagens relevantes para a receita identificada pelo primeiro agente.
Agente Criador de Post de Receita para Site: Combina as informações da receita e a URL da imagem para gerar um post formatado para um site.

#Tecnologias Utilizadas

Python: Linguagem de programação principal.
google-generativeai: Biblioteca para interagir com os modelos generativos do Google (como o Gemini), utilizada para criar os agentes de IA.
genai.model.Agent: Classe da biblioteca google-generativeai para definir e executar os agentes.
genai.tool.GoogleSearch: Ferramenta para permitir que os agentes realizem buscas no Google.
