![Perfil de Wilmer](https://avatars.githubusercontent.com/u/44853160?s=128)

# 👋 Hi, I’m Wilmer (@wilmerm)

Soy un desarrollador apasionado por crear soluciones prácticas y eficientes. Trabajo principalmente con **Python** y **Django**, **Vue.js**, **JavaScript** y **TypeScript**.

## 🚀 Repositorios Destacados

### 🔗 [**alanube-python**](https://github.com/wilmerm/alanube-python)  
  Librería Python para conectar con la API de [Alanube](https://www.alanube.co/), compatible con servicios de facturación electrónica.  
  _Python · API Client · Electrónica_

  ```py
  # Import the Alanube class specific to the country,
  # in this case from `alanube.do` for the Dominican Republic
  from alanube.do import Alanube
  
  # Connect to the API
  Alanube.connect("[TOKEN]")
  
  payload = {...}
  
  data = Alanube.send_document(encf_type=31, payload)
  ```

---

### 🔗 [**django-survey**](https://github.com/wilmerm/django-survey)  
  Aplicación Django para crear encuestas, recolectar respuestas y generar reportes estadísticos.  
  _Django · Encuestas · Open Source_

  ```py
  from survey.models import Survey, SurveyOption

  survey = Survey.objects.create(
      title='Test Survey',
      description='Survey Description',
  )
  
  for i in range(1, 5):
      SurveyOption.objects.create(
          survey=survey,
          title=f'Option {i}',
          description=f'Option {i} Description',
      )
  ```

  ![image](https://github.com/user-attachments/assets/7f334515-3a99-4553-9e00-255f13b6da98)

---

### 🔗 [**django-tours**](https://github.com/wilmerm/django-tours)  
  App Django para mostrar recorridos guiados con Shepherd.js.  
  _Django · Tours · UI Help_

  ![django-tours-1](https://github.com/wilmerm/django-tours/assets/44853160/d7a8c20f-ddb1-4f93-b287-e143813aef95)

---

### 🔗 [**cryptshield**](https://github.com/wilmerm/cryptshield)  
  Aplicación CLI para cifrado y eliminación segura de archivos en Linux.  
  _CLI · Cifrado · Seguridad_

  ```bash
  # Encrypt a file
  cryptshield encrypt /path/to/file secret_key
  
  # Decrypt a file
  cryptshield decrypt /path/to/file.encrypted secret_key
  
  # Encrypt a text
  cryptshield encrypt_text "Sample text" secret_key
  "gAAAAABnsO0xV07ndDmt-fO..."
  
  # Decrypt a text
  cryptshield decrypt_text "gAAAAABnsO0xV07ndDmt-fO..." secret_key
  "Sample text"
  
  # Secure file deletion
  cryptshield delete /path/to/file
  ```

## 📬 Contacto

Si quieres ponerte en contacto conmigo para colaboraciones, proyectos o consultas técnicas, puedes escribirme a:

**wilmermorelmartinez [at] gmail.com**



<!---
wilmerm/wilmerm is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
