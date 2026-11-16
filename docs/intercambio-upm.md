```mermaid
flowchart TD
    A["Tenho uma página HTML"] --> B{"Quem deve ver?"}

    B -->|"Só eu"| C["Artifact privado no claude.ai"]
    C --> D["Cópia de segurança no repositório privado do GitHub"]

    B -->|"Só quem receber o link"| E["Artifact no claude.ai"]
    E --> F["Compartilhar: aberto para quem tem o link"]
    F --> G["Copiar e mandar o link"]
    G --> H["Depois: voltar para privado, se quiser"]

    B -->|"Uma pessoa, sem link"| I["Mandar o arquivo .html por e-mail ou WhatsApp"]
    I --> J["A pessoa recebe uma cópia que não se atualiza"]

    B -->|"Qualquer pessoa: vitrine"| K{"Tem dado pessoal? E-mail, celular, IDs"}
    K -->|"Sim"| L["Tirar antes: skill revisar-seguranca"]
    L --> M["Repositório público com GitHub Pages"]
    K -->|"Não"| M
    M --> N["Aparece no seu perfil, e o código fica visível"]
```

## Regras
- Repositório privado: gaveta. Guarda, não compartilha.
- Artifact: link. Cada página abre ou fecha separadamente.
- Repositório público: vitrine. Todo mundo que entra no seu perfil vê.
```
