# Linguaflow  Multilingual Translator 

Linguaflow is a robust multilingual translation API developed using FastAPI and the MarianMT models from Hugging Face's Transformers library. It provides seamless and efficient translation services between English and multiple target languages, including French, Portuguese, and Spanish.

Designed for speed and scalability, Linguaflow exposes RESTful endpoints that allow developers to easily integrate real-time translation capabilities into their applications. Under the hood, it leverages the power of MarianMT pretrained neural machine translation models optimized for high-quality multilingual translation tasks.
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



