## Pre-Requisites
- Install dependencies `pip install -r requirements.txt`
- Copy/rename `config.json.example` to `config.json` and populate
  - Redis connection is **optional**
- Copy/rename `requests.json.example` to `requests.json`
- Copy/rename `denied.json.example` to `denied.json` 
- Run it `uvicorn main:app --port <YOUR_PORT_HERE> --host 0.0.0.0 --reload`
- Check it out at `https://<yourDomain>.com/docs`
