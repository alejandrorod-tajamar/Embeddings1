# Embeddings 1

Para probar este proyecto, estos son los pasos a seguir:

1. Con una terminal de `Git Bash`, **clona** el repositorio:
   
   ```bash
   git clone https://github.com/alejandrorod-tajamar/Embeddings1.git
   ```
   
2. Abre una terminal de `Command Prompt`.
   
3. Navega al **directorio del proyecto**:
   
   ```cmd
   cd Embeddings1
   ```

4. Crea un **entorno virtual**:

   ```cmd
   python -m venv nombre_del_entorno
   ```

5. Activa el entorno virtual:

   ```cmd
   .\nombre_del_entorno\Scripts\activate
   ```

6. Instala en el entorno virtual el contenido del archivo `requirements.txt`:

   ```cmd
   pip install -r requirements.txt
   ```

7. Crea un archivo `config.json` en el directorio raíz del proyecto con el siguiente contenido, reemplazando con tu Endpoint y tu clave de API de Azure OpenAI:

   ```json
   {
    "EMBEDDINGS_MODEL": "text-embedding-ada-002",
    "OPENAI_API_BASE": "tu_endpoint",
    "OPENAI_API_KEY": "tu_clave_api",
    "OPENAI_API_VERSION": "2022-12-01"
   }
   ```

8. Sigue las instrucciones en (basic_embeddings_example_restapi.ipynb)[basic_embeddings_example_restapi.ipynb]
