# 📚 Fine-Tuning de LLM para Geração e Resumo de Livros

Este notebook do **Google Colab** implementa o fine-tuning de um **Large Language Model (LLM)** utilizando **UnsLoTH** e **LoRA**, otimizando a geração de descrições de livros.  

## ✨ Funcionalidades  
✅ Monta o **Google Drive** para leitura e salvamento de dados  
✅ Processa um dataset JSON contendo **títulos e descrições de livros**  
✅ Carrega e configura modelos **Llama-3** e outras variantes compatíveis com **4-bit quantization**  
✅ Gera **descrições detalhadas** para títulos de livros  
✅ Realiza **fine-tuning** do modelo com **SFTTrainer** para aprimorar a geração de texto  
✅ Testa o modelo treinado em novas entradas

## 🚀 Como Usar  
1️⃣ **Configure** seu dataset no **Google Drive**  
2️⃣ **Execute** as células do notebook para **treinar o modelo**  
3️⃣ **Teste** a geração de descrições e resumos  
4️⃣ **Salve** o modelo treinado para inferência futura  

## 📂 Estrutura de Arquivos  
📌 `trn.json` – Dataset inicial com **títulos e descrições**  
📌 `amazon_titles_search.json` – Dataset processado  
📌 `formatted_amazon_titles_search_data.json` – Dados formatados para treinamento  
📌 `lora_model` – **Modelo treinado salvo**  

## 🛠 Tecnologias Utilizadas  
🔹 **Google Colab**  
🔹 **UnsLoTH**  
🔹 **LoRA**  
🔹 **Transformers**  
🔹 **Hugging Face Datasets**  
