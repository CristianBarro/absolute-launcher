# Absolute Launcher

![Absolute Launcher](docs/capa.jpg)

Launcher de Minecraft Java leve, feito em Tauri + Rust. Instâncias separadas, Fabric, Forge e NeoForge, e mods do Modrinth instalados direto pelo app.

## ⬇️ Download

Baixe a versão mais recente em **[Releases](../../releases/latest)**:

| Arquivo | Para quem |
| --- | --- |
| `Absolute-Launcher-0.1.0-setup.exe` | **Instalador** (recomendado). Cria atalho no menu Iniciar |
| `Absolute-Launcher-0.1.0-portatil.exe` | **Portátil**. Abre direto, sem instalar |

Requisitos: Windows 10/11 64 bits. O Java certo para cada versão do Minecraft é baixado automaticamente.

> O Windows pode mostrar "O Windows protegeu o computador" (SmartScreen) porque o app ainda não tem assinatura digital. Clique em **Mais informações → Executar assim mesmo**.

## Recursos

- **Instâncias** separadas (versão, loader, memória e pasta própria com mundos e mods)
- **Vanilla, Fabric, Forge e NeoForge**
- **Mods do Modrinth**: busca, instala com dependências, atualiza, ativa/desativa e remove
- **Pack de desempenho** em 1 clique: Sodium, Lithium, FerriteCore, EntityCulling, ImmediatelyFast, ModernFix
- **Java automático**: baixa o runtime oficial da Mojang certo para cada versão
- **Leve e rápido**: downloads paralelos, flags de memória ajustadas, cache compartilhado
- **Contas**: offline direto, e Microsoft opcional (skin oficial e servidores premium)

## Segurança

- Todo arquivo da Mojang é verificado por SHA-1, e mods do Modrinth por SHA-512
- Só baixa de fontes oficiais (Mojang, Fabric, Modrinth, Microsoft), sempre por HTTPS
- Sua senha nunca passa pelo launcher: o login é pelo site da Microsoft
- Sem telemetria: nada é enviado para outro lugar

## Código-fonte

Este repositório só distribui os executáveis. O código-fonte ainda não foi publicado.

---

Feito por **Cristian**.
