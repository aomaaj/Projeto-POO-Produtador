# 📦 Produtador - Painel do Fornecedor (Android)

[![Kotlin](https://img.shields.io/badge/Kotlin-1.9%2B-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![Firebase](https://img.shields.io/badge/Backend-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)

Aplicativo complementar ao sistema de delivery de Gás & Água, voltado para os **produtores, distribuidoras e fornecedores**. Permite a gestão, inclusão e sincronização do catálogo de produtos comercializados no ecossistema.

---

## ✨ Funcionalidades

* ➕ **Cadastro de Novos Produtos**: Inclusão de nome, categoria (Água / Gás), preço unitário e descrição detalhada.
* 🖼️ **Upload de Imagens**: Seleção de fotos da galeria do aparelho com envio direto para o **Firebase Storage**.
* 🔄 **Sincronização em Tempo Real**: Os produtos salvos são gravados no **Cloud Firestore** e disponibilizados instantaneamente no app do cliente.
* ⚡ **Validações Nativas**: Prevenção de cadastro com campos em branco ou dados inconsistentes.

---

## 🛠️ Stack Tecnológica

* **Linguagem**: Kotlin
* **View Binding**: Acesso simplificado e seguro a views da interface.
* **Corrotinas Kotlin**: Execução assíncrona para upload de mídia e chamadas de rede sem bloquear a UI.
* **Firebase SDK**:
  * Cloud Firestore
  * Firebase Storage

---

## 🚀 Como Executar

1. Abra a pasta do projeto no **Android Studio**.
2. Adicione o seu `google-services.json` dentro da pasta `app/` (utilize o modelo `app/google-services.json.example` fornecido).
3. Sincronize as dependências do Gradle:
   ```bash
   ./gradlew assembleDebug
   ```
4. Execute no emulador ou dispositivo físico.

---

## 👨‍💻 Autor

Desenvolvido por **João Mateus** ([@aomaaj](https://github.com/aomaaj)).
