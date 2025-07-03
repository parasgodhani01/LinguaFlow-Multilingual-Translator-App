# Linguaflow  Multilingual Translator 

Linguaflow is a robust multilingual translation API developed using FastAPI and the MarianMT models from Hugging Face's Transformers library. It provides seamless and efficient translation services between English and multiple target languages, including French, Portuguese, and Spanish.

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



