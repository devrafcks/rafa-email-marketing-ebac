# Template de Email Marketing Responsivo
<img width="490" height="826" alt="image" src="https://github.com/user-attachments/assets/c8563354-e4b6-4b19-bab2-a2685ae3afe2" />


Este repositório apresenta um **template de email marketing completo e responsivo**, desenvolvido com foco em **HTML e CSS inline**. O objetivo principal é garantir a **máxima compatibilidade** e **renderização consistente** em uma ampla variedade de clientes de email (como Gmail, Outlook e Apple Mail), superando as limitações comuns de suporte a CSS externo.

## Características Técnicas

* **HTML e CSS Inline:** Adota rigorosamente o uso de estilos CSS diretamente nos atributos `style` dos elementos HTML. Esta abordagem é fundamental para contornar as restrições de muitos clientes de email que removem ou ignoram folhas de estilo externas e tags `<style>` no `<head>`.
* **Estrutura Baseada em Tabelas:** O layout do email é construído inteiramente com **tabelas HTML aninhadas (`<table>`)**. Esta é a técnica mais robusta e amplamente suportada para organizar o conteúdo de forma responsiva e consistente em diferentes ambientes de email, garantindo que os elementos se alinhem e se comportem como esperado.
* **Design Responsivo Híbrido:** Embora focado em CSS inline, o template incorpora princípios de design responsivo. Elementos como `width` e `max-width` em pixels, juntamente com `display: block` para imagens, são utilizados para adaptar o layout a diferentes tamanhos de tela.
* **Preheader Text:** Implementação de um texto preheader oculto (`<div style="display:none; ...">`) para otimizar a pré-visualização do email na caixa de entrada, fornecendo um resumo conciso antes mesmo da abertura.

## Conceitos Aplicados

Este projeto solidifica o entendimento sobre:

* A **arquitetura de HTML para email**: Diferenças e restrições em comparação com o desenvolvimento web tradicional.
* Técnicas de **compatibilidade cross-client**: Como garantir que um email se comporte de maneira previsível em diversas plataformas.
