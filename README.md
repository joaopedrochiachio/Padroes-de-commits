# 📋 Guia de Labels para Commits

Este guia estabelece a padronização de labels para commits em projetos **Backend, Frontend e Mobile**. Inspirado no *Conventional Commits*, utilizamos emojis para facilitar a leitura visual do histórico do Git.

---

## 🎯 Labels Universais

| Emoji | Nome | Aplicação | Exemplo de Uso |
| :--- | :--- | :--- | :--- |
| ✨ | **feat** | Nova funcionalidade | `✨ feat: Login com Biometria` |
| 🐛 | **fix** | Correção de bugs | `🐛 fix: Validação de data inválida` |
| 📚 | **docs** | Documentação | `📚 docs: Atualiza diagrama de arquitetura` |
| ♻️ | **refactor** | Refatoração de código | `♻️ refactor: Remove código duplicado` |
| 🚧 | **wip** | Trabalho em progresso | `🚧 wip: Tela de pagamento (50%)` |
| 🔧 | **config** | Configurações do projeto | `🔧 config: Atualiza webpack para v5` |
| ⚡ | **perf** | Melhoria de performance | `⚡ perf: Reduz tempo de carga em 40%` |
| 🧪 | **test** | Adição ou alteração de testes | `🧪 test: Cobertura de testes para API` |

---

## ⚙️ Backend

| Emoji | Nome | Aplicação | Exemplo de Uso |
| :--- | :--- | :--- | :--- |
| 🔒 | **security** | Segurança e vulnerabilidades | `🔒 security: Adiciona sanitização de SQL` |
| 📡 | **endpoint** | Endpoints da API | `📡 endpoint: DELETE /api/users/{id}` |
| 💾 | **db** | Banco de Dados / Migrations | `💾 db: Migração para UUID` |
| 📦 | **package** | Pacotes e Integrações | `📦 package: Atualiza SDK do Twilio` |
| 📈 | **metrics** | Monitoramento e Logs | `📈 metrics: Configura New Relic` |
| 🧩 | **middleware** | Middlewares e Interceptors | `🧩 middleware: Rate limiter global` |

---

## 🎨 Frontend

| Emoji | Nome | Aplicação | Exemplo de Uso |
| :--- | :--- | :--- | :--- |
| 🎨 | **ui** | Interface e Estilização | `🎨 ui: Novo design da homepage` |
| 📱 | **responsive** | Ajustes de Responsividade | `📱 responsive: Grid ajustável para mobile` |
| 🖼️ | **assets** | Imagens, Ícones e Fontes | `🖼️ assets: Otimiza imagens em WebP` |
| 🌐 | **i18n** | Internacionalização | `🌐 i18n: Traduções para japonês` |
| 📡 | **api-call** | Consumo/Chamadas de API | `📡 api-call: Paginação na busca` |
| 📊 | **analytics** | Eventos e Rastreamento | `📊 analytics: Evento de scroll depth` |

---

## 📱 Mobile

| Emoji | Nome | Aplicação | Exemplo de Uso |
| :--- | :--- | :--- | :--- |
| 🤖 | **android** | Específico para Android | `🤖 android: Suporte a foldables` |
| 🍎 | **ios** | Específico para iOS | `🍎 ios: Dark mode dinâmico` |
| 📲 | **gesture** | Interações e Gestos | `📲 gesture: Double tap para like` |
| 📡 | **native-module** | Módulos Nativos | `📡 native-module: Integração com ARKit` |
| 🔔 | **push** | Notificações Push/Locais | `🔔 push: Notificação local agendada` |
| 📵 | **offline** | Funcionalidades Offline/Sync | `📵 offline: Sync automático` |

---

## 🛠️ Exemplo de Commit Completo

```bash
git commit -m "✨ feat(search): Adiciona filtro por geolocalização

- Implementa busca por raio de 10km
- Integra com Google Maps API
- Adiciona testes E2E

Refs: #45, #78"
