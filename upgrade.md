# LangChain v1.0 Upgrade Summary

**Branch**: `langchain-v1.0`

---

## 📋 Overview

Successfully upgraded **ChatPPT** project from LangChain 0.2.16 to **LangChain 1.0.7** with full backward compatibility maintained. 

---

## 🔄 Version Changes
Upgrade python from v3.10 to v3.12

### **LangChain Core Updates**
| Package | Before | After | Change Type |
|---------|---------|--------|-------------|
| `langchain` | 0.2.16 | **1.0.7** | 🔺 Major Upgrade |
| `langchain_core` | 0.2.41 | **1.0.5** | 🔺 Major Upgrade |
| `langchain_openai` | 0.1.25 | **1.0.3** | 🔺 Major Upgrade |
| `langchain_community` | 0.2.17 | ❌ Removed | 🗑️ Cleanup (unused) |
| `langchain_ollama` | 0.1.3 | ❌ Removed | 🗑️ Cleanup (unused) |


### **Supporting Dependencies Updated**
| Package | Before | After | Reason |
|---------|---------|--------|---------|
| `gradio` | 5.1.0 | **5.7.0** | Compatibility & new features |
| `Pillow` | 9.1.0 | **11.0.0** | Security patches & compatibility |
| `torch` | 2.5.0 | **2.9.1** | Latest stable version |
| `torchvision` | 0.20.0 | **0.24.1** | Compatibility with torch 2.9.1 |
| `sentencepiece` | 0.1.99 | **0.2.1** | Stability improvements |
| `pydantic` |  | 2.10.6 | ✅ Gradio run in Python 3.12|
