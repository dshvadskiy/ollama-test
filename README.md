# ollama-test
From https://blog.llamaindex.ai/running-mixtral-8x7-locally-with-llamaindex-e6cebeabe0ab

1. Start Ollama

        ollama run mistral

2. Install requirements

        pip install -r requiremnts.txt

3. Run test
    
        python ollama_test.py

4. Load Data

        python load_index.py

5. Run flask app

        python app.py

6. Test app


        curl -X POST 'http://127.0.0.1:5000/process_form' --form 'query="What does the author think about Star Trek?"'