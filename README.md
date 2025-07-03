# Linguaflow  Multilingual Translator 

Linguaflow is a multilingual translation API built using FastAPI and MarianMT from Hugging Face Transformers. This project enables translation between English and other languages like French, Portuguese, and Spanish. The project was developed as part of a course at **Grow Data Skills**.

---

## Features
- Translate text from English to other languages.
- Supported languages: French, Portuguese, Spanish.
- Simple and efficient API.

---


#### Sample Payload:
```json
{
  "src_text": [">>esp<< This is a test sentence to translate to Spanish."]
}
```

#### Sample Response:
```json
{
  "translated_text": ["Esta es una frase de prueba para traducir al español."]
}
```

---

## Project Structure
```
Linguaflow/
│
├── app/
│   ├── main.py         # FastAPI application code
│
├── requirements.txt    # Dependency list
├── README.md           # Project documentation
```



